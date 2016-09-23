#### Test 8633324603eeb8f_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 09:42:09.084   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-23 09:42:09.084   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 09:42:09.553  5433  5433 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 09:42:09.559  5433  5433 D AndroidRuntime: CheckJNI is OFF
09-23 09:42:09.586  5433  5433 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 09:42:09.616  5433  5433 I Radio-JNI: register_android_hardware_Radio DONE
09-23 09:42:09.631  5433  5433 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 09:42:09.633   928  3559 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 09:42:09.680   928  3559 I ActivityManager: Start proc 5442:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 09:42:09.684  5433  5433 D AndroidRuntime: Shutting down VM
,09-23 09:42:10.025   928   939 I WindowManager: Screenshot max retries 4 of Token{454ef37 ActivityRecord{a508436 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{147e40e u0 Starting com.test.thalitest} drawState=4
,09-23 09:42:10.093  5442  5442 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 09:42:10.131  5442  5442 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 09:42:10.154  5442  5442 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 349-367)
,09-23 09:42:10.154  5442  5442 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 09:42:10.171  5442  5442 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4f6497f}
,09-23 09:42:10.171  5442  5442 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 09:42:10.172  5442  5442 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 09:42:10.175  5442  5442 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 09:42:10.176  5442  5442 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 09:42:10.208  5442  5442 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 09:42:10.219  5442  5442 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 09:42:10.219  5442  5442 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 09:42:10.219  5442  5442 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 09:42:10.219  5442  5442 I Adreno  : Build Date                       : 12/06/15
09-23 09:42:10.219  5442  5442 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 09:42:10.219  5442  5442 I Adreno  : Local Branch                     : mybranch17112971
09-23 09:42:10.219  5442  5442 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 09:42:10.219  5442  5442 I Adreno  : Remote Branch                    : NONE
09-23 09:42:10.219  5442  5442 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 09:42:10.250   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4cbd07d:true
,09-23 09:42:10.281   404   404 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24311]" dev="sockfs" ino=24311 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 09:42:10.281   404   404 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[24311]" dev="sockfs" ino=24311 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 09:42:10.293  5442  5442 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 09:42:10.301  5442  5442 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 09:42:10.321   402   402 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31654]" dev="sockfs" ino=31654 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 09:42:10.321   402   402 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31654]" dev="sockfs" ino=31654 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 09:42:10.324  5442  5479 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 09:42:10.324  5210  5210 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[29818]" dev="sockfs" ino=29818 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 09:42:10.324  5210  5210 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29818]" dev="sockfs" ino=29818 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 09:42:10.329  5442  5466 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 09:42:10.364  5442  5479 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 09:42:10.432   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +405ms (total +785ms)
,09-23 09:42:10.454  5442  5442 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5442
,09-23 09:42:10.585  5442  5442 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 09:42:10.679  5442  5482 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -560985808
,09-23 09:42:10.682  5442  5482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 09:42:10.682  5442  5482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 09:42:10.682  5442  5482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 09:42:10.682  5442  5482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 09:42:10.682  5442  5482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 09:42:10.682  5442  5482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efbb00d added. We now have 1 listener(s)
,09-23 09:42:10.685  5442  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 09:42:10.685  5442  5482 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:42:10.685  5442  5482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:42:10.686  5442  5482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 09:42:10.688  5442  5482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9a2d10 added. We now have 1 listener(s)
09-23 09:42:10.688  5442  5482 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:42:10.692   928  2976 D WifiService: New client listening to asynchronous messages
,09-23 09:42:10.692  5442  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:42:10.692  5442  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 09:42:10.692  5442  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 09:42:10.692  5442  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 09:42:10.692  5442  5482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 09:42:10.694  5442  5482 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:10.694  5442  5482 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 09:42:10.698  5442  5482 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:10.698  5442  5482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:10.698  5442  5482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 09:42:10.698  5442  5482 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:42:10.698  5442  5482 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 09:42:10.764  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:10.767  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:10.769  5442  5442 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 09:42:10.823   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:42:10.979  5442  5488 W jxcore-log: Initializing JXcore engine
09-23 09:42:10.979  5442  5488 W jxcore-log: JXcore engine is ready
,09-23 09:42:11.001  5488  5488 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 09:42:11.001  5488  5488 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[18524]" dev="sockfs" ino=18524 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 09:42:11.001  5488  5488 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 09:42:11.004  5488  5488 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32168]" dev="sockfs" ino=32168 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 09:42:11.012  5442  5488 W jxcore-log: Starting JXcore engine
,09-23 09:42:11.068  5442  5488 W jxcore-log: Platform android
09-23 09:42:11.068  5442  5488 W jxcore-log: 
,09-23 09:42:11.068  5442  5488 W jxcore-log: Process ARCH arm
09-23 09:42:11.068  5442  5488 W jxcore-log: 
,09-23 09:42:11.167  5442  5488 I jxcore-log: JXcore Cordova bridge is ready!
09-23 09:42:11.167  5442  5488 I jxcore-log: 
,09-23 09:42:11.167  5442  5488 W jxcore-log: JXcore engine is started
,09-23 09:42:11.171  5442  5482 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 09:42:11.174  5442  5442 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 09:42:19.085   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:20.087   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:20.802  5442  5488 I jxcore-log: 2016-09-23 13:42:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 09:42:20.802  5442  5488 I jxcore-log: 
,09-23 09:42:20.804  5442  5488 I jxcore-log: 2016-09-23 13:42:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 09:42:20.804  5442  5488 I jxcore-log: 
,09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:20.808  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:42:20.810  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:42:20.811  5442  5488 I jxcore-log: 2016-09-23 13:42:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 09:42:20.811  5442  5488 I jxcore-log: 
,09-23 09:42:20.813  5442  5488 I jxcore-log: 2016-09-23 13:42:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 09:42:20.813  5442  5488 I jxcore-log: 
,09-23 09:42:21.065  5442  5488 I jxcore-log: Running unit tests
09-23 09:42:21.065  5442  5488 I jxcore-log: 
,09-23 09:42:21.065  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:42:21.066  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d823395 added. We now have 2 listener(s)
,09-23 09:42:21.067  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:42:21.067  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 09:42:21.067  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:42:21.067  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:42:21.067  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6658caa added. We now have 2 listener(s)
09-23 09:42:21.067  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:42:21.068  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:42:21.070  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:21.073  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:21.074  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:21.074  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 09:42:21.074  5442  5488 D executeNativeTests: Running unit tests
,09-23 09:42:21.081  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:21.087  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:21.088   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:21.114  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:42:21.114  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 added. We now have 3 listener(s)
09-23 09:42:21.115  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:42:21.115  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 09:42:21.115  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:42:21.115  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:42:21.115  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 added. We now have 3 listener(s)
,09-23 09:42:21.115  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:42:21.115  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:42:21.117  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:21.119  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:21.120  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:21.120  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 09:42:21.122  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 09:42:21.122  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:42:21.122  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:42:21.122  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:42:21.122  5442  5488 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 09:42:21.123  5442  5488 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-23 09:42:21.123  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 09:42:21.123  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:42:21.123  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:42:21.123  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:42:21.123  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:42:21.123  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:21.123  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:21.123  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:21.123  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.123  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:21.123  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 09:42:21.124  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 removed from the list
09-23 09:42:21.124  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:21.124  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 removed from the list
09-23 09:42:21.125  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:21.125  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:21.125  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:21.125  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.125  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:21.129  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:21.130  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:21.130  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:21.130  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:21.130  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:21.132  5442  5488 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 09:42:21.133  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:21.133  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:21.133  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:21.134  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:21.134  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.134  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:21.134  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:21.134  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:21.134  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:21.134  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:21.134  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.134  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:21.134  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.134  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:21.134  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:21.134  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:21.134  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:21.134  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 09:42:21.137  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 09:42:21.138  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:21.138  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:21.138  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:21.138  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:21.138  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.138  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:21.138  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:21.138  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:21.138  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:21.138  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:21.138  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.138  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:21.138  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:21.138  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:21.139  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:21.139  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:21.139  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:21.139  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:21.139  5442  5488 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 09:42:21.141  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:21.143  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:21.144  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:21.144  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:42:21.144  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:42:21.144  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:42:21.144  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:42:21.144  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:21.144  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:42:21.147  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:21.147  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:42:21.148  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:21.151  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:21.151  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:42:21.154  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:42:21.155  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:42:21.157  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 09:42:21.161  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 09:42:21.161  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 09:42:21.161  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:42:21.162  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:42:21.163  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:21.167  4468  4481 D BtGatt.GattService: registerClient() - UUID=377f2080-9544-4873-ab1f-1ec01270d914
,09-23 09:42:21.169  4468  4542 D BtGatt.GattService: onClientRegistered() - UUID=377f2080-9544-4873-ab1f-1ec01270d914, clientIf=5
09-23 09:42:21.170  5442  5452 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 09:42:21.171  4468  4482 D BtGatt.GattService: start scan with filters
09-23 09:42:21.175  4468  4546 D BtGatt.ScanManager: handling starting scan
09-23 09:42:21.175  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:42:21.176  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 09:42:21.176  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:42:21.176  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 09:42:21.177  4468  4546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:42:21.177  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:42:21.177  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:42:21.177  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:42:21.177  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:42:21.179  5442  5488 I io.jxcore.node.ConnectionHelper: start: OK
09-23 09:42:21.185  4468  4542 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:42:21.186  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:21.186  4468  4546 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-23 09:42:21.193  4468  4542 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 09:42:21.193  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:21.193  4468  4546 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:42:21.193  4468  4546 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 09:42:21.205  4468  4542 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 09:42:21.205  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:21.212  4468  4542 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 09:42:21.212  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:21.654   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:42:21.678  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 09:42:21.678  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:42:21.678  5442  5442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:42:22.088   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:23.090   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:24.090   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 09:42:24.680   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:42:26.183  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:42:26.183  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:26.183  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:42:26.183  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:26.183  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:42:26.184  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:42:26.184  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 09:42:26.184  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:42:26.184  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:42:26.184  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:42:26.185  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:42:26.186  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:42:26.186  4468  4481 D BtGatt.GattService: stopScan() - queue size =1
09-23 09:42:26.187  4468  4482 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:42:26.188  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:26.188  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:42:26.188  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:42:26.188  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:42:26.188  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:42:26.190  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:42:26.190  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:26.190  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:42:26.190  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:26.191  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:26.192  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:26.192  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:26.193  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:26.193  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:26.193  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:42:26.193  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:26.193  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:26.193  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:26.194  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:26.194  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:26.194  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:42:26.195  4468  4468 D BtGatt.ScanManager: awakened up at time 236409
,09-23 09:42:26.204  4468  4542 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:42:26.205  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:26.205  4468  4546 D BtGatt.ScanManager: stopping BLe Batch
09-23 09:42:26.206  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:26.206  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:42:26.213  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:42:26.214  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:42:26.215  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:42:26.215  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:26.215  4468  4542 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:42:26.215  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:26.216  4468  4546 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 09:42:26.216  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:26.220  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 09:42:26.220  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:26.220  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:42:26.225  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:42:26.225  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:26.227  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:26.229  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:42:26.245  4468  4542 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-23 09:42:26.245  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:26.245  4468  4542 D BtGatt.GattService: current time is 236459127320
09-23 09:42:26.246  4468  4542 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -71, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -75, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -52, 11, 57, -70, 107, -17, 1, 0, -98, 75, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, -46, -4, -117, 6, 105, -37, 1, -128, -74, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 09:42:26.247  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 09:42:26.248  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 09:42:26.248  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 09:42:26.248  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 09:42:26.249  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 09:42:26.249  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 09:42:26.249  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-23 09:42:26.731  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:42:27.712   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:42:29.091   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:30.093   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:31.094   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:31.195  5442  5488 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 09:42:31.200  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:31.213  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:42:31.217  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:42:31.218  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:42:31.218  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:42:31.218  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:42:31.218  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:42:31.218  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:31.218  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:42:31.223  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:31.226  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:42:31.230  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:31.235  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:42:31.235  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:42:31.235  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:42:31.236  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:42:31.240  4468  4699 D BtGatt.GattService: registerClient() - UUID=5d9baf52-df97-4e65-bd05-5c38e0d1f6a0
,09-23 09:42:31.241  4468  4542 D BtGatt.GattService: onClientRegistered() - UUID=5d9baf52-df97-4e65-bd05-5c38e0d1f6a0, clientIf=5
,09-23 09:42:31.241  5442  5452 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 09:42:31.242  4468  4481 D BtGatt.GattService: start scan with filters
09-23 09:42:31.247  4468  4546 D BtGatt.ScanManager: handling starting scan
,09-23 09:42:31.247  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:42:31.247  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 09:42:31.247  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:42:31.247  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 09:42:31.251  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:42:31.252  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:42:31.252  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:42:31.254  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:42:31.256  4468  4542 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:42:31.256  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.257  4468  4546 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:42:31.258  5442  5488 I io.jxcore.node.ConnectionHelper: start: OK
09-23 09:42:31.262  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:31.262  5442  5488 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-23 09:42:31.262  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:31.262  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:42:31.262  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:31.262  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:42:31.262  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-23 09:42:31.263  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:42:31.263  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:42:31.263  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:42:31.263  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:42:31.263  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:42:31.264  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:31.265  4468  4699 D BtGatt.GattService: stopScan() - queue size =1
09-23 09:42:31.265  4468  4542 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 09:42:31.265  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.265  4468  4481 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:42:31.266  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:31.266  4468  4546 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:42:31.266  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:42:31.266  4468  4546 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 09:42:31.266  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:42:31.266  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:42:31.266  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:42:31.270  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:42:31.270  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:31.270  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:42:31.270  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:31.271  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:31.272  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:31.272  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:31.272  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:31.272  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:31.272  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:31.272  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:31.272  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:31.273  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:42:31.273  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:31.273  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:31.273  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:42:31.277  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:31.277  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:42:31.280  4468  4542 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 09:42:31.281  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:31.282  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:42:31.284  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:42:31.284  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:42:31.284  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:31.285  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:31.288  4468  4542 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 09:42:31.288  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:31.290  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:31.290  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:31.290  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:42:31.293  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:31.293  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:31.294  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:31.296  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:42:31.296  4468  4542 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:42:31.296  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:31.296  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.296  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:31.296  4468  4546 D BtGatt.ScanManager: stopping BLe Batch
,09-23 09:42:31.298  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:42:31.298  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:31.298  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:31.299  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:31.299  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:31.299  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:31.299  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:31.299  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:31.300  5442  5488 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 09:42:31.302  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:31.304  4468  4542 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:42:31.304  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.304  4468  4546 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:31.309  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:31.310  4468  4542 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-23 09:42:31.310  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.311  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:31.311  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:42:31.312  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:42:31.312  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:42:31.312  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:42:31.312  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:31.312  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:42:31.314  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:31.316  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:42:31.316  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:31.320  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:42:31.320  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:42:31.320  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:42:31.321  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:42:31.322  4468  4699 D BtGatt.GattService: registerClient() - UUID=fa90c103-9fc0-4281-bb3a-5b05bb70bc7b
09-23 09:42:31.323  4468  4542 D BtGatt.GattService: onClientRegistered() - UUID=fa90c103-9fc0-4281-bb3a-5b05bb70bc7b, clientIf=5
,09-23 09:42:31.323  5442  5453 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 09:42:31.324  4468  4482 D BtGatt.GattService: start scan with filters
,09-23 09:42:31.326  4468  4546 D BtGatt.ScanManager: handling starting scan
09-23 09:42:31.327  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:42:31.327  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 09:42:31.327  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:42:31.327  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 09:42:31.329  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:42:31.329  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:42:31.329  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:42:31.331  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:42:31.332  4468  4542 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:42:31.332  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.333  4468  4546 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:42:31.333  5442  5488 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 09:42:31.338  4468  4542 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 09:42:31.338  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:31.339  4468  4546 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:42:31.339  4468  4546 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 09:42:31.349  4468  4542 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 09:42:31.349  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:31.354  4468  4542 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 09:42:31.354  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:31.831  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-23 09:42:31.831  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:42:31.831  5442  5442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:42:32.096   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:33.097   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:34.098   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-23 09:42:36.334  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:36.334  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:42:36.334  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:42:36.334  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:36.335  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 09:42:36.335  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:42:36.335  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 09:42:36.335  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:42:36.335  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:42:36.335  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:42:36.335  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:42:36.338  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:36.340  4468  4481 D BtGatt.GattService: stopScan() - queue size =1
09-23 09:42:36.343  4468  4720 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:42:36.344  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:42:36.344  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:42:36.344  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:42:36.344  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:42:36.344  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:42:36.346  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:42:36.347  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:36.347  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:42:36.347  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:42:36.348  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:36.348  4468  4468 D BtGatt.ScanManager: awakened up at time 246562
09-23 09:42:36.350  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:36.351  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:36.351  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:42:36.356  4468  4542 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:42:36.356  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:36.356  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:36.356  4468  4546 D BtGatt.ScanManager: stopping BLe Batch
09-23 09:42:36.356  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:42:36.363  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:42:36.365  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:42:36.365  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:42:36.365  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:36.366  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:36.366  4468  4542 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:42:36.366  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:42:36.366  4468  4546 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 09:42:36.370  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:36.370  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:36.370  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:42:36.375  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:36.375  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:36.376  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:36.379  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:42:36.393  4468  4542 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-23 09:42:36.393  4468  4542 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:42:36.393  4468  4542 D BtGatt.GattService: current time is 246607273569
09-23 09:42:36.393  4468  4542 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -75, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -71, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -94, 65, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 09:42:36.394  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 09:42:36.394  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 09:42:36.394  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 09:42:36.394  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 09:42:36.395  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-23 09:42:36.395  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 09:42:36.395  4468  4542 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,09-23 09:42:36.881  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:42:36.881  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:36.881  5442  5442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:42:41.352  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.352  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.352  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-23 09:42:41.353  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.353  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.353  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:41.353  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.353  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:42:41.354  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.354  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.354  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.355  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.355  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.359  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.359  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:42:41.359  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.361  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.361  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.361  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:42:41.361  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.361  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.363  5442  5488 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-23 09:42:41.364  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.365  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.365  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-23 09:42:41.365  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.365  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.365  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.366  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.366  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.366  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.366  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.366  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.366  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:41.367  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.367  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.369  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.369  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.369  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:42:41.371  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.371  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.371  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:41.371  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.371  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.373  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 09:42:41.373  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:42:41.373  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.373  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.373  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.373  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.373  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.373  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.373  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.373  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.373  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.373  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.374  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.374  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:41.374  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.375  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.375  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.375  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:42:41.376  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.376  5442  5488 D BluetoothLeScanner: could not find callback wrapper
,09-23 09:42:41.376  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:41.376  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.376  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.377  5442  5488 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 09:42:41.377  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.377  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.377  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.378  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.378  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.378  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.378  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.378  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.378  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.378  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:42:41.378  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.378  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.378  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.378  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.380  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.380  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.380  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.381  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.381  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.381  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:41.381  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.381  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:41.382  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-23 09:42:41.383  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.383  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.383  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.383  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.383  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:41.383  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.389  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
,09-23 09:42:41.389  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.389  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.389  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.389  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.389  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.389  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.389  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.391  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.391  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.391  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.391  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.392  5442  5488 D BluetoothLeScanner: could not find callback wrapper
,09-23 09:42:41.392  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:41.392  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.392  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.393  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 09:42:41.393  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 09:42:41.393  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:42:41.394  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 09:42:41.394  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:42:41.394  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:42:41.395  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 09:42:41.395  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:42:41.395  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:42:41.395  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.395  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.395  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.395  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.395  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.395  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.395  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
,09-23 09:42:41.395  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.396  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.396  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.396  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.396  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.397  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.397  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:41.399  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.399  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.399  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.400  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.400  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.400  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:42:41.400  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.400  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.401  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:42:41.401  5442  5488 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 09:42:41.401  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 09:42:41.407  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-23 09:42:41.407  5442  5488 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-23 09:42:41.407  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 09:42:41.408  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 09:42:41.409  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 09:42:41.409  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-23 09:42:41.410  5442  5488 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-23 09:42:41.410  5442  5488 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 09:42:41.410  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:42:41.410  5442  5488 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 09:42:41.410  5442  5488 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 09:42:41.410  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:42:41.410  5442  5488 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 09:42:41.411  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-23 09:42:41.415  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-23 09:42:41.415  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-23 09:42:41.415  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-23 09:42:41.416  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 09:42:41.416  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-23 09:42:41.416  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-23 09:42:41.416  5442  5488 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:42:41.417  5442  5488 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 09:42:41.417  5442  5489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-23 09:42:41.417  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.418  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.418  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.418  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.418  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.418  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.418  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 09:42:41.419  5442  5489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:42:41.419  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.419  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.419  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.419  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.419  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.419  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.419  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.419  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.420  5442  5490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-23 09:42:41.420  5442  5490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-23 09:42:41.420  5442  5490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-23 09:42:41.420  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.420  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.420  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.421  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.421  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.421  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:41.421  5442,  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.421  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.422  5442  5488 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 09:42:41.422  5442  5489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-23 09:42:41.417  4720  4720 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28646]" dev="sockfs" ino=28646 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:42:41.417  4720  4720 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28646]" dev="sockfs" ino=28646 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:42:41.423  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.423  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.423  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.423  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.423  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.424  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.424  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.424  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.424  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.424  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.424  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.424  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.424  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.424  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.425  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.425  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.425  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.426  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.426  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.426  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:42:41.426  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.426  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.428  5442  5488 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-23 09:42:41.428  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.428  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.428  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.428  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.428  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.428  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.428  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.428  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.428  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:41.428  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.428  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.428  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.428  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.429  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.430  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.430  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.430  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:42:41.431  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.431  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.431  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:42:41.431  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.431  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.432  5442  5488 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 09:42:41.432  5442  5488 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 09:42:41.432  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 09:42:41.432  5442  5488 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 09:42:41.432  5442  5488 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 09:42:41.432  5442  5488 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 09:42:41.432  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 09:42:41.432  5442  5488 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 09:42:41.432  5442  5488 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 09:42:41.432  5442  5488 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 09:42:41.433  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-23 09:42:41.433  5442  5488 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 09:42:41.433  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:41.433  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:41.433  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:41.433  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.433  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.433  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.434  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.434  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.434  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.434  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.434  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:41.434  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.434  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.434  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.435  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:41.435  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:41.435  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:41.435  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:41.435  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:41.435  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:41.435  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.435  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:41.436  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:41.436  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.436  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:41.436  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:41.436  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:41.436  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:41.436  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:41.436  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:41.436  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:44.099   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:45.100   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:46.101   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:46.437  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:42:46.437  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:46.438  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:46.438  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.438  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:46.438  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.438  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:46.439  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:46.439  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:46.439  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:42:46.439  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.439  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.440  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.440  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.440  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:46.440  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:46.440  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.440  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.440  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:46.441  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.443  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:42:46.444  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:42:46.444  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:46.446  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:46.446  5442  5488 D BluetoothLeScanner: could not find callback wrapper
,09-23 09:42:46.446  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:46.446  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.447  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:46.452  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 09:42:46.453  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:42:46.454  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 09:42:46.456  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 09:42:46.456  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-23 09:42:46.457  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 09:42:46.457  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:42:46.457  5442  5442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 09:42:46.458  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:46.458  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 09:42:46.458  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 09:42:46.458  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 09:42:46.458  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:46.458  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 09:42:46.458  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.459  5442  5442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 09:42:46.459  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.459  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:42:46.459  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:42:46.459  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:42:46.459  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 09:42:46.459  5442  5491 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:42:46.461  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:46.461  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:46.461  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:46.461  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:46.462  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:42:46.462  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.462  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.461  4481  4481 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29579]" dev="sockfs" ino=29579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:42:46.461  4481  4481 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29579]" dev="sockfs" ino=29579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:42:46.464  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:42:46.464  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:46.464  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:46.464  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:46.464  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:46.464  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:42:46.464  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:46.464  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:46.464  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:46.464  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.465  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:46.465  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.465  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.465  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:46.465  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:46.465  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.465  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:46.466  5442  5491 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 09:42:46.467  5442  5491 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 09:42:46.467  5442  5491 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 09:42:46.469  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:46.469  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:42:46.476  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:42:46.477  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:42:46.477  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:42:46.477  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:46.478  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.480  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.480  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:46.481  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:42:46.481  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:46.481  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:42:46.482  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:42:46.483  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:46.483  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:46.483  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.483  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:42:46.483  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:46.483  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:42:46.483  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:42:46.484  5442  5488 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-23 09:42:46.484  5442  5488 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 09:42:46.485  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 09:42:46.485  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-23 09:42:46.485  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:42:46.485  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:46.485  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:46.485  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:46.485  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:46.485  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.485  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:46.485  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.485  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:42:46.486  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:46.486  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:46.486  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.487  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:42:46.487  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:42:46.487  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:42:46.488  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:46.492  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:46.492  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:42:46.492  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.492  5442  5442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 09:42:46.493  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:46.493  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:42:46.493  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:46.494  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:46.494  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:46.494  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:46.494  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.494  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:46.498  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:42:46.498  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:46.498  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:46.498  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:46.499  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.499  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.499  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.499  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.499  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:46.499  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:46.499  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.499  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.499  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.499  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.500  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:42:46.501  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:46.501  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:46.501  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:42:46.501  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:46.501  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:46.501  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.501  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:46.503  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:42:46.504  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:42:46.504  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:42:46.504  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:42:46.504  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.504  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.504  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ff368 not in the list
09-23 09:42:46.504  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.504  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
,09-23 09:42:46.504  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:46.504  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.504  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.504  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:46.504  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:46.506  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:42:46.506  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:42:46.506  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:42:46.508  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:42:46.508  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:42:46.508  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:42:46.508  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:42:46.508  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb48381 not in the list
09-23 09:42:46.510  5442  5488 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-23 09:42:46.510  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 09:42:46.510  5442  5488 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 09:42:46.510  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 09:42:46.510  5442  5488 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-23 09:42:46.510  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-23 09:42:46.513  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-23 09:42:46.514  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-23 09:42:46.514  5442  5488 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-23 09:42:46.514  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 09:42:46.514  5442  5488 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-23 09:42:46.515  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 09:42:46.515  5442  5488 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-23 09:42:46.515  5442  5488 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-23 09:42:46.515  5442  5488 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-23 09:42:46.515  5442  5488 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 09:42:46.516  5442  5488 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 09:42:46.516  5442  5488 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-23 09:42:46.516  5442  5488 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 09:42:46.516  5442  5488 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-23 09:42:46.519  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:42:46.520  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a1344f added. We now have 3 listener(s)
09-23 09:42:46.520  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:42:46.522  5442  5488 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 09:42:46.523   928  3409 D WifiService: setWifiEnabled: true pid=5442, uid=10077
09-23 09:42:46.523   928  3409 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:42:46.546  4468  4673 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-23 09:42:46.546  4468  4679 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-23 09:42:46.993  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:42:47.102   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:48.103   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:42:49.103   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-23 09:42:50.827   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:42:51.528  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:42:51.529  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ead87dc added. We now have 4 listener(s)
,09-23 09:42:51.529  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:42:51.544  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:42:51.544  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ead87dc removed from the list
09-23 09:42:51.544  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:42:51.544  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:42:51.545  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:42:51.546  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:42:51.546  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f7010e5 added. We now have 4 listener(s)
09-23 09:42:51.547  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:42:51.550  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:42:51.550  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f7010e5 removed from the list
09-23 09:42:51.550  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:42:51.550  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:42:51.550  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:42:51.552  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:42:51.552  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dfb27ba added. We now have 4 listener(s)
09-23 09:42:51.552  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:42:51.557   928  3419 D WifiService: setWifiEnabled: false pid=5442, uid=10077
,09-23 09:42:51.557   928  3419 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:42:51.563   928  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-23 09:42:51.563   928  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-23 09:42:51.564   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 09:42:51.564   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:42:51.569  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:42:51.572  4468  4538 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 09:42:51.572  4468  4538 D BluetoothAdapterProperties: Setting state to 13
,09-23 09:42:51.572  4468  4538 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 09:42:51.573  4468  4538 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 09:42:51.576  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:51.577  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:51.579  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:42:51.579  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:51.579  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:42:51.580  4468  4468 D BluetoothMapService: onReceive
09-23 09:42:51.580  4468  4468 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:42:51.580  4468  4468 D BluetoothMapService: STATE_TURNING_OFF
09-23 09:42:51.581  4468  4468 D BluetoothMapService: MAP Service closeService in
09-23 09:42:51.581  4468  4468 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 09:42:51.581  4468  4468 D ObexServerSockets0: shutdown(block = true)
09-23 09:42:51.582  4468  4468 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 09:42:51.582   928  5193 D DhcpClient: Clearing IP address
09-23 09:42:51.582  4468  4468 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 09:42:51.582   507   925 D CommandListener: Clearing all IP addresses on wlan0
,09-23 09:42:51.583  4468  4726 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 09:42:51.583  4468  4679 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 09:42:51.583  4468  4725 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-23 09:42:51.582  4468  4538 I BluetoothAdapterState: Entering PendingCommandState
09-23 09:42:51.587  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:51.587  4468  4468 I BtOppRfcommListener: stopping Accept Thread
09-23 09:42:51.588  4468  5133 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 09:42:51.589  4468  5133 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 09:42:51.590   507   925 D CommandListener: Setting iface cfg
,09-23 09:42:51.591  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.593  3606  5250 V NativeCrypto: Read error: ssl=0x7f807f0000: I/O error during system call, Connection timed out
09-23 09:42:51.593   928  5194 D DhcpClient: Receive thread stopped
,09-23 09:42:51.595  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:51.595  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:51.595  3606  5250 V NativeCrypto: SSL shutdown failed: ssl=0x7f807f0000: I/O error during system call, Broken pipe
09-23 09:42:51.596  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.596  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:51.598   928  3197 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-23 09:42:51.598   928  5191 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-23 09:42:51.600  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:51.600  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:42:51.601   928  5191 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-23 09:42:51.601   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-23 09:42:51.601  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.601   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-23 09:42:51.601  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:42:51.606  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.606   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 09:42:51.615   928   941 I ActivityManager: Start proc 5495:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-23 09:42:51.616  4468  4542 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:42:51.617  4468  4538 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-23 09:42:51.619  4468  4468 D HeadsetService: Received stop request...Stopping profile...
,09-23 09:42:51.623   928   928 D RttService: SCAN_AVAILABLE : 1
09-23 09:42:51.623   533   533 E Parcel  : Reading a NULL string not supported here.
09-23 09:42:51.624  3546  3570 D BluetoothHeadset: Proxy object disconnected
09-23 09:42:51.624   928  3080 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 09:42:51.624  3143  3157 D BluetoothHeadset: Proxy object disconnected
09-23 09:42:51.625   928   928 D BluetoothHeadset: Proxy object disconnected
,09-23 09:42:51.625   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 09:42:51.625   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 09:42:51.625  4468  4468 D A2dpService: Received stop request...Stopping profile...
09-23 09:42:51.626   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-23 09:42:51.626   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-23 09:42:51.628  4468  4706 D A2dpStateMachine: Exit Disconnected: -1
09-23 09:42:51.629  4468  4468 V BluetoothAdapterState: isTurningOff()=true
,09-23 09:42:51.629  4468  4468 V BluetoothAdapterState: isTurningOn()=false
,09-23 09:42:51.629  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.629  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:42:51.630   928   928 D BluetoothA2dp: Proxy object disconnected
09-23 09:42:51.630  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:42:51.630  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:42:51.631  4468  4468 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-23 09:42:51.631  4468  4468 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 09:42:51.631  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:42:51.631  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:51.631  4468  4673 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:42:51.631  4468  4673 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:42:51.631  4468  4673 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:42:51.631   928  2977 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 09:42:51.633  3498  3700 W QCNEJ   : |CORE| network lost: 100
09-23 09:42:51.633  4468  4542 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 09:42:51.633  4468  4542 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 09:42:51.633  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.633  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:42:51.634  3498  3700 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-23 09:42:51.634  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.634  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:51.636  4468  4468 D HidService: Received stop request...Stopping profile...
09-23 09:42:51.636  4468  4468 D HidService: Stopping Bluetooth HidService
09-23 09:42:51.639  4468  4468 V BluetoothAdapterState: isTurningOff()=true
09-23 09:42:51.639  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.639  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.639  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:42:51.640  3143  3143 D HeadsetProfile: Bluetooth service disconnected
09-23 09:42:51.640  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.640  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:42:51.640  3143  3143 D BluetoothA2dp: Proxy object disconnected
09-23 09:42:51.641  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.641  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:51.641  4468  4468 D HealthService: Received stop request...Stopping profile...
09-23 09:42:51.645  3143  3143 D BluetoothInputDevice: Proxy object disconnected
09-23 09:42:51.645  3143  3143 D HidProfile: Bluetooth service disconnected
09-23 09:42:51.645  4468  4673 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:42:51.645  4468  4673 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 09:42:51.646  4468  4542 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 09:42:51.646  4468  4468 D PanService: Received stop request...Stopping profile...
,09-23 09:42:51.646  4468  4673 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:42:51.646  4468  4673 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:42:51.646  4468  4673 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:42:51.646  4468  4673 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:42:51.646   928  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-23 09:42:51.647   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:42:51.647  4468  4468 D BluetoothMapService: Received stop request...Stopping profile...
09-23 09:42:51.647  4468  4468 D BluetoothMapService: stop()
,09-23 09:42:51.647  4468  4468 D BluetoothMapAppObserver: deinitObservers()
09-23 09:42:51.647  4468  4468 D BluetoothMapAppObserver: removeReceiver()
09-23 09:42:51.649  4468  4468 D SapService: Received stop request...Stopping profile...
09-23 09:42:51.649  4468  4468 V SapService: stop()
09-23 09:42:51.650  4468  4468 V BluetoothAdapterState: isTurningOff()=true
09-23 09:42:51.650  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.650  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.650  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:42:51.650  4468  4468 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-23 09:42:51.650  3143  3143 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-23 09:42:51.651  3143  3143 D PanProfile: Bluetooth service disconnected
09-23 09:42:51.651  4468  4542 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 09:42:51.651  3143  3143 D BluetoothMap: Proxy object disconnected
09-23 09:42:51.651  3143  3143 D MapProfile: Bluetooth service disconnected
,09-23 09:42:51.651  4468  4468 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 09:42:51.651  4468  4468 V BluetoothAdapterState: isTurningOff()=true
09-23 09:42:51.651  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.651  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.651  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:42:51.651  4468  4468 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 09:42:51.651  4468  4542 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 09:42:51.652  4468  4468 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 09:42:51.652  4468  4468 V BluetoothAdapterState: isTurningOff()=true
09-23 09:42:51.652  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.652  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.652  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:42:51.652  4468  4468 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 09:42:51.652  4468  4468 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 09:42:51.653  4468  4468 D BluetoothMapService: MAP Service closeService in
09-23 09:42:51.653  4468  4468 V BluetoothAdapterState: isTurningOff()=true
,09-23 09:42:51.653  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.653  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.653  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:42:51.654  4468  4468 D BluetoothMapService: cleanup()
09-23 09:42:51.654  4468  4468 D BluetoothMapService: MAP Service closeService in
09-23 09:42:51.654  4468  4468 V BluetoothAdapterState: isTurningOff()=true
09-23 09:42:51.654  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.654  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.654  4468  4468 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:42:51.654  4468  4538 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 09:42:51.654  4468  4538 D BluetoothAdapterProperties: Setting state to 15
09-23 09:42:51.654  4468  4538 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 09:42:51.655  4468  4538 I BluetoothAdapterState: Entering BleOnState
09-23 09:42:51.655  3143  3157 D BluetoothMap: onBluetoothStateChange: up=false
09-23 09:42:51.656  3546  3804 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:42:51.656  3143  3778 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:42:51.657   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:42:51.657  3143  3156 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:42:51.657  3143  3780 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 09:42:51.658   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:42:51.658  3143  3157 D BluetoothPan: onBluetoothStateChange on: false
09-23 09:42:51.659  3143  3778 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 09:42:51.660   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:42:51.660   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:42:51.660  4468  4538 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 09:42:51.660  4468  4538 D BluetoothAdapterProperties: Setting state to 16
09-23 09:42:51.660  4468  4538 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 09:42:51.661  4468  4538 D BluetoothAdapterProperties: onBleDisable
09-23 09:42:51.662   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-23 09:42:51.663  4468  4538 I BluetoothAdapterState: Entering PendingCommandState
09-23 09:42:51.663  4468  4539 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 09:42:51.664  4468  4542 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:42:51.664  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.664  4468  4673 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 09:42:51.664  4468  4673 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.664  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:51.666  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.667  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:51.668  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.669  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.669  5495  5495 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-23 09:42:51.670  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.671  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:51.681   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-23 09:42:51.681   507   925 D CommandListener: Clearing all IP addresses on wlan0
09-23 09:42:51.682   507   925 D TetherController: Setting IP forward enable = 0
09-23 09:42:51.684   928  2977 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-23 09:42:51.684   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:42:51.688   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-23 09:42:51.690  4243  4243 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ed33e5b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-23 09:42:51.691   928  2975 D DhcpClient: doQuit
09-23 09:42:51.691   928  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 09:42:51.692   928  5193 D DhcpClient: onQuitting
09-23 09:42:51.692  3630  3630 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 09:42:51.693  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:51.695  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:51.697  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.697  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:51.700  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.700  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:51.700  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.700  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:51.703  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:51.703  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:51.704  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Blu,etooth is disabled - will return stored value
09-23 09:42:51.704  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:51.706  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.708  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.708  4907  4920 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:42:51.708  4907  4920 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:42:51.708  4907  4920 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 09:42:51.708  4907  4920 E SarControlService: no key has been found,reset the power
09-23 09:42:51.708  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:42:51.709  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:42:51.709  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 09:42:51.709  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:42:51.709  4933  4933 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-23 09:42:51.711  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-23 09:42:51.712  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:42:51.712  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:42:51.712  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:42:51.712  4933  4933 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:42:51.715  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000ea03000000000000ffffffff]
09-23 09:42:51.715  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:42:51.715  4933  4947 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-23 09:42:51.715  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:42:51.715  4907  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:42:51.717  5495  5495 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 09:42:51.723   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0fb4ad:true
09-23 09:42:51.723  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:42:51.724  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000eb03000000000000ffffffff]
,09-23 09:42:51.724  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:42:51.724  4933  4947 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-23 09:42:51.725  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:42:51.725  4907  4918 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 09:42:51.727  3630  3630 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-23 09:42:51.731  3630  3630 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-23 09:42:51.739   928  3583 I ActivityManager: Start proc 5525:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 09:42:51.753  5495  5495 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 09:42:51.757   507   925 E Netd    : netlink response contains error (No such file or directory)
,09-23 09:42:51.758   507   925 D TetherController: Setting IP forward enable = 0
09-23 09:42:51.758   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 09:42:51.759  5495  5495 D BluetoothMap: Create BluetoothMap proxy object
,09-23 09:42:51.774  3630  3630 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 09:42:51.774  5495  5495 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 09:42:51.783  5525  5525 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 09:42:51.786  3630  3630 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 09:42:51.793  5495  5495 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:42:51.795   928  3155 I ActivityManager: Killing 4871:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 09:42:51.870  4468  4542 I bt_hci  : shut_down
,09-23 09:42:51.874  4468  4549 D bt_hwcfg: hw_epilog_process
,09-23 09:42:51.874  4468  4549 I bt_vendor: low_power_mode_cb
,09-23 09:42:51.877  4468  4549 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 09:42:51.877  4468  4549 I bt_vendor: epilog_cb
09-23 09:42:51.877  4468  4549 I bt_hci  : epilog_finished_callback
,09-23 09:42:51.879  4468  4542 I bt_hci_h4: hal_close
09-23 09:42:51.880  4468  4542 I bt_userial_vendor: device fd = 54 close
,09-23 09:42:51.891  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 09:42:51.891   928  2975 D wifi    : In wifi stop Hal
09-23 09:42:51.891   928  2975 D wifi    : halHandle = 0x7f6a9c9a00, mVM = 0x7f86acd140, mCls = 0x100b16
,09-23 09:42:51.892   928  3628 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 09:42:51.892   928  3628 D WifiHAL : Got a signal to exit!!!
09-23 09:42:51.892   928  3628 I WifiHAL : Exit wifi_event_loop
09-23 09:42:51.892   928  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-23 09:42:51.892   928  2975 E WifiHAL : Event processing terminated
,09-23 09:42:51.893   928  2975 D wifi    : In wifi cleaned up handler
09-23 09:42:51.893   928  2975 I WifiHAL : Internal cleanup completed
09-23 09:42:51.895  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:51.897  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:51.898  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:42:51.898  3477  4027 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 09:42:51.914   928  3628 D wifi    : set interface wlan0 flags (DOWN)
,09-23 09:42:51.915   928  2975 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.974  5525  5525 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:42:51.974  5525  5525 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:42:51.982  5495  5495 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:42:51.984  4468  4539 D bt_stack_manager: event_shut_down_stack finished.
09-23 09:42:51.984  4468  4538 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 09:42:51.987  4468  4538 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 09:42:51.987  4468  4468 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 09:42:51.988  4468  4468 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 09:42:51.988  4468  4468 D BtGatt.GattService: stop()
09-23 09:42:51.988  4468  4468 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 09:42:51.988  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:42:51.990  5495  5495 D DockEventReceiver: finishStartingService: stopping service
09-23 09:42:51.991  4468  4468 V BluetoothAdapterState: isTurningOff()=false
09-23 09:42:51.991  4468  4468 V BluetoothAdapterState: isTurningOn()=false
09-23 09:42:51.991  4468  4468 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:42:51.991  4468  4468 V BluetoothAdapterState: isBleTurningOff()=true
09-23 09:42:51.991  4468  4538 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 09:42:51.991  4468  4538 D BluetoothAdapterProperties: Setting state to 10
09-23 09:42:51.991  4468  4538 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 09:42:51.992   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-23 09:42:51.993  4468  4538 I BluetoothAdapterState: Entering OffState
09-23 09:42:51.995   928  3419 I ActivityManager: Killing 4243:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-23 09:42:52.099  4468  4468 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-23 09:42:52.099  4468  4468 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 09:42:52.101  4468  4468 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 09:42:52.101  4468  4539 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-23 09:42:52.102  3899  3899 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-23 09:42:52.110  3899  3899 D SystemUpdateService: onCreate
09-23 09:42:52.116  4468  4539 D bt_stack_manager: event_clean_up_stack finished.
09-23 09:42:52.116  3899  3899 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 09:42:52.117   928   945 D Tethering: InitialState.processMessage what=4
09-23 09:42:52.119   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 09:42:52.121  4468  4468 I art     : System.exit called, status: 0
09-23 09:42:52.121  4468  4468 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 09:42:52.127  3899  3899 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 09:42:52.140  3899  5221 I iu.UploadsManager: num queued entries: 0
,09-23 09:42:52.141  3899  5221 I iu.UploadsManager: num updated entries: 0
09-23 09:42:52.141  3899  5221 I iu.SyncManager: NEXT; no task
,09-23 09:42:52.143  3899  5560 I SystemUpdateService: active receiver: enabled
,09-23 09:42:52.147  3899  3899 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 09:42:52.148  3899  3899 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:42:52.150  5224  5224 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:42:52.154  5224  5224 D SprintDMHelper: simOperator: 
,09-23 09:42:52.154  5224  5224 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:42:52.177  4300  5562 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 09:42:52.179   928  3197 I ActivityManager: Start proc 5563:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 09:42:52.179  3899  5560 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-23 09:42:52.180   928  3423 I ActivityManager: Process com.android.bluetooth (pid 4468) has died
,09-23 09:42:52.182  3899  5560 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-23 09:42:52.182  3899  5560 I SystemUpdateService: now status is 0 (complete)
,09-23 09:42:52.182  3899  5560 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-23 09:42:52.183  3899  5560 I SystemUpdateService: file has been verified
09-23 09:42:52.183  3899  5560 I SystemUpdateService: OTA package size = 21989297
,09-23 09:42:52.200  3899  5560 I SystemUpdateService: showing system update notification
,09-23 09:42:52.210  5563  5563 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 09:42:52.247  3899  3899 D SystemUpdateService: onDestroy
,09-23 09:42:52.249   928   939 I ActivityManager: Killing 4565:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 09:42:52.328  5525  5555 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 09:42:52.337   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ea0e9b6:true
,09-23 09:42:56.588   928   938 D WifiService: setWifiEnabled: true pid=5442, uid=10077
09-23 09:42:56.589   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:42:56.595   507   925 D SoftapController: Softap fwReload - Ok
,09-23 09:42:56.600   507   925 D CommandListener: Setting iface cfg
,09-23 09:42:56.601   507   925 D CommandListener: Trying to bring down wlan0
09-23 09:42:56.602   507   925 D CommandListener: Clearing all IP addresses on wlan0
,09-23 09:42:56.607   928  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 09:42:57.191   928  2975 D wifi    : set interface wlan0 flags (UP)
,09-23 09:42:57.194   928  2975 I WifiHAL : Initializing wifi
09-23 09:42:57.194   928  2975 I WifiHAL : Creating socket
09-23 09:42:57.200   928  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-23 09:42:57.201   928  2975 D wifi    : Did set static halHandle = 0x7f6a9c9a00
09-23 09:42:57.201   928  2975 D wifi    : halHandle = 0x7f6a9c9a00, mVM = 0x7f86acd140, mCls = 0x18ee
,09-23 09:42:57.201   928  2975 D wifi    : array field set
,09-23 09:42:57.201   928  2975 I WifiNative-HAL: interface[0] = wlan0
09-23 09:42:57.202   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-23 09:42:57.206   928  5580 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547249494528
09-23 09:42:57.206   928  5580 D wifi    : waitForHalEvents called, vm = 0x7f86acd140, obj = 0x18ee, env = 0x7f68107880
,09-23 09:42:57.285  5581  5581 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 09:42:57.305  5581  5581 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:42:57.307   928  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 09:42:57.309  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:57.310  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:57.312  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:42:57.333  5581  5581 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:42:57.333  5581  5581 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 09:42:57.348   928  2975 D WifiConfigStore: Loading config and enabling all networks 
,09-23 09:42:57.349  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:57.349  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:57.349  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:57.349  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:57.350  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:57.350  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:42:57.350  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:57.350  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:42:57.351  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:42:57.351  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:42:57.352  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:42:57.352  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:42:57.358   928  2975 D WifiConfigStore: loaded 0 passpoint configs
,09-23 09:42:57.359   928  2975 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 09:42:57.359   928  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-23 09:42:57.360   928  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-23 09:42:57.362   928  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 09:42:57.362   928  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 09:42:57.362   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 09:42:57.362   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 09:42:57.366   928  2975 D WifiNative-HAL: Setting external_sim to 1
,09-23 09:42:57.366  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 09:42:57.366   928  2975 D wifi    : setting dfs flag to true, 0x7f6c998c80
,09-23 09:42:57.367   928  2975 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 09:42:57.367   928  2975 D wifi    : setting scan oui 0x7f6c998c80
09-23 09:42:57.367   928  2975 D WifiHAL : Sending mac address OUI
,09-23 09:42:57.371   928  2975 E native  : do suspend false
,09-23 09:42:57.378   928  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-23 09:42:57.378   928   928 D RttService: SCAN_AVAILABLE : 3
09-23 09:42:57.378   507   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 09:42:57.378   928  3080 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 09:42:57.379   507   925 D CommandListener: Setting iface cfg
,09-23 09:42:57.382   928  2948 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-23 09:42:57.383   928  2948 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 09:42:57.391   928  2948 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 09:42:57.396   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267610 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-23 09:42:57.396   928  2948 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 09:43:00.570  5581  5581 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:00.576  5581  5581 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:00.582  5581  5581 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:00.587  5581  5581 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:00.634   928  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 09:43:00.635   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 09:43:00.635   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:43:00.646   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 09:43:00.679   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 09:43:00.681  5581  5581 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 09:43:01.100  5581  5581 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 09:43:01.136  5581  5581 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 09:43:01.137  5581  5581 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 09:43:01.148   928  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:43:01.148   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 09:43:01.148   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 09:43:01.165   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:43:01.178   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:01.184   928  2975 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 09:43:01.191   928  5589 D DhcpClient: Receive thread started
,09-23 09:43:01.196   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 09:43:01.196   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 09:43:01.196   928  2977 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 09:43:01.277   928  2975 E native  : do suspend false
,09-23 09:43:01.292   928  5588 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 09:43:01.304   928  5589 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
,09-23 09:43:01.305   928  5588 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
,09-23 09:43:01.307   928  5588 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 09:43:01.319   928  5589 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 09:43:01.320   928  5588 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 09:43:01.323   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:01.327   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 09:43:01.331   928  5588 D DhcpClient: Scheduling renewal in 86399s
,09-23 09:43:01.340   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 09:43:01.340   928  2975 D WifiConfigStore: No blacklist allowed without epno enabled
09-23 09:43:01.341   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-23 09:43:01.343   928  2977 D ConnectivityService: Adding iface wlan0 to network 101
,09-23 09:43:01.343   928  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 09:43:01.386   928  2977 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 09:43:01.386   928  2977 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 09:43:01.389   928  2977 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 09:43:01.392   928  2977 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-23 09:43:01.395   928  2977 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 09:43:01.405   928  2977 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 09:43:01.410   928  2977 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-23 09:43:01.410   928  2977 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-23 09:43:01.410   928  2977 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-23 09:43:01.410   928  2977 D ConnectivityService:    accepting network in place of null
09-23 09:43:01.410   928  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 09:43:01.410   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:43:01.411   928  2977 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:43:01.431   928  5587 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271645, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 09:43:01.435   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:43:01.458   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:43:01.462   928  2977 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-23 09:43:01.462   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 09:43:01.462  3498  3700 W QCNEJ   : |CORE| network available: 101
,09-23 09:43:01.463   928  2977 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-23 09:43:01.465   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-23 09:43:01.468  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:43:01.468  3498  3700 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:01.468  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:43:01.469  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.469  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:01.469  3498  3700 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-23 09:43:01.470  3498  3700 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-23 09:43:01.473  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:01.473  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:43:01.473  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:43:01.473  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:01.475  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:01.475  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:43:01.475  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.475  4907  4920 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:43:01.475  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:01.476  4907  4920 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:43:01.476  4907  4920 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-23 09:43:01.476  4907  4920 E SarControlService: no key has been found,reset the power
09-23 09:43:01.478  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:43:01.478  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:43:01.478  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 09:43:01.479  3899  3899 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 09:43:01.480  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-23 09:43:01.480  4933  4933 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 09:43:01.482  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 09:43:01.482  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:43:01.482  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:43:01.482  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:43:01.482  4933  4933 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-23 09:43:01.487  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000ec03000000000000ffffffff]
09-23 09:43:01.487  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:43:01.487  4933  4947 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 09:43:01.487  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:43:01.488  4907  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:43:01.488  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000ed03000000000000ffffffff]
09-23 09:43:01.488  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:43:01.488  4933  4947 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 09:43:01.489  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:43:01.489  4907  4918 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 09:43:01.486  3899  3899 D SystemUpdateService: onCreate
09-23 09:43:01.492  3899  3899 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 09:43:01.498   928  5586 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-23 09:43:01.502  3899  3899 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 09:43:01.507  3899  5221 I iu.UploadsManager: num queued entries: 0
,09-23 09:43:01.507  3899  5221 I iu.UploadsManager: num updated entries: 0
09-23 09:43:01.508  3899  5221 I iu.SyncManager: NEXT; no task
,09-23 09:43:01.511  3899  5600 I SystemUpdateService: active receiver: enabled
,09-23 09:43:01.513  3899  3899 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 09:43:01.514  3899  3899 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:43:01.516  5224  5224 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-23 09:43:01.519  5224  5224 D SprintDMHelper: simOperator: 
09-23 09:43:01.519  5224  5224 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:43:01.545  3899  5600 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:43:01.547   928  5586 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 13:43:01 GMT], X-Android-Received-Millis=[1474638181546], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474638181523]}
,09-23 09:43:01.547   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 09:43:01.548   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-23 09:43:01.548   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-23 09:43:01.549   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 09:43:01.553  3899  5600 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 09:43:01.554  3899  5600 I SystemUpdateService: now status is 0 (complete)
09-23 09:43:01.554  3899  5600 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 09:43:01.554  3899  5600 I SystemUpdateService: file has been verified
09-23 09:43:01.554  3899  5600 I SystemUpdateService: OTA package size = 21989297
,09-23 09:43:01.561  3899  5600 I SystemUpdateService: showing system update notification
,09-23 09:43:01.570  3899  3899 D SystemUpdateService: onDestroy
,09-23 09:43:01.593   928  3559 D WifiService: setWifiEnabled: false pid=5442, uid=10077
,09-23 09:43:01.593   928  3559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 09:43:01.594   928  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-23 09:43:01.594   928  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-23 09:43:01.595   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:43:01.595   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:43:01.603   928  5588 D DhcpClient: Clearing IP address
,09-23 09:43:01.603   507   925 D CommandListener: Clearing all IP addresses on wlan0
,09-23 09:43:01.604   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:01.607  3606  5601 V NativeCrypto: SSL handshake aborted: ssl=0x7f807f0000: I/O error during system call, Connection timed out
,09-23 09:43:01.613  4300  5605 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-23 09:43:01.614   928  3197 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-23 09:43:01.614   928  5586 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-23 09:43:01.615   928  5586 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-23 09:43:01.616   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-23 09:43:01.616   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-23 09:43:01.618   533   533 E Parcel  : Reading a NULL string not supported here.
09-23 09:43:01.620   928  2977 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-23 09:43:01.620   928  5586 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-23 09:43:01.623  3498  3700 W QCNEJ   : |CORE| network lost: 101
,09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
09-23 09:43:01.624  4300  5605 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-23 09:43:01.624  4300  5605 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-23 09:43:01.624  3498  3700 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-23 09:43:01.625   928   928 D RttService: SCAN_AVAILABLE : 1
09-23 09:43:01.625   928  3080 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 09:43:01.627   928  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 09:43:01.630   928  5589 D DhcpClient: Receive thread stopped
09-23 09:43:01.630   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 09:43:01.646   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:43:01.666   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:43:01.666   507   925 D CommandListener: Clearing all IP addresses on wlan0
09-23 09:43:01.666   928  2977 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-23 09:43:01.667   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:43:01.668   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-23 09:43:01.669   928  2975 D DhcpClient: doQuit
,09-23 09:43:01.669   928  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 09:43:01.670   928  5588 D DhcpClient: onQuitting
09-23 09:43:01.670  5581  5581 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 09:43:01.671  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:01.671  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:01.671  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.671  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:01.673  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:01.673  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:43:01.673  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.673  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:01.675  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:01.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:01.675  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:01.675  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:01.676  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:01.677  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:01.678  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:01.680  3899  3899 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 09:43:01.682  4907  4920 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:43:01.682  4907  4920 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:43:01.682  4907  4920 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 09:43:01.682  4907  4920 E SarControlService: no key has been found,reset the power
09-23 09:43:01.682  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:43:01.682  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:43:01.683  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 09:43:01.683  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-23 09:43:01.683  4933  4933 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 09:43:01.684  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 09:43:01.684  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:43:01.684  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:43:01.685  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:43:01.685  4933  4933 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:43:01.687  5581  5581 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 09:43:01.688  3899  3899 D SystemUpdateService: onCreate
09-23 09:43:01.689  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000ee03000000000000ffffffff]
09-23 09:43:01.689  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:43:01.690  4933  4947 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-23 09:43:01.690  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:43:01.690  5581  5581 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-23 09:43:01.690  4907  4918 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:43:01.691  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000ef03000000000000ffffffff]
09-23 09:43:01.692  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:43:01.692  4933  4947 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,09-23 09:43:01.692  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:43:01.693  4907  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 09:43:01.695  3899  3899 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 09:43:01.702  3899  5618 I SystemUpdateService: active receiver: enabled
,09-23 09:43:01.704  3899  3899 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 09:43:01.709  3899  5221 I iu.UploadsManager: num queued entries: 0
,09-23 09:43:01.711  3899  3899 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 09:43:01.712  3899  3899 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:43:01.714  5224  5224 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-23 09:43:01.717  5224  5224 D SprintDMHelper: simOperator: 
,09-23 09:43:01.718  5224  5224 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-23 09:43:01.719  5581  5581 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 09:43:01.723   507   925 E Netd    : netlink response contains error (No such file or directory)
,09-23 09:43:01.724   928  2977 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-23 09:43:01.725   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 09:43:01.725  3899  5221 I iu.UploadsManager: num updated entries: 0
,09-23 09:43:01.720  3899  5618 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:43:01.730  4300  5622 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 09:43:01.733  5581  5581 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 09:43:01.734  3899  5221 I iu.SyncManager: NEXT; no task
,09-23 09:43:01.736  3899  5618 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-23 09:43:01.736  3899  5618 I SystemUpdateService: now status is 0 (complete)
09-23 09:43:01.737  3899  5618 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 09:43:01.737  3899  5618 I SystemUpdateService: file has been verified
09-23 09:43:01.737  3899  5618 I SystemUpdateService: OTA package size = 21989297
,09-23 09:43:01.748  3899  5618 I SystemUpdateService: showing system update notification
,09-23 09:43:01.758  3899  3899 D SystemUpdateService: onDestroy
,09-23 09:43:01.835   928  2975 D wifi    : In wifi stop Hal
,09-23 09:43:01.835   928  2975 D wifi    : halHandle = 0x7f6a9c9a00, mVM = 0x7f86acd140, mCls = 0x18ee
09-23 09:43:01.838   928  5580 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 09:43:01.838   928  5580 D WifiHAL : Got a signal to exit!!!
09-23 09:43:01.838   928  5580 I WifiHAL : Exit wifi_event_loop
09-23 09:43:01.838   928  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 09:43:01.838   928  2975 E WifiHAL : Event processing terminated
09-23 09:43:01.839   928  2975 D wifi    : In wifi cleaned up handler
09-23 09:43:01.839   928  2975 I WifiHAL : Internal cleanup completed
09-23 09:43:01.839  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 09:43:01.843  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:01.844  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:01.844  3477  4027 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 09:43:01.845  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:01.864   928  5580 D wifi    : set interface wlan0 flags (DOWN)
,09-23 09:43:01.864   928  2975 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 09:43:02.069   928   945 D Tethering: InitialState.processMessage what=4
09-23 09:43:02.075   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 09:43:02.463   928  2977 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 09:43:04.104   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:05.105   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:06.106   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:06.630   928   945 I ActivityManager: Start proc 5624:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 09:43:06.732  5624  5624 D AdapterServiceConfig: Adding HeadsetService
,09-23 09:43:06.732  5624  5624 D AdapterServiceConfig: Adding A2dpService
09-23 09:43:06.733  5624  5624 D AdapterServiceConfig: Adding HidService
09-23 09:43:06.733  5624  5624 D AdapterServiceConfig: Adding HealthService
,09-23 09:43:06.733  5624  5624 D AdapterServiceConfig: Adding PanService
09-23 09:43:06.733  5624  5624 D AdapterServiceConfig: Adding GattService
09-23 09:43:06.733  5624  5624 D AdapterServiceConfig: Adding BluetoothMapService
09-23 09:43:06.734  5624  5624 D AdapterServiceConfig: Adding SapService
,09-23 09:43:06.745   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2a5b05:true
,09-23 09:43:06.745  5624  5624 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 09:43:06.748  5624  5624 I bt_bluedroid: init
,09-23 09:43:06.748  5624  5636 I BluetoothAdapterState: Entering OffState
,09-23 09:43:06.750  5624  5637 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-23 09:43:06.750  5624  5637 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 09:43:06.750  5624  5637 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 09:43:06.750  5624  5637 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-23 09:43:06.751  5624  5624 I bt_bluedroid: get_profile_interface socket
,09-23 09:43:06.752  5624  5640 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 09:43:06.753  5624  5624 I bt_bluedroid: get_profile_interface sdp
,09-23 09:43:06.754  5624  5640 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 09:43:06.757  5624  5635 I bt_bluedroid: config_hci_snoop_log
09-23 09:43:06.758   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 09:43:06.762  5624  5636 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 09:43:06.762  5624  5636 D BluetoothAdapterProperties: Setting state to 14
,09-23 09:43:06.762  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 09:43:06.765  5624  5636 D BluetoothBondStateMachine: make
,09-23 09:43:06.766  5624  5641 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 09:43:06.769  5624  5636 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:43:06.770  5624  5624 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 09:43:06.772  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:06.772  5624  5624 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 09:43:06.773  5624  5624 D BtGatt.GattService: Received start request. Starting profile...
09-23 09:43:06.773  5624  5624 D BtGatt.GattService: start()
,09-23 09:43:06.773  5624  5624 I bt_bluedroid: get_profile_interface gatt
,09-23 09:43:06.774  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
,09-23 09:43:06.774  5624  5624 D BtGatt.AdvertiseManager: advertise manager created
,09-23 09:43:06.779  5624  5624 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:06.779  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:06.779  5624  5624 V BluetoothAdapterState: isBleTurningOn()=true
09-23 09:43:06.779  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:06.780  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 09:43:06.781  5624  5636 I bt_bluedroid: bt_bluedroid
,09-23 09:43:06.781  5624  5637 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 09:43:06.781  5624  5637 I bt_hci  : start_up
,09-23 09:43:06.786  5624  5637 I bt_vendor: alloc value 0xf424d871
,09-23 09:43:06.786  5624  5637 I bt_vendor: init
09-23 09:43:06.786  5624  5637 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 09:43:06.787  5624  5637 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 09:43:06.895  5624  5637 D bt_hci  : start_up starting async portion
,09-23 09:43:06.896  5624  5644 I bt_hci  : event_finish_startup
09-23 09:43:06.896  5624  5644 I bt_hci_h4: hal_open
09-23 09:43:06.896  5624  5644 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 09:43:06.894  5645  5645 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 09:43:06.898  5624  5644 I bt_userial_vendor: device fd = 54 open
,09-23 09:43:06.912  5624  5644 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 09:43:06.914  5624  5644 D bt_hwcfg: Chipset BCM4358A3
,09-23 09:43:06.914  5624  5644 D bt_hwcfg: Target name = [BCM4358A3]
,09-23 09:43:06.915  5624  5644 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 09:43:07.107   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:07.317  5624  5644 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 09:43:07.317  5624  5644 D bt_hwcfg: Settlement delay -- 100 ms
09-23 09:43:07.317  5624  5644 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 09:43:07.452  5624  5644 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 09:43:07.452  5624  5644 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 09:43:07.453  5624  5644 I bt_hwcfg: vendor lib fwcfg completed
09-23 09:43:07.453  5624  5644 I bt_vendor: firmware callback
09-23 09:43:07.454  5624  5644 I bt_hci  : firmware_config_callback
,09-23 09:43:07.462  5624  5647 I bt_btu  : btu_task pending for preload complete event
,09-23 09:43:07.463  5624  5647 I bt_btu_task: Bluetooth chip preload is complete
09-23 09:43:07.463  5624  5647 I bt_btu  : btu_task received preload complete event
,09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_HCI
09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 09:43:07.470  5624  5647 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_PAN
,09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_SDP
09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 09:43:07.471  5624  5647 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-23 09:43:07.472  5624  5647 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 09:43:07.555  5624  5647 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41cb549
09-23 09:43:07.555  5624  5647 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41cb549 
,09-23 09:43:07.577  5624  5640 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 09:43:07.578  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 09:43:07.579  5624  5640 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 09:43:07.582  5624  5640 D BluetoothAdapterProperties: Name is: Nexus 6P
09-23 09:43:07.584  5624  5640 D BluetoothAdapterProperties: Scan Mode:20
,09-23 09:43:07.584  5624  5640 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 09:43:07.584  5624  5640 D bt_hci  : do_postload posting postload work item
,09-23 09:43:07.584  5624  5644 I bt_hci  : event_postload
,09-23 09:43:07.584  5624  5644 I bt_vendor: sco_config_cb
09-23 09:43:07.585  5624  5644 I bt_hci  : sco_config_callback postload finished.
09-23 09:43:07.588  5624  5640 D bt_bte_conf: Device ID record 1 : primary
09-23 09:43:07.588  5624  5640 D bt_bte_conf:   vendorId            = 000f
09-23 09:43:07.588  5624  5640 D bt_bte_conf:   vendorIdSource      = 0001
09-23 09:43:07.588  5624  5640 D bt_bte_conf:   product             = 1200
09-23 09:43:07.588  5624  5640 D bt_bte_conf:   version             = 1436
09-23 09:43:07.588  5624  5640 D bt_bte_conf:   clientExecutableURL = 
09-23 09:43:07.588  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:07.588  5624  5640 D bt_bte_conf:   serviceDescription  = 
09-23 09:43:07.588  5624  5640 D bt_bte_conf:   documentationURL    = 
09-23 09:43:07.588  5624  5640 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 09:43:07.589  5624  5637 D bt_stack_manager: event_start_up_stack finished
09-23 09:43:07.590  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 09:43:07.591  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:07.591  5624  5636 D BluetoothAdapterProperties: Setting state to 15
09-23 09:43:07.591  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 09:43:07.592  5624  5636 I BluetoothAdapterState: Entering BleOnState
09-23 09:43:07.594  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:07.597  5624  5644 I bt_vendor: low_power_mode_cb
,09-23 09:43:07.598  5624  5636 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 09:43:07.598  5624  5636 D BluetoothAdapterProperties: Setting state to 11
09-23 09:43:07.598  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 09:43:07.602  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
,09-23 09:43:07.603  5624  5624 D HeadsetService: Received start request. Starting profile...
09-23 09:43:07.605  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:07.606  5624  5624 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 09:43:07.606  5624  5624 D HeadsetStateMachine: make
09-23 09:43:07.607  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:07.609  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:07.614  5624  5636 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:43:07.617  5624  5624 D HeadsetStateMachine: max_hf_connections = 1
,09-23 09:43:07.618  5624  5624 I bt_bluedroid: get_profile_interface handsfree
09-23 09:43:07.618  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 09:43:07.618  5624  5640 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-23 09:43:07.621  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
,09-23 09:43:07.621  5624  5624 D A2dpService: Received start request. Starting profile...
,09-23 09:43:07.622  5624  5624 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 09:43:07.622  5624  5624 I bt_bluedroid: get_profile_interface avrcp
,09-23 09:43:07.629  5624  5624 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 09:43:07.629  5624  5624 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 09:43:07.629  5624  5624 D A2dpStateMachine: make
,09-23 09:43:07.630  5624  5624 I bt_bluedroid: get_profile_interface a2dp
,09-23 09:43:07.631  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 09:43:07.632  5624  5655 D A2dpStateMachine: Enter Disconnected: -2
,09-23 09:43:07.632  5624  5624 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 09:43:07.633  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
,09-23 09:43:07.635  5495  5495 D BluetoothInputDevice: Proxy object connected
,09-23 09:43:07.635  5495  5495 D HidProfile: Bluetooth service connected
09-23 09:43:07.636  5624  5624 D HidService: Received start request. Starting profile...
,09-23 09:43:07.636  5624  5624 I bt_bluedroid: get_profile_interface hidhost
,09-23 09:43:07.636  5624  5624 D HidService: setHidService(): set to: null
09-23 09:43:07.636  5624  5640 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41ac56d
09-23 09:43:07.636  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 09:43:07.637  5624  5624 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 09:43:07.637  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:07.638  5624  5624 D HealthService: Received start request. Starting profile...
09-23 09:43:07.639  5624  5624 I bt_bluedroid: get_profile_interface health
,09-23 09:43:07.640  5624  5624 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-23 09:43:07.641  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:07.641  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:43:07.642  5624  5624 D PanService: Received start request. Starting profile...
09-23 09:43:07.642  5624  5624 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 09:43:07.643  5624  5624 I bt_bluedroid: get_profile_interface pan
09-23 09:43:07.643  5624  5640 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 09:43:07.644  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:07.645  5495  5495 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:43:07.646  5495  5495 D PanProfile: Bluetooth service connected
09-23 09:43:07.646  5624  5624 D BluetoothMapService: Received start request. Starting profile...
09-23 09:43:07.646  5624  5624 D BluetoothMapService: start()
09-23 09:43:07.646  5495  5495 D BluetoothMap: Proxy object connected
09-23 09:43:07.647  5495  5495 D MapProfile: Bluetooth service connected
09-23 09:43:07.647  5495  5495 D BluetoothMap: getConnectedDevices()
09-23 09:43:07.647  5495  5495 D BluetoothMap: Bluetooth is Not enabled
,09-23 09:43:07.649  5624  5624 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 09:43:07.650  5624  5624 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 09:43:07.650  5624  5624 D BluetoothMapAppObserver: createReceiver()
,09-23 09:43:07.651  5624  5624 D BluetoothMapAppObserver: initObservers()
09-23 09:43:07.651  5624  5624 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 09:43:07.658  5624  5624 V SapService: SapBinder()
,09-23 09:43:07.658  5624  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:07.659  5624  5624 D SapService: Received start request. Starting profile...
09-23 09:43:07.659  5624  5624 V SapService: start()
,09-23 09:43:07.662  5624  5624 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:43:07.662  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.662  5624  5652 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 09:43:07.662  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.662  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:07.662  5624  5624 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.663  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.664  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:43:07.664  5624  5624 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:07.664  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.664  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.664  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:43:07.665  5624  5624 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:07.665  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.665  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.665  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:43:07.665  5624  5624 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:07.666  5624  5624 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:07.666  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:07.666  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:43:07.666  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 09:43:07.666  5624  5636 D BluetoothAdapterProperties: ScanMode =  20
,09-23 09:43:07.666  5624  5636 D BluetoothAdapterProperties: State =  11
,09-23 09:43:07.670  5624  5640 D BluetoothAdapterProperties: Scan Mode:21
09-23 09:43:07.670  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:07.670  5624  5640 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-23 09:43:07.670  5624  5636 D BluetoothAdapterProperties: Setting state to 12
09-23 09:43:07.670  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-23 09:43:07.671  5495  5508 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 09:43:07.671  5624  5636 I BluetoothAdapterState: Entering OnState
09-23 09:43:07.671  3143  3156 D BluetoothMap: onBluetoothStateChange: up=true
09-23 09:43:07.673  3143  3143 D BluetoothMap: Proxy object connected
09-23 09:43:07.673  3143  3143 D MapProfile: Bluetooth service connected
09-23 09:43:07.673  3546  3571 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:07.673  3143  3143 D BluetoothMap: getConnectedDevices()
09-23 09:43:07.673  3143  3157 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:07.675  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:07.675   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:07.675  5495  5505 D BluetoothMap: onBluetoothStateChange: up=true
09-23 09:43:07.676  5495  5508 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:43:07.676  3143  3143 D BluetoothA2dp: Proxy object connected
09-23 09:43:07.676  3143  3778 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:07.676  3143  3156 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:43:07.677  5624  5624 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 09:43:07.677  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:43:07.678  5624  5624 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 09:43:07.679  3143  3143 D BluetoothInputDevice: Proxy object connected
09-23 09:43:07.679  3143  3143 D HidProfile: Bluetooth service connected
09-23 09:43:07.679  5624  5624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:07.680   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:07.680  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:07.681  3143  3778 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:43:07.681  5624  5624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:07.682  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:07.682  3143  3156 D BluetoothPbap: onBluetoothStateChange: up=true
,09-23 09:43:07.683  5624  5624 D ObexServerSockets: Succeed to create listening sockets 
,09-23 09:43:07.683  5624  5624 D ObexServerSockets0: startAccept()
09-23 09:43:07.683  5624  5624 D ObexServerSockets0: prepareForNewConnect()
09-23 09:43:07.684   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:07.684   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:43:07.685   928   928 D BluetoothA2dp: Proxy object connected
09-23 09:43:07.685  5495  5505 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 09:43:07.685  5624  5624 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-23 09:43:07.685  5624  5624 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 09:43:07.685  3143  3143 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:43:07.685  3143  3143 D PanProfile: Bluetooth service connected
,09-23 09:43:07.688  5624  5662 D ObexServerSockets0: Accepting socket connection...
,09-23 09:43:07.688  5624  5661 D ObexServerSockets0: Accepting socket connection...
09-23 09:43:07.688  5624  5624 D BluetoothMapService: onReceive
09-23 09:43:07.688  5624  5624 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:43:07.689  5624  5624 D BluetoothMapService: STATE_ON
,09-23 09:43:07.689   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-23 09:43:07.691  5495  5495 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:07.692  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:07.693  5624  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:07.694  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:07.694  5624  5664 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 09:43:07.694  5624  5664 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-23 09:43:07.695  5495  5495 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-23 09:43:07.696  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:07.698  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:07.703  5495  5495 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:43:07.705  5495  5495 D BluetoothA2dp: Proxy object connected
,09-23 09:43:07.708  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:43:07.717  3143  3143 D BluetoothPbap: Proxy object connected
09-23 09:43:07.717  3143  3143 D PbapServerProfile: Bluetooth service connected
09-23 09:43:07.717  5624  5624 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 09:43:07.717  5624  5624 D ObexServerSockets0: prepareForNewConnect()
,09-23 09:43:07.719  5495  5495 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:43:07.720  5495  5495 D BluetoothPbap: Proxy object connected
09-23 09:43:07.721  5495  5495 D PbapServerProfile: Bluetooth service connected
,09-23 09:43:07.725  5624  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:43:07.738  5624  5672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:43:07.739  5624  5672 I BtOppRfcommListener: Accept thread started.
,09-23 09:43:07.774  3546  3803 D BluetoothHeadset: Proxy object connected
,09-23 09:43:07.775  3143  3778 D BluetoothHeadset: Proxy object connected
09-23 09:43:07.775  3143  3143 D HeadsetProfile: Bluetooth service connected
,09-23 09:43:07.775   928   928 D BluetoothHeadset: Proxy object connected
09-23 09:43:07.775   928   928 D BluetoothHeadset: Proxy object connected
09-23 09:43:07.775   928   928 D BluetoothHeadset: Proxy object connected
09-23 09:43:07.775   928   945 D BluetoothHeadset: Proxy object connected
,09-23 09:43:07.777  3143  3780 D BluetoothHeadset: Proxy object connected
09-23 09:43:07.777  3143  3143 D HeadsetProfile: Bluetooth service connected
,09-23 09:43:07.780   928   945 D BluetoothHeadset: Proxy object connected
,09-23 09:43:07.784   928   945 D BluetoothHeadset: Proxy object connected
,09-23 09:43:07.801  5495  5505 D BluetoothHeadset: Proxy object connected
,09-23 09:43:07.802  5495  5495 D HeadsetProfile: Bluetooth service connected
,09-23 09:43:08.108   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:09.109   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 09:43:09.418   928  2977 D ConnectivityService: handlePromptUnvalidated 101
,09-23 09:43:11.609  5624  5636 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 09:43:11.609  5624  5636 D BluetoothAdapterProperties: Setting state to 13
09-23 09:43:11.609  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 09:43:11.610  5624  5636 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 09:43:11.612  5624  5636 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:43:11.617  5624  5624 D BluetoothMapService: onReceive
,09-23 09:43:11.617  5624  5624 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-23 09:43:11.617  5624  5624 D BluetoothMapService: STATE_TURNING_OFF
,09-23 09:43:11.618  5624  5624 D BluetoothMapService: MAP Service closeService in
09-23 09:43:11.618  5624  5624 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 09:43:11.618  5624  5624 D ObexServerSockets0: shutdown(block = true)
09-23 09:43:11.621  5624  5640 D BluetoothAdapterProperties: Scan Mode:20
,09-23 09:43:11.622  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 09:43:11.622  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:11.622  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:43:11.623  5624  5661 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 09:43:11.623  5624  5624 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 09:43:11.625  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:43:11.625  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:11.626  5624  5662 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 09:43:11.627  5624  5624 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-23 09:43:11.628  5624  5649 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-23 09:43:11.629  5624  5624 I BtOppRfcommListener: stopping Accept Thread
,09-23 09:43:11.629  5624  5672 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 09:43:11.630  5624  5672 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-23 09:43:11.630  5495  5495 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:43:11.631  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:11.632  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:43:11.632  5624  5624 D HeadsetService: Received stop request...Stopping profile...
09-23 09:43:11.635  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:11.635  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:11.637  3546  3804 D BluetoothHeadset: Proxy object disconnected
09-23 09:43:11.638  5495  5508 D BluetoothHeadset: Proxy object disconnected
09-23 09:43:11.638  3143  3780 D BluetoothHeadset: Proxy object disconnected
09-23 09:43:11.640  5624  5624 D A2dpService: Received stop request...Stopping profile...
09-23 09:43:11.639   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 09:43:11.640   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 09:43:11.640   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 09:43:11.640  5624  5655 D A2dpStateMachine: Exit Disconnected: -1
09-23 09:43:11.641   928   928 D BluetoothA2dp: Proxy object disconnected
09-23 09:43:11.641  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:11.642  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:11.643  5442  5442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:43:11.643  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:11.644  5624  5624 D HidService: Received stop request...Stopping profile...
09-23 09:43:11.644  5624  5624 D HidService: Stopping Bluetooth HidService
09-23 09:43:11.645  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:11.647  5495  5495 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:43:11.647  5624  5624 D HealthService: Received stop request...Stopping profile...
09-23 09:43:11.648  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.648  5495  5495 D HeadsetProfile: Bluetooth service disconnected
09-23 09:43:11.648  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:11.648  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:11.648  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.649  5495  5495 D BluetoothA2dp: Proxy object disconnected
09-23 09:43:11.649  5495  5495 D BluetoothInputDevice: Proxy object disconnected
09-23 09:43:11.649  5495  5495 D HidProfile: Bluetooth service disconnected
09-23 09:43:11.651  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:11.654  5624  5624 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 09:43:11.655  5624  5624 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 09:43:11.655  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:43:11.655  5624  5647 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:43:11.655  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.655  5624  5647 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:43:11.655  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:11.655  5624  5647 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:43:11.655  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:11.655  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.656  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:11.656  5624  5624 D PanService: Received stop request...Stopping profile...
09-23 09:43:11.656  3143  3143 D HeadsetProfile: Bluetooth service disconnected
,09-23 09:43:11.657  3143  3143 D BluetoothA2dp: Proxy object disconnected
09-23 09:43:11.657  3143  3143 D BluetoothInputDevice: Proxy object disconnected
09-23 09:43:11.657  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 09:43:11.657  3143  3143 D HidProfile: Bluetooth service disconnected
09-23 09:43:11.657  3143  3143 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 09:43:11.657  5624  5640 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 09:43:11.657  3143  3143 D PanProfile: Bluetooth service disconnected
09-23 09:43:11.658  5495  5495 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 09:43:11.658  5495  5495 D PanProfile: Bluetooth service disconnected
09-23 09:43:11.659  5624  5647 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 09:43:11.659  5624  5647 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 09:43:11.659  5624  5647 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:43:11.659  5624  5647 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-23 09:43:11.659  5624  5647 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-23 09:43:11.659  5624  5647 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:43:11.659  5624  5624 D BluetoothMapService: Received stop request...Stopping profile...
09-23 09:43:11.659  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 09:43:11.660  5624  5624 D BluetoothMapService: stop()
09-23 09:43:11.660  5624  5624 D BluetoothMapAppObserver: deinitObservers()
09-23 09:43:11.660  5624  5624 D BluetoothMapAppObserver: removeReceiver()
09-23 09:43:11.661  3143  3143 D BluetoothMap: Proxy object disconnected
09-23 09:43:11.661  3143  3143 D MapProfile: Bluetooth service disconnected
09-23 09:43:11.662  5495  5495 D BluetoothMap: Proxy object disconnected
09-23 09:43:11.662  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.662  5495  5495 D MapProfile: Bluetooth service disconnected
09-23 09:43:11.662  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:11.662  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:11.662  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.662  5624  5624 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 09:43:11.662  5624  5624 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 09:43:11.663  5624  5624 D SapService: Received stop request...Stopping profile...
09-23 09:43:11.663  5624  5624 V SapService: stop()
09-23 09:43:11.665  5624  5640 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 09:43:11.665  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.665  5624  5624 V BluetoothAdapterState: isTurningOn()=false
,09-23 09:43:11.665  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:11.665  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.665  5624  5624 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 09:43:11.665  5624  5640 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 09:43:11.666  5624  5624 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 09:43:11.668  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.668  5624  5624 V BluetoothAdapterState: isTurningOn()=false
,09-23 09:43:11.668  3143  3143 D BluetoothPbap: Proxy object disconnected
09-23 09:43:11.668  3143  3143 D PbapServerProfile: Bluetooth service disconnected
09-23 09:43:11.668  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:11.668  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.669  5495  5495 D BluetoothPbap: Proxy object disconnected
09-23 09:43:11.669  5495  5495 D PbapServerProfile: Bluetooth service disconnected
,09-23 09:43:11.669  5624  5624 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 09:43:11.669  5624  5624 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 09:43:11.670  5624  5624 D BluetoothMapService: MAP Service closeService in
09-23 09:43:11.670  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.670  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:11.670  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 09:43:11.670  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.671  5624  5624 D BluetoothMapService: cleanup()
09-23 09:43:11.671  5624  5624 D BluetoothMapService: MAP Service closeService in
09-23 09:43:11.671  5624  5624 V BluetoothAdapterState: isTurningOff()=true
09-23 09:43:11.671  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:11.671  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:11.671  5624  5624 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:11.672  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 09:43:11.672  5624  5636 D BluetoothAdapterProperties: Setting state to 15
09-23 09:43:11.672  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 09:43:11.672  5624  5636 I BluetoothAdapterState: Entering BleOnState
09-23 09:43:11.674  5495  5505 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 09:43:11.674  3143  3780 D BluetoothMap: onBluetoothStateChange: up=false
09-23 09:43:11.675  3546  3570 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:43:11.675  3143  3156 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:43:11.676  5495  5508 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:43:11.676   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:43:11.676  5495  5505 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-23 09:43:11.677  5495  5508 D BluetoothMap: onBluetoothStateChange: up=false
,09-23 09:43:11.678  5495  5505 D BluetoothPan: onBluetoothStateChange on: false
,09-23 09:43:11.678  3143  3778 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:43:11.679  3143  3157 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 09:43:11.680   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:43:11.680  3143  3156 D BluetoothPan: onBluetoothStateChange on: false
09-23 09:43:11.682  3143  3157 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 09:43:11.683   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:43:11.683   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:43:11.683  5495  5508 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 09:43:11.683  5624  5636 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 09:43:11.683  5624  5636 D BluetoothAdapterProperties: Setting state to 16
09-23 09:43:11.684  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 09:43:11.684  5624  5636 D BluetoothAdapterProperties: onBleDisable
09-23 09:43:11.684  5624  5636 I BluetoothAdapterState: Entering PendingCommandState
09-23 09:43:11.684  5624  5637 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-23 09:43:11.685  5624  5647 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 09:43:11.686  5624  5647 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:43:11.686  5624  5640 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:43:11.687  5495  5495 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:43:11.687  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:11.689  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:11.690  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:11.692  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:11.694  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:11.694  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:43:11.695  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:11.695  5495  5495 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:43:11.896  5624  5640 I bt_hci  : shut_down
,09-23 09:43:11.901  5624  5644 D bt_hwcfg: hw_epilog_process
09-23 09:43:11.902  5624  5644 I bt_vendor: low_power_mode_cb
,09-23 09:43:11.904  5624  5644 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 09:43:11.904  5624  5644 I bt_vendor: epilog_cb
09-23 09:43:11.904  5624  5644 I bt_hci  : epilog_finished_callback
,09-23 09:43:11.908  5624  5640 I bt_hci_h4: hal_close
,09-23 09:43:11.908  5624  5640 I bt_userial_vendor: device fd = 54 close
,09-23 09:43:12.017  5624  5637 D bt_stack_manager: event_shut_down_stack finished.
,09-23 09:43:12.018  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-23 09:43:12.023  5624  5636 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 09:43:12.023  5624  5624 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 09:43:12.025  5624  5624 D BtGatt.GattService: Received stop request...Stopping profile...
,09-23 09:43:12.025  5624  5624 D BtGatt.GattService: stop()
09-23 09:43:12.025  5624  5624 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 09:43:12.029  5624  5624 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:43:12.030  5624  5624 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:12.030  5624  5624 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:12.030  5624  5624 V BluetoothAdapterState: isBleTurningOff()=true
09-23 09:43:12.030  5624  5636 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 09:43:12.031  5624  5636 D BluetoothAdapterProperties: Setting state to 10
,09-23 09:43:12.031  5624  5636 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 09:43:12.032  5624  5636 I BluetoothAdapterState: Entering OffState
09-23 09:43:12.033   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-23 09:43:12.051  5624  5624 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-23 09:43:12.052  5624  5624 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 09:43:12.052  5624  5624 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 09:43:12.054  5624  5637 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 09:43:12.060  5624  5624 I art     : System.exit called, status: 0
,09-23 09:43:12.060  5624  5624 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 09:43:12.089   928  3409 I ActivityManager: Process com.android.bluetooth (pid 5624) has died
,09-23 09:43:16.607  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:43:16.608  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:16.613  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:43:16.613  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dfb27ba removed from the list
09-23 09:43:16.613  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:16.613  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:16.614  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:16.616  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:16.616  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7945c8 added. We now have 4 listener(s)
09-23 09:43:16.617  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:43:16.620  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:43:16.620  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7945c8 removed from the list
09-23 09:43:16.621  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:16.621  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:16.621  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:16.623  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:16.623  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95d661 added. We now have 4 listener(s)
09-23 09:43:16.623  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:43:21.633  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:21.673   928   945 I ActivityManager: Start proc 5680:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 09:43:21.759  5680  5680 D AdapterServiceConfig: Adding HeadsetService
,09-23 09:43:21.759  5680  5680 D AdapterServiceConfig: Adding A2dpService
,09-23 09:43:21.760  5680  5680 D AdapterServiceConfig: Adding HidService
,09-23 09:43:21.760  5680  5680 D AdapterServiceConfig: Adding HealthService
09-23 09:43:21.760  5680  5680 D AdapterServiceConfig: Adding PanService
09-23 09:43:21.760  5680  5680 D AdapterServiceConfig: Adding GattService
09-23 09:43:21.760  5680  5680 D AdapterServiceConfig: Adding BluetoothMapService
09-23 09:43:21.761  5680  5680 D AdapterServiceConfig: Adding SapService
,09-23 09:43:21.772   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@64a1d4b:true
,09-23 09:43:21.772  5680  5680 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 09:43:21.774  5680  5680 I bt_bluedroid: init
,09-23 09:43:21.775  5680  5692 I BluetoothAdapterState: Entering OffState
,09-23 09:43:21.777  5680  5693 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-23 09:43:21.777  5680  5693 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 09:43:21.777  5680  5693 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 09:43:21.777  5680  5693 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-23 09:43:21.778  5680  5680 I bt_bluedroid: get_profile_interface socket
,09-23 09:43:21.780  5680  5696 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 09:43:21.780  5680  5680 I bt_bluedroid: get_profile_interface sdp
,09-23 09:43:21.781  5680  5696 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 09:43:21.785  5680  5690 I bt_bluedroid: config_hci_snoop_log
,09-23 09:43:21.786   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 09:43:21.790  5680  5692 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 09:43:21.791  5680  5692 D BluetoothAdapterProperties: Setting state to 14
09-23 09:43:21.791  5680  5692 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 09:43:21.792  5680  5692 D BluetoothBondStateMachine: make
09-23 09:43:21.794  5680  5697 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 09:43:21.796  5680  5692 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:43:21.797  5680  5680 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 09:43:21.800  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:21.800  5680  5680 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 09:43:21.801  5680  5680 D BtGatt.GattService: Received start request. Starting profile...
09-23 09:43:21.801  5680  5680 D BtGatt.GattService: start()
09-23 09:43:21.801  5680  5680 I bt_bluedroid: get_profile_interface gatt
09-23 09:43:21.802  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:21.802  5680  5680 D BtGatt.AdvertiseManager: advertise manager created
,09-23 09:43:21.807  5680  5680 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:43:21.807  5680  5680 V BluetoothAdapterState: isTurningOn()=false
09-23 09:43:21.807  5680  5680 V BluetoothAdapterState: isBleTurningOn()=true
09-23 09:43:21.807  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:21.808  5680  5692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 09:43:21.809  5680  5692 I bt_bluedroid: bt_bluedroid
,09-23 09:43:21.809  5680  5693 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 09:43:21.809  5680  5693 I bt_hci  : start_up
,09-23 09:43:21.815  5680  5693 I bt_vendor: alloc value 0xf424d871
,09-23 09:43:21.816  5680  5693 I bt_vendor: init
09-23 09:43:21.816  5680  5693 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 09:43:21.816  5680  5693 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 09:43:21.927  5680  5693 D bt_hci  : start_up starting async portion
,09-23 09:43:21.927  5680  5700 I bt_hci  : event_finish_startup
09-23 09:43:21.927  5680  5700 I bt_hci_h4: hal_open
09-23 09:43:21.928  5680  5700 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 09:43:21.927  5701  5701 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 09:43:21.932  5680  5700 I bt_userial_vendor: device fd = 54 open
,09-23 09:43:21.948  5680  5700 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 09:43:21.951  5680  5700 D bt_hwcfg: Chipset BCM4358A3
,09-23 09:43:21.951  5680  5700 D bt_hwcfg: Target name = [BCM4358A3]
09-23 09:43:21.951  5680  5700 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 09:43:22.461  5680  5700 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 09:43:22.462  5680  5700 D bt_hwcfg: Settlement delay -- 100 ms
,09-23 09:43:22.462  5680  5700 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 09:43:22.596  5680  5700 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 09:43:22.596  5680  5700 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 09:43:22.598  5680  5700 I bt_hwcfg: vendor lib fwcfg completed
09-23 09:43:22.598  5680  5700 I bt_vendor: firmware callback
,09-23 09:43:22.598  5680  5700 I bt_hci  : firmware_config_callback
,09-23 09:43:22.608  5680  5703 I bt_btu  : btu_task pending for preload complete event
09-23 09:43:22.608  5680  5703 I bt_btu_task: Bluetooth chip preload is complete
,09-23 09:43:22.608  5680  5703 I bt_btu  : btu_task received preload complete event
,09-23 09:43:22.615  5680  5703 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 09:43:22.615  5680  5703 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 09:43:22.615  5680  5703 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 09:43:22.615  5680  5703 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 09:43:22.616  5680  5703 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 09:43:22.616  5680  5703 I         : BTE_InitTraceLevels -- TRC_A2D
,09-23 09:43:22.616  5680  5703 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 09:43:22.616  5680  5703 I         : BTE_InitTraceLevels -- TRC_BTM
,09-23 09:43:22.617  5680  5703 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 09:43:22.617  5680  5703 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 09:43:22.618  5680  5703 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 09:43:22.618  5680  5703 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 09:43:22.618  5680  5703 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 09:43:22.618  5680  5703 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 09:43:22.618  5680  5703 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 09:43:22.710  5680  5703 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41cb549
09-23 09:43:22.710  5680  5703 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41cb549 
,09-23 09:43:22.723  5680  5696 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 09:43:22.725  5680  5696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 09:43:22.726  5680  5696 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 09:43:22.727  5680  5696 D BluetoothAdapterProperties: Name is: Nexus 6P
09-23 09:43:22.729  5680  5696 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:43:22.729  5680  5696 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 09:43:22.730  5680  5696 D bt_hci  : do_postload posting postload work item
09-23 09:43:22.730  5680  5700 I bt_hci  : event_postload
09-23 09:43:22.730  5680  5700 I bt_vendor: sco_config_cb
,09-23 09:43:22.730  5680  5700 I bt_hci  : sco_config_callback postload finished.
,09-23 09:43:22.732  5680  5696 D bt_bte_conf: Device ID record 1 : primary
,09-23 09:43:22.733  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:22.733  5680  5696 D bt_bte_conf:   vendorId            = 000f
09-23 09:43:22.734  5680  5696 D bt_bte_conf:   vendorIdSource      = 0001
09-23 09:43:22.734  5680  5696 D bt_bte_conf:   product             = 1200
,09-23 09:43:22.734  5680  5696 D bt_bte_conf:   version             = 1436
09-23 09:43:22.734  5680  5696 D bt_bte_conf:   clientExecutableURL = 
,09-23 09:43:22.734  5680  5696 D bt_bte_conf:   serviceDescription  = 
09-23 09:43:22.734  5680  5696 D bt_bte_conf:   documentationURL    = 
09-23 09:43:22.734  5680  5696 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 09:43:22.735  5680  5693 D bt_stack_manager: event_start_up_stack finished
09-23 09:43:22.735  5680  5692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 09:43:22.737  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:22.738  5680  5692 D BluetoothAdapterProperties: Setting state to 15
,09-23 09:43:22.738  5680  5692 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 09:43:22.740  5680  5692 I BluetoothAdapterState: Entering BleOnState
09-23 09:43:22.740  5680  5700 I bt_vendor: low_power_mode_cb
,09-23 09:43:22.745  5680  5692 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 09:43:22.745  5680  5692 D BluetoothAdapterProperties: Setting state to 11
,09-23 09:43:22.745  5680  5692 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 09:43:22.753  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
,09-23 09:43:22.754  5680  5680 D HeadsetService: Received start request. Starting profile...
09-23 09:43:22.757  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:22.759  5680  5680 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 09:43:22.759  5680  5680 D HeadsetStateMachine: make
,09-23 09:43:22.759  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:22.772  5680  5692 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:43:22.775  5680  5680 D HeadsetStateMachine: max_hf_connections = 1
,09-23 09:43:22.775  5680  5680 I bt_bluedroid: get_profile_interface handsfree
09-23 09:43:22.775  5680  5696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 09:43:22.776  5680  5696 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-23 09:43:22.778  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:22.779  5680  5680 D A2dpService: Received start request. Starting profile...
,09-23 09:43:22.780  5680  5680 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 09:43:22.780  5680  5680 I bt_bluedroid: get_profile_interface avrcp
,09-23 09:43:22.787  5680  5680 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 09:43:22.787  5680  5680 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 09:43:22.787  5680  5680 D A2dpStateMachine: make
09-23 09:43:22.789  5680  5680 I bt_bluedroid: get_profile_interface a2dp
,09-23 09:43:22.790  5680  5696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 09:43:22.791  5680  5711 D A2dpStateMachine: Enter Disconnected: -2
,09-23 09:43:22.791  5680  5680 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 09:43:22.792  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:22.793  5680  5680 D HidService: Received start request. Starting profile...
09-23 09:43:22.793  5680  5680 I bt_bluedroid: get_profile_interface hidhost
09-23 09:43:22.793  5680  5680 D HidService: setHidService(): set to: null
09-23 09:43:22.793  5680  5696 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41ac56d
09-23 09:43:22.794  5680  5696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 09:43:22.795  5680  5680 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 09:43:22.796  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:22.796  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:43:22.797  5680  5680 D HealthService: Received start request. Starting profile...
,09-23 09:43:22.798  5680  5680 I bt_bluedroid: get_profile_interface health
,09-23 09:43:22.799  5680  5680 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-23 09:43:22.800  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:22.800  5680  5680 D PanService: Received start request. Starting profile...
09-23 09:43:22.801  5680  5680 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-23 09:43:22.801  5680  5680 I bt_bluedroid: get_profile_interface pan
09-23 09:43:22.801  5680  5696 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-23 09:43:22.805  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
,09-23 09:43:22.805  5680  5680 D BluetoothMapService: Received start request. Starting profile...
,09-23 09:43:22.805  5680  5680 D BluetoothMapService: start()
,09-23 09:43:22.808  5680  5680 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 09:43:22.809  5680  5680 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-23 09:43:22.809  5680  5680 D BluetoothMapAppObserver: createReceiver()
09-23 09:43:22.810  5680  5680 D BluetoothMapAppObserver: initObservers()
09-23 09:43:22.811  5680  5680 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 09:43:22.818  5680  5680 V SapService: SapBinder()
,09-23 09:43:22.818  5680  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:22.819  5680  5680 D SapService: Received start request. Starting profile...
09-23 09:43:22.819  5680  5680 V SapService: start()
,09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:22.821  5680  5709 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 09:43:22.821  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:22.822  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.822  5680  5680 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:22.822  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:22.822  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:22.822  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.822  5680  5680 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isTurningOn()=true
09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:43:22.823  5680  5680 V BluetoothAdapterState: isTurningOff()=false
09-23 09:43:22.824  5680  5680 V BluetoothAdapterState: isTurningOn()=true
,09-23 09:43:22.824  5680  5680 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:43:22.824  5680  5680 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:43:22.824  5680  5692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 09:43:22.825  5680  5692 D BluetoothAdapterProperties: ScanMode =  20
,09-23 09:43:22.825  5680  5692 D BluetoothAdapterProperties: State =  11
,09-23 09:43:22.825  5680  5692 D BluetoothAdapterProperties: Setting state to 12
09-23 09:43:22.825  5680  5692 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 09:43:22.826  5680  5692 I BluetoothAdapterState: Entering OnState
09-23 09:43:22.826  5680  5696 D BluetoothAdapterProperties: Scan Mode:21
09-23 09:43:22.826  5680  5696 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 09:43:22.826  5495  5508 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:43:22.828  3143  3157 D BluetoothMap: onBluetoothStateChange: up=true
09-23 09:43:22.830  3546  3570 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:22.830  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:22.831  3143  3156 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:43:22.831  3143  3143 D BluetoothMap: Proxy object connected
09-23 09:43:22.831  3143  3143 D MapProfile: Bluetooth service connected
09-23 09:43:22.831  3143  3143 D BluetoothMap: getConnectedDevices()
09-23 09:43:22.833  5495  5508 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:22.833  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:22.833   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:22.833  5495  5505 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:43:22.834  3143  3143 D BluetoothA2dp: Proxy object connected
09-23 09:43:22.835  5495  5508 D BluetoothMap: onBluetoothStateChange: up=true
09-23 09:43:22.836  5680  5680 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 09:43:22.837  5680  5680 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 09:43:22.837  5495  5505 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:22.839  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:22.839  5680  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:22.839  3143  3778 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:22.840  3143  3780 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:43:22.841  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:43:22.841  5680  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:22.841  5495  5495 D BluetoothInputDevice: Proxy object connected
09-23 09:43:22.841  5495  5495 D HidProfile: Bluetooth service connected
09-23 09:43:22.842   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:22.842  3143  3143 D BluetoothInputDevice: Proxy object connected
09-23 09:43:22.842  3143  3143 D HidProfile: Bluetooth service connected
09-23 09:43:22.842  3143  3157 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:43:22.843  5680  5680 D ObexServerSockets: Succeed to create listening sockets 
09-23 09:43:22.843  5680  5680 D ObexServerSockets0: startAccept()
09-23 09:43:22.843  5680  5680 D ObexServerSockets0: prepareForNewConnect()
09-23 09:43:22.843  3143  3780 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 09:43:22.845  5495  5495 D BluetoothA2dp: Proxy object connected
09-23 09:43:22.845   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:43:22.845   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:43:22.845  5680  5680 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 09:43:22.845  5680  5680 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 09:43:22.846   928   928 D BluetoothA2dp: Proxy object connected
,09-23 09:43:22.846  5495  5508 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 09:43:22.846  5680  5719 D ObexServerSockets0: Accepting socket connection...
09-23 09:43:22.847  3143  3143 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:43:22.847  3143  3143 D PanProfile: Bluetooth service connected
09-23 09:43:22.847  5495  5495 D BluetoothMap: Proxy object connected
09-23 09:43:22.847  5495  5495 D MapProfile: Bluetooth service connected
09-23 09:43:22.847  5680  5720 D ObexServerSockets0: Accepting socket connection...
,09-23 09:43:22.847  5495  5495 D BluetoothMap: getConnectedDevices()
09-23 09:43:22.849   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 09:43:22.850  5680  5680 D BluetoothMapService: onReceive
09-23 09:43:22.850  5680  5680 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:43:22.850  5680  5680 D BluetoothMapService: STATE_ON
09-23 09:43:22.851  5495  5495 D BluetoothPan: BluetoothPAN Proxy object connected
,09-23 09:43:22.851  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:22.851  5495  5495 D PanProfile: Bluetooth service connected
09-23 09:43:22.852  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:22.853  5680  5721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:22.854  5680  5721 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 09:43:22.854  5680  5721 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 09:43:22.856  5495  5495 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:43:22.863  5495  5495 D DockEventReceiver: finishStartingService: stopping service
09-23 09:43:22.863  3606  3606 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:43:22.869  5495  5495 D BluetoothPbap: Proxy object connected
09-23 09:43:22.869  5495  5495 D PbapServerProfile: Bluetooth service connected
,09-23 09:43:22.875  5680  5680 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 09:43:22.875  5680  5680 D ObexServerSockets0: prepareForNewConnect()
09-23 09:43:22.876  5680  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:43:22.885  3143  3143 D BluetoothPbap: Proxy object connected
09-23 09:43:22.885  3143  3143 D PbapServerProfile: Bluetooth service connected
,09-23 09:43:22.894  5680  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:43:22.895  5680  5729 I BtOppRfcommListener: Accept thread started.
,09-23 09:43:22.932  3546  3571 D BluetoothHeadset: Proxy object connected
,09-23 09:43:22.933  5495  5505 D BluetoothHeadset: Proxy object connected
,09-23 09:43:22.933  3143  3778 D BluetoothHeadset: Proxy object connected
09-23 09:43:22.933   928   928 D BluetoothHeadset: Proxy object connected
09-23 09:43:22.933   928   928 D BluetoothHeadset: Proxy object connected
09-23 09:43:22.933   928   928 D BluetoothHeadset: Proxy object connected
09-23 09:43:22.933  3143  3143 D HeadsetProfile: Bluetooth service connected
09-23 09:43:22.934  5495  5495 D HeadsetProfile: Bluetooth service connected
09-23 09:43:22.934  5495  5718 D BluetoothHeadset: Proxy object connected
09-23 09:43:22.935   928   945 D BluetoothHeadset: Proxy object connected
,09-23 09:43:22.936  5495  5495 D HeadsetProfile: Bluetooth service connected
,09-23 09:43:22.940  3143  3157 D BluetoothHeadset: Proxy object connected
,09-23 09:43:22.940  3143  3143 D HeadsetProfile: Bluetooth service connected
,09-23 09:43:22.942   928   945 D BluetoothHeadset: Proxy object connected
,09-23 09:43:22.946   928   945 D BluetoothHeadset: Proxy object connected
,09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:26.648  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:43:26.653  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:43:26.654  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:26.654  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95d661 removed from the list
09-23 09:43:26.654  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:43:26.654  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:26.655  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:26.658  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:26.658  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7240586 added. We now have 4 listener(s)
09-23 09:43:26.658  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:43:26.661   928   938 D WifiService: setWifiEnabled: false pid=5442, uid=10077
,09-23 09:43:26.661   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:43:29.110   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:30.112   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:31.113   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:31.671  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:31.673   928  5210 D WifiService: setWifiEnabled: true pid=5442, uid=10077
09-23 09:43:31.673   928  5210 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:43:31.685   507   925 D SoftapController: Softap fwReload - Ok
,09-23 09:43:31.690   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:31.690   507   925 D CommandListener: Trying to bring down wlan0
09-23 09:43:31.692   507   925 D CommandListener: Clearing all IP addresses on wlan0
09-23 09:43:31.696   928  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 09:43:32.114   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:32.367   928  2975 D wifi    : set interface wlan0 flags (UP)
,09-23 09:43:32.367   928  2975 I WifiHAL : Initializing wifi
09-23 09:43:32.367   928  2975 I WifiHAL : Creating socket
09-23 09:43:32.373   928  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-23 09:43:32.373   928  2975 D wifi    : Did set static halHandle = 0x7f6a9c9a00
09-23 09:43:32.374   928  2975 D wifi    : halHandle = 0x7f6a9c9a00, mVM = 0x7f86acd140, mCls = 0x101462
09-23 09:43:32.374   928  2975 D wifi    : array field set
09-23 09:43:32.374   928  2975 I WifiNative-HAL: interface[0] = wlan0
09-23 09:43:32.378   928  5735 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547249494528
09-23 09:43:32.378   928  5735 D wifi    : waitForHalEvents called, vm = 0x7f86acd140, obj = 0x101462, env = 0x7f6a4b0c00
09-23 09:43:32.381   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 09:43:32.441  5736  5736 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 09:43:32.461  5736  5736 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:43:32.479   928  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 09:43:32.484  5736  5736 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-23 09:43:32.485  5736  5736 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
09-23 09:43:32.488  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:32.492  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:32.511   928  2975 D WifiConfigStore: Loading config and enabling all networks 
,09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:32.513  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:43:32.516  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:43:32.520  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:43:32.522  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:43:32.522   928  2975 D WifiConfigStore: loaded 0 passpoint configs
09-23 09:43:32.523   928  2975 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 09:43:32.523   928  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 09:43:32.524   928  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 09:43:32.525   928  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 09:43:32.525   928  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 09:43:32.525   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 09:43:32.525   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 09:43:32.529   928  2975 D WifiNative-HAL: Setting external_sim to 1
,09-23 09:43:32.529   928  2975 D wifi    : setting dfs flag to true, 0x7f6c998360
,09-23 09:43:32.530   928  2975 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 09:43:32.530   928  2975 D wifi    : setting scan oui 0x7f6c998360
09-23 09:43:32.530   928  2975 D WifiHAL : Sending mac address OUI
09-23 09:43:32.531  4300  4300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 09:43:32.535   928  2975 E native  : do suspend false
,09-23 09:43:32.543   928  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 09:43:32.543   928   928 D RttService: SCAN_AVAILABLE : 3
09-23 09:43:32.543   507   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 09:43:32.543   928  3080 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 09:43:32.544   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:32.550   928  2948 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '97 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 97 Failed to set address (No such device)'
09-23 09:43:32.550   928  2948 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 09:43:32.559   928  2948 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 09:43:32.564   928  2948 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 09:43:32.564   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302778 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-23 09:43:33.115   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:43:34.116   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 09:43:35.721  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:35.732  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:35.738  5736  5736 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:43:35.774   928  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-23 09:43:35.774   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 09:43:35.775   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:43:35.788   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 09:43:35.831   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 09:43:35.834  5736  5736 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 09:43:36.267  5736  5736 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 09:43:36.309  5736  5736 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 09:43:36.311  5736  5736 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 09:43:36.321   928  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:43:36.321   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 09:43:36.321   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 09:43:36.340   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:43:36.355   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:36.363   928  2975 D WifiStateMachine: Start Dhcp Watchdog 3
,09-23 09:43:36.373   928  5741 D DhcpClient: Receive thread started
,09-23 09:43:36.379   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-23 09:43:36.379   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-23 09:43:36.380   928  2977 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-23 09:43:36.468   928  2975 E native  : do suspend false
,09-23 09:43:36.488   928  5740 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 09:43:36.503   928  5741 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-23 09:43:36.505   928  5740 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-23 09:43:36.507   928  5740 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 09:43:36.525   928  5741 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 09:43:36.527   928  5740 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 09:43:36.531   507   925 D CommandListener: Setting iface cfg
,09-23 09:43:36.536   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 09:43:36.542   928  5740 D DhcpClient: Scheduling renewal in 86399s
,09-23 09:43:36.554   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 09:43:36.555   928  2975 D WifiConfigStore: No blacklist allowed without epno enabled
09-23 09:43:36.557   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-23 09:43:36.558   928  2977 D ConnectivityService: Adding iface wlan0 to network 102
09-23 09:43:36.561   928  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 09:43:36.609   928  2977 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 09:43:36.610   928  2977 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-23 09:43:36.612   928  2977 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-23 09:43:36.615   928  2977 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-23 09:43:36.618   928  2977 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-23 09:43:36.630   928  2977 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-23 09:43:36.634   928  2977 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-23 09:43:36.634   928  2977 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-23 09:43:36.634   928  2977 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-23 09:43:36.634   928  2977 D ConnectivityService:    accepting network in place of null
09-23 09:43:36.634   928  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 09:43:36.635   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:43:36.635   928  2977 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:43:36.656   928  5739 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306870, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 09:43:36.659   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:43:36.681   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:43:36.684   928  2977 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-23 09:43:36.684   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:43:36.684  3498  3700 W QCNEJ   : |CORE| network available: 102
09-23 09:43:36.685   928  2977 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-23 09:43:36.686   928   945 D Tethering: MasterInitialState.processMessage what=3
09-23 09:43:36.689  3498  3700 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-23 09:43:36.690  3498  3700 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-23 09:43:36.690  3498  3700 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:36.693  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:36.696  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:36.698  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:36.699  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:36.699  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7240586 removed from the list
09-23 09:43:36.699  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:36.699  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:36.699  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:36.701  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:36.703  5442  5750 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-23 09:43:36.703  5442  5750 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-23 09:43:36.704  4907  4920 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:43:36.704  4907  4920 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:43:36.704  4907  4920 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 09:43:36.704  4907  4920 E SarControlService: no key has been found,reset the power
09-23 09:43:36.704  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:43:36.704  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:43:36.704  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 09:43:36.705  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:43:36.705  4933  4933 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 09:43:36.706  4907  4945 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 09:43:36.706  4907  4945 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:43:36.706  4907  4945 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:36.706  5442  5442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:43:36.706  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:43:36.707  4933  4933 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:43:36.708  5442  5442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:36.709  3899  3899 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 09:43:36.713  3899  3899 D SystemUpdateService: onCreate
09-23 09:43:36.713  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000f003000000000000ffffffff]
09-23 09:43:36.714  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:43:36.714  4933  4947 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-23 09:43:36.714  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:43:36.714  4907  4918 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:43:36.718  3899  3899 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 09:43:36.719  4933  4947 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f50d0d9 HexData = [00000000f103000000000000ffffffff]
09-23 09:43:36.719  4933  4947 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:43:36.719  4933  4947 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-23 09:43:36.720  4933  4933 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:43:36.720  4907  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 09:43:36.731  3899  3899 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-23 09:43:36.734   928  5738 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-23 09:43:36.737  3899  5221 I iu.UploadsManager: num queued entries: 0
09-23 09:43:36.738  3899  5221 I iu.UploadsManager: num updated entries: 0
09-23 09:43:36.738  3899  5221 I iu.SyncManager: NEXT; no task
09-23 09:43:36.739  3899  5752 I SystemUpdateService: active receiver: enabled
09-23 09:43:36.742  3899  3899 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-23 09:43:36.744  3899  3899 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-23 09:43:36.746  5224  5224 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-23 09:43:36.749  5224  5224 D SprintDMHelper: simOperator: 
09-23 09:43:36.750  5224  5224 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:43:36.770  3899  5752 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:43:36.783  3899  5752 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 09:43:36.783  3899  5752 I SystemUpdateService: now status is 0 (complete)
09-23 09:43:36.783  3899  5752 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 09:43:36.783  3899  5752 I SystemUpdateService: file has been verified
09-23 09:43:36.784  3899  5752 I SystemUpdateService: OTA package size = 21989297
,09-23 09:43:36.789  3899  5752 I SystemUpdateService: showing system update notification
,09-23 09:43:36.793   928  5738 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 13:43:36 GMT], X-Android-Received-Millis=[1474638216792], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474638216761]}
,09-23 09:43:36.793   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-23 09:43:36.793   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-23 09:43:36.794   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-23 09:43:36.795   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 09:43:36.799  3899  3899 D SystemUpdateService: onDestroy
,09-23 09:43:36.855  4300  5756 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 09:43:39.404   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-23 09:43:39.715  5442  5750 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-23 09:43:39.716  5442  5750 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:43:39.716  5442  5764 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-23 09:43:39.717  5442  5764 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:43:39.717  5442  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:43:39.717  5442  5764 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:43:39.718  5442  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:43:39.720  5442  5764 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:43:39.722  5442  5766 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender)
,09-23 09:43:39.723  5442  5750 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 09:43:39.723  5442  5764 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-23 09:43:39.724  5442  5767 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Sender)
09-23 09:43:39.726  5442  5769 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Receiver)
,09-23 09:43:39.728  5442  5769 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: IncomingSocketThread/Receiver)
,09-23 09:43:39.728  5442  5769 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 09:43:39.728  5442  5769 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-23 09:43:39.730  5442  5768 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
,09-23 09:43:39.732  5442  5768 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
,09-23 09:43:39.733  5442  5768 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-23 09:43:39.733  5442  5768 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 09:43:42.710  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-23 09:43:42.711  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-23 09:43:42.718  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2886e4d Bundle[{}]
,09-23 09:43:42.720  5442  5488 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 09:43:42.720  5442  5488 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-23 09:43:42.721  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-23 09:43:42.723  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-23 09:43:42.724  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-23 09:43:42.725  5442  5488 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-23 09:43:42.731  5442  5488 I System.out: Running OutgoingSocketThread
,09-23 09:43:42.733  5442  5770 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-23 09:43:42.733  5442  5770 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 09:43:44.640   928  2977 D ConnectivityService: handlePromptUnvalidated 102
,09-23 09:43:45.744  5442  5770 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-23 09:43:45.744  5442  5771 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-23 09:43:45.744  5442  5770 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:43:45.744  5442  5771 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:43:45.744  5442  5770 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:43:45.744  5442  5771 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:43:45.746  5442  5771 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:43:45.746  5442  5770 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:43:45.748  5442  5773 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
09-23 09:43:45.749  5442  5770 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 09:43:45.753  5442  5771 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 09:43:45.756  5442  5774 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender)
,09-23 09:43:45.759  5442  5775 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Receiver)
,09-23 09:43:45.760  5442  5776 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,09-23 09:43:45.761  5442  5775 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: OutgoingSocketThread/Receiver)
,09-23 09:43:45.761  5442  5775 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 09:43:45.761  5442  5775 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 09:43:45.762  5442  5776 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
09-23 09:43:45.762  5442  5776 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 09:43:45.762  5442  5776 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 09:43:47.567   928  2975 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-23 09:43:48.742  5442  5488 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-23 09:43:48.744  5442  5488 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-23 09:43:48.744  5442  5488 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,09-23 09:43:48.750  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:43:48.751  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa95e47 added. We now have 3 listener(s)
,09-23 09:43:48.754  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:43:48.754  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:43:48.754  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:43:48.755  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:48.755  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c0f674 added. We now have 4 listener(s)
09-23 09:43:48.755  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:43:48.756  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:43:48.760  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:48.766  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:48.770  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:43:48.770  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:43:48.771  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:43:48.771  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:43:48.771  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:43:48.772  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:43:48.772  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:48.772  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:48.772  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 09:43:48.772  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa95e47 removed from the list
09-23 09:43:48.772  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:48.772  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c0f674 removed from the list
,09-23 09:43:48.775  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:48.778  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:48.779  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:48.779  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:48.780  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:48.780  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:48.781  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:48.781  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:48.781  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:48.781  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c0f674 not in the list
09-23 09:43:48.781  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:48.782  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:48.783  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:48.783  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:48.783  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:48.783  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c0f674 not in the list
09-23 09:43:48.783  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:43:48.783  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:48.783  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:48.783  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa95e47 not in the list
09-23 09:43:48.784  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:43:48.784  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aaf412 added. We now have 3 listener(s)
09-23 09:43:48.786  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:43:48.786  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:43:48.786  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:43:48.786  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:48.786  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1397e3 added. We now have 4 listener(s)
09-23 09:43:48.787  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:43:48.787  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:43:48.791  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:48.796  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:48.798  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:43:48.799  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:43:48.799  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:43:48.799  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:43:48.799  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:43:48.799  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:48.799  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:43:48.803  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:43:48.803  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:43:48.803  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:48.809  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:48.809  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:43:48.811  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:43:48.811  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:43:48.815  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:43:48.815  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:43:48.815  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:43:48.816  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:43:48.820  5680  5717 D BtGatt.GattService: registerClient() - UUID=7343ab21-9c9e-4f3c-9adc-942a451cf6f3
09-23 09:43:48.821  5680  5696 D BtGatt.GattService: onClientRegistered() - UUID=7343ab21-9c9e-4f3c-9adc-942a451cf6f3, clientIf=5
,09-23 09:43:48.822  5442  5537 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 09:43:48.823  5680  5708 D BtGatt.GattService: start scan with filters
,09-23 09:43:48.827  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:43:48.827  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 09:43:48.828  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:43:48.828  5680  5699 D BtGatt.ScanManager: handling starting scan
09-23 09:43:48.828  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 09:43:48.829  5680  5699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9bff76
09-23 09:43:48.831  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:43:48.831  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:43:48.831  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:43:48.833  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 09:43:48.836  5442  5488 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 09:43:48.837  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:43:48.837  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:43:48.837  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:48.837  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:43:48.837  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:43:48.837  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:43:48.837  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:43:48.837  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:43:48.837  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:43:48.837  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:43:48.837  5680  5696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:43:48.837  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:48.838  5680  5699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-23 09:43:48.838  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:48.839  5680  5708 D BtGatt.GattService: stopScan() - queue size =1
09-23 09:43:48.840  5680  5716 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 09:43:48.841  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:48.841  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:43:48.841  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:43:48.841  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:43:48.841  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:43:48.842  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:43:48.842  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:48.842  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:43:48.843  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:48.843  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:48.845  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:43:48.845  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:48.845  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:43:48.846  5680  5696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 09:43:48.846  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:43:48.847  5680  5699 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 09:43:48.848  5680  5699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 09:43:48.850  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:43:48.850  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:43:48.855  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:43:48.857  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:43:48.857  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:43:48.857  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:48.857  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:48.860  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:43:48.860  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:48.860  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:43:48.862  5680  5696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 09:43:48.862  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:48.863  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:43:48.863  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:43:48.864  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:43:48.866  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:43:48.868  5680  5696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 09:43:48.868  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:43:48.876  5680  5696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:43:48.876  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:48.876  5680  5699 D BtGatt.ScanManager: stopping BLe Batch
,09-23 09:43:48.882  5680  5696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:43:48.882  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:48.882  5680  5699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 09:43:48.888  5680  5696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-23 09:43:48.888  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:43:49.368  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-23 09:43:49.368  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:43:49.369  5442  5442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:43:51.845  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:43:51.846  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:43:51.846  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:43:51.846  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:43:51.847  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:51.847  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:51.847  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:43:51.847  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aaf412 removed from the list
09-23 09:43:51.847  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:43:51.848  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1397e3 removed from the list
,09-23 09:43:51.848  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:51.848  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:51.849  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:51.850  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:51.854  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:51.854  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:51.854  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:43:51.856  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:51.856  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:43:51.857  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:51.857  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:43:51.857  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1397e3 not in the list
09-23 09:43:51.857  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:51.857  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:51.860  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:43:51.862  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:43:51.863  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:43:51.863  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:51.863  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:51.863  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:51.863  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:51.863  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1397e3 not in the list
09-23 09:43:51.864  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:43:51.864  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:51.864  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:51.864  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aaf412 not in the list
09-23 09:43:51.865  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:43:51.865  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cedb0f8 added. We now have 3 listener(s)
,09-23 09:43:51.867  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:43:51.867  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:43:51.868  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:43:51.868  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:51.868  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f019d1 added. We now have 4 listener(s)
09-23 09:43:51.868  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:43:51.869  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:43:51.873  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:51.879  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:51.882  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:43:51.882  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:43:51.882  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 09:43:51.884  5442  5488 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-23 09:43:51.884  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 09:43:51.884  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 09:43:51.884  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 09:43:51.884  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 09:43:51.884  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:51.887  5708  5708 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33034]" dev="sockfs" ino=33034 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:43:51.887  5708  5708 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33034]" dev="sockfs" ino=33034 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:43:51.886  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 09:43:51.886  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 09:43:51.886  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 09:43:51.886  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 09:43:51.886  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-23 09:43:51.887  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:51.887  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:43:51.887  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:51.888  5442  5777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:43:51.890  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:51.890  5442  5442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 09:43:51.891  5442  5777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 09:43:51.892  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:43:51.892  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:43:51.896  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:43:51.897  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:43:51.897  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:43:51.899  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 09:43:51.899  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:43:51.900  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-23 09:43:51.900  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 09:43:51.901  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 09:43:51.901  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 09:43:51.902  5442  5488 D BluetoothAdapter: STATE_ON
,09-23 09:43:51.906  5680  5717 D BtGatt.GattService: registerClient() - UUID=0a88d168-7435-4b98-a407-35d3fadab959
,09-23 09:43:51.907  5680  5696 D BtGatt.GattService: onClientRegistered() - UUID=0a88d168-7435-4b98-a407-35d3fadab959, clientIf=5
09-23 09:43:51.907  5442  5453 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 09:43:51.910  5680  5698 D BtGatt.AdvertiseManager: message : 0
,09-23 09:43:51.912  5680  5698 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 09:43:51.922  5680  5696 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 09:43:51.928  5680  5696 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 09:43:51.928  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 09:43:51.929  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:43:51.930  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:43:51.931  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 09:43:51.931  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 09:43:51.931  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 09:43:51.931  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 09:43:51.931  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 09:43:51.932  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 09:43:51.933  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 09:43:51.934  5442  5442 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 09:43:51.934  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 09:43:52.435  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 09:43:52.436  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 09:43:52.436  5442  5442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:43:54.934  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:43:54.934  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 09:43:54.935  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:43:54.935  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 09:43:54.935  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 09:43:54.935  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 09:43:54.936  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:43:54.936  5442  5777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 09:43:54.936  5442  5488 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 09:43:54.936  5442  5777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 09:43:54.936  5442  5777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 09:43:54.936  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:43:54.936  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:43:54.936  5442  5442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 09:43:54.937  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:43:54.937  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:43:54.937  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:43:54.939  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:54.940  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:43:54.940  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:54.940  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 09:43:54.942  5680  5698 D BtGatt.AdvertiseManager: message : 1
,09-23 09:43:54.944  5680  5698 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 09:43:54.958  5680  5696 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 09:43:54.958  5680  5696 D BtGatt.GattService: Client app is not null!
,09-23 09:43:54.961  5680  5691 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 09:43:54.962  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:54.962  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 09:43:54.963  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 09:43:54.963  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 09:43:54.963  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 09:43:54.965  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:43:54.965  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 09:43:54.965  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:54.967  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:43:54.970  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:43:54.970  5442  5442 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 09:43:54.970  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:54.970  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:54.970  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:43:54.970  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 09:43:54.971  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cedb0f8 removed from the list
09-23 09:43:54.971  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:54.971  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f019d1 removed from the list
09-23 09:43:54.971  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:43:54.971  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:54.971  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:43:54.971  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:43:54.983  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:43:54.983  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:43:54.989  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:43:54.991  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:43:54.991  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:43:54.991  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:54.992  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:54.995  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:54.996  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:54.997  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:54.997  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:43:54.997  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:54.998  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:54.998  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:43:54.998  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:54.998  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:43:54.998  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:43:54.998  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f019d1 not in the list
09-23 09:43:54.998  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:54.998  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:43:55.002  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:43:55.003  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:55.003  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:55.005  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:55.005  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:43:55.005  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:55.007  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:55.008  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:55.008  5442  5488 D BluetoothLeScanner: could not find callback wrapper
,09-23 09:43:55.008  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:55.008  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:55.008  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:55.008  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:55.008  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f019d1 not in the list
09-23 09:43:55.008  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:43:55.008  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:55.008  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:55.009  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cedb0f8 not in the list
09-23 09:43:55.010  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:43:55.010  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6293c0e added. We now have 3 listener(s)
,09-23 09:43:55.012  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:43:55.012  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:43:55.012  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:43:55.013  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:55.013  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af062f added. We now have 4 listener(s)
09-23 09:43:55.013  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:43:55.014  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:43:55.017  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:55.022  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:55.025  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:55.025  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:43:55.025  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:43:55.025  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:43:55.025  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-23 09:43:55.025  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:55.025  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:43:55.030  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:55.031  5442  5488 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:43:55.031  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:43:55.034  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:55.037  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:43:55.038  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:43:55.038  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:43:55.043  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:43:55.043  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:43:55.043  5442  5488 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:43:55.044  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:55.046  5680  5708 D BtGatt.GattService: registerClient() - UUID=464ebdb7-a4fe-4a4a-9016-3d5b206a376c
,09-23 09:43:55.047  5680  5696 D BtGatt.GattService: onClientRegistered() - UUID=464ebdb7-a4fe-4a4a-9016-3d5b206a376c, clientIf=5
,09-23 09:43:55.047  5442  5453 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 09:43:55.048  5680  5717 D BtGatt.GattService: start scan with filters
,09-23 09:43:55.051  5680  5699 D BtGatt.ScanManager: handling starting scan
09-23 09:43:55.052  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:43:55.052  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 09:43:55.052  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:43:55.052  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 09:43:55.057  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:43:55.058  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:43:55.058  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:43:55.060  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 09:43:55.062  5680  5696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:43:55.062  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:55.062  5680  5699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:43:55.069  5680  5696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 09:43:55.069  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:55.069  5680  5699 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:43:55.069  5680  5699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 09:43:55.081  5680  5696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 09:43:55.081  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:43:55.088  5680  5696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 09:43:55.088  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:43:55.506  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:43:55.559  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 09:43:55.560  5442  5442 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:43:55.560  5442  5442 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:43:58.071  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:43:58.072  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:43:58.072  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 09:43:58.072  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.072  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:43:58.072  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:43:58.073  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 09:43:58.073  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:43:58.073  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 09:43:58.073  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:43:58.073  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:43:58.077  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:58.080  5680  5690 D BtGatt.GattService: stopScan() - queue size =1
,09-23 09:43:58.081  5680  5691 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 09:43:58.082  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:58.083  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:43:58.083  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:43:58.083  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-23 09:43:58.083  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:43:58.085  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:43:58.085  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:58.085  5442  5488 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:43:58.085  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:58.087  5680  5680 D BtGatt.ScanManager: awakened up at time 328300
09-23 09:43:58.087  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:58.090  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:43:58.090  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.090  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:43:58.090  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:58.090  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:43:58.090  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6293c0e removed from the list
09-23 09:43:58.090  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:58.091  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af062f removed from the list
09-23 09:43:58.091  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:58.091  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:58.091  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:43:58.091  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:43:58.097  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:43:58.097  5442  5442 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:43:58.098  5680  5696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-23 09:43:58.098  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:58.098  5680  5699 D BtGatt.ScanManager: stopping BLe Batch
,09-23 09:43:58.104  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:43:58.107  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:43:58.107  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:43:58.108  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:58.108  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:58.109  5680  5696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:43:58.110  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:43:58.110  5680  5699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 09:43:58.112  5442  5442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:43:58.113  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:58.113  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:43:58.116  5442  5442 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:43:58.117  5442  5442 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:43:58.118  5442  5442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:58.123  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.123  5442  5442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:43:58.123  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:58.124  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:58.124  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:58.124  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:58.125  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:58.125  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:43:58.125  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:43:58.125  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:43:58.126  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af062f not in the list
09-23 09:43:58.126  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.126  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:58.127  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:58.128  5442  5488 D BluetoothAdapter: STATE_ON
09-23 09:43:58.128  5442  5488 D BluetoothLeScanner: could not find callback wrapper
09-23 09:43:58.128  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:43:58.128  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:58.128  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:43:58.128  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:58.128  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af062f not in the list
09-23 09:43:58.128  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:43:58.128  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:58.128  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:58.128  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6293c0e not in the list
09-23 09:43:58.129  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:43:58.129  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@480bed4 added. We now have 3 listener(s)
09-23 09:43:58.131  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:43:58.131  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:43:58.131  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:43:58.131  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:43:58.132  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee087d added. We now have 4 listener(s)
,09-23 09:43:58.132  5442  5488 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:43:58.132  5680  5696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-23 09:43:58.132  5680  5696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:43:58.132  5680  5696 D BtGatt.GattService: current time is 328346315214
09-23 09:43:58.133  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:43:58.134  5680  5696 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -75, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -74, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 09:43:58.136  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:43:58.136  5680  5696 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 09:43:58.138  5680  5696 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-23 09:43:58.138  5680  5696 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 09:43:58.138  5680  5696 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 09:43:58.139  5680  5696 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:43:58.141  5442  5488 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:43:58.144  5442  5488 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:43:58.144  5442  5488 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:43:58.144  5442  5488 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:43:58.145  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:43:58.145  5442  5488 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:43:58.145  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:43:58.145  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.145  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:43:58.145  5442  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 09:43:58.145  5442  5488 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@480bed4 removed from the list
09-23 09:43:58.145  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:58.145  5442  5488 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee087d removed from the list
,09-23 09:43:58.147  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:43:58.150  5442  5442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:43:58.151  5442  5488 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:43:58.151  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:58.151  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:43:58.151  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:58.164  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:43:58.164  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:58.164  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:58.164  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee087d not in the list
09-23 09:43:58.164  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.164  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:43:58.165  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:43:58.165  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:43:58.165  5442  5488 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:43:58.165  5442  5488 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee087d not in the list
09-23 09:43:58.166  5442  5488 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:43:58.166  5442  5488 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:43:58.166  5442  5488 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:43:58.166  5442  5488 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@480bed4 not in the list
,09-23 09:43:58.166  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-23 09:43:58.167  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 09:43:58.167  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 09:43:58.167  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:43:58.167  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 09:43:58.167  5442  5488 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:43:58.624  5442  5442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:43:59.117   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 09:43:59.117   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 09:44:00.174  5442  5780 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-23 09:44:02.174  5442  5488 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 187
,09-23 09:44:02.174  5442  5488 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 187, name: My test thread name)
09-23 09:44:02.179  5442  5781 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,09-23 09:44:02.179  5442  5781 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 188, thread name: My test thread name)
09-23 09:44:02.180  5442  5781 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-23 09:44:02.184  5442  5488 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:44:02.191  5442  5782 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,09-23 09:44:02.192  5442  5782 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 192, thread name: My test thread name): Test exception.
,09-23 09:44:02.192  5442  5782 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-23 09:44:02.201  5442  5488 I jxcore-log: Total number of executed tests:  82
09-23 09:44:02.201  5442  5488 I jxcore-log: 
09-23 09:44:02.201  5442  5488 I jxcore-log: Number of passed tests:  82
09-23 09:44:02.201  5442  5488 I jxcore-log: 
09-23 09:44:02.202  5442  5488 I jxcore-log: Number of failed tests:  0
09-23 09:44:02.202  5442  5488 I jxcore-log: 
09-23 09:44:02.202  5442  5488 I jxcore-log: Number of ignored tests:  0
09-23 09:44:02.202  5442  5488 I jxcore-log: 
09-23 09:44:02.202  5442  5488 I jxcore-log: Total duration:  101081
09-23 09:44:02.202  5442  5488 I jxcore-log: 
,09-23 09:44:02.208  5442  5488 I jxcore-log: Unit Test app is loaded
09-23 09:44:02.208  5442  5488 I jxcore-log: 
,09-23 09:44:02.222  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.222  5442  5488 I jxcore-log: 
,09-23 09:44:02.229  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.229  5442  5488 I jxcore-log: 
,09-23 09:44:02.230  5442  5442 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-23 09:44:02.231  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.231  5442  5488 I jxcore-log: 
,09-23 09:44:02.233  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.233  5442  5488 I jxcore-log: 
,09-23 09:44:02.234  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-23 09:44:02.234  5442  5488 I jxcore-log: 
09-23 09:44:02.236  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:44:02.236  5442  5488 I jxcore-log: 
09-23 09:44:02.239  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.239  5442  5488 I jxcore-log: 
,09-23 09:44:02.242  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.242  5442  5488 I jxcore-log: 
,09-23 09:44:02.243  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-23 09:44:02.243  5442  5488 I jxcore-log: 
,09-23 09:44:02.244  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:44:02.244  5442  5488 I jxcore-log: 
09-23 09:44:02.245  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:44:02.245  5442  5488 I jxcore-log: 
09-23 09:44:02.245  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.245  5442  5488 I jxcore-log: 
09-23 09:44:02.246  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.246  5442  5488 I jxcore-log: 
,09-23 09:44:02.248  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.248  5442  5488 I jxcore-log: 
,09-23 09:44:02.249  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.249  5442  5488 I jxcore-log: 
,09-23 09:44:02.251  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.251  5442  5488 I jxcore-log: 
,09-23 09:44:02.252  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.252  5442  5488 I jxcore-log: 
,09-23 09:44:02.253  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.253  5442  5488 I jxcore-log: 
,09-23 09:44:02.255  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.255  5442  5488 I jxcore-log: 
,09-23 09:44:02.256  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.256  5442  5488 I jxcore-log: 
,09-23 09:44:02.258  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.258  5442  5488 I jxcore-log: 
,09-23 09:44:02.258  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.258  5442  5488 I jxcore-log: 
09-23 09:44:02.259  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.259  5442  5488 I jxcore-log: 
,09-23 09:44:02.260  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.260  5442  5488 I jxcore-log: 
,09-23 09:44:02.261  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.261  5442  5488 I jxcore-log: 
09-23 09:44:02.262  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.262  5442  5488 I jxcore-log: 
09-23 09:44:02.263  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.263  5442  5488 I jxcore-log: 
,09-23 09:44:02.264  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.264  5442  5488 I jxcore-log: 
,09-23 09:44:02.265  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.265  5442  5488 I jxcore-log: 
,09-23 09:44:02.268  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.268  5442  5488 I jxcore-log: 
,09-23 09:44:02.270  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.270  5442  5488 I jxcore-log: 
,09-23 09:44:02.270  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.270  5442  5488 I jxcore-log: 
,09-23 09:44:02.271  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.271  5442  5488 I jxcore-log: 
,09-23 09:44:02.272  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.272  5442  5488 I jxcore-log: 
,09-23 09:44:02.272  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.272  5442  5488 I jxcore-log: 
09-23 09:44:02.273  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.273  5442  5488 I jxcore-log: 
,09-23 09:44:02.273  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.273  5442  5488 I jxcore-log: 
,09-23 09:44:02.274  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:44:02.274  5442  5488 I jxcore-log: 
,09-23 09:44:02.275  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.275  5442  5488 I jxcore-log: 
09-23 09:44:02.275  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-23 09:44:02.275  5442  5488 I jxcore-log: 
,09-23 09:44:02.276  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.276  5442  5488 I jxcore-log: 
,09-23 09:44:02.277  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.277  5442  5488 I jxcore-log: 
,09-23 09:44:02.277  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.277  5442  5488 I jxcore-log: 
,09-23 09:44:02.278  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.278  5442  5488 I jxcore-log: 
09-23 09:44:02.279  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.279  5442  5488 I jxcore-log: 
,09-23 09:44:02.280  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:44:02.280  5442  5488 I jxcore-log: 
,09-23 09:44:02.280  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.280  5442  5488 I jxcore-log: 
,09-23 09:44:02.281  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-23 09:44:02.281  5442  5488 I jxcore-log: 
,09-23 09:44:02.281  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.281  5442  5488 I jxcore-log: 
,09-23 09:44:02.282  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:44:02.282  5442  5488 I jxcore-log: 
,09-23 09:44:02.283  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-23 09:44:02.283  5442  5488 I jxcore-log: 
,09-23 09:44:02.283  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:44:02.283  5442  5488 I jxcore-log: 
,09-23 09:44:02.284  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:44:02.284  5442  5488 I jxcore-log: 
,09-23 09:44:02.287  5442  5488 I jxcore-log: My device name is: Huawei-Nexus 6P
09-23 09:44:02.287  5442  5488 I jxcore-log: 
,09-23 09:44:02.288  5442  5488 I jxcore-log: 2016-09-23 13:44:02 - WARN testUtils: 'myNameCallback not set!'
09-23 09:44:02.288  5442  5488 I jxcore-log: 
,09-23 09:44:02.288  5442  5488 I jxcore-log: Running for WIFI network type
09-23 09:44:02.288  5442  5488 I jxcore-log: 
,09-23 09:44:02.296  5442  5780 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-23 09:44:04.293  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-23 09:44:04.293  5442  5488 I jxcore-log: 
,09-23 09:44:04.470   928  5739 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334683, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 09:44:04.610  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-23 09:44:04.610  5442  5488 I jxcore-log: 
,09-23 09:44:04.624  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-23 09:44:04.624  5442  5488 I jxcore-log: 
,09-23 09:44:05.739  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-23 09:44:05.739  5442  5488 I jxcore-log: 
,09-23 09:44:05.886  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-23 09:44:05.886  5442  5488 I jxcore-log: 
,09-23 09:44:05.891  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-23 09:44:05.891  5442  5488 I jxcore-log: 
,09-23 09:44:05.895  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-23 09:44:05.895  5442  5488 I jxcore-log: 
,09-23 09:44:06.017  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-23 09:44:06.017  5442  5488 I jxcore-log: 
,09-23 09:44:06.030  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-23 09:44:06.030  5442  5488 I jxcore-log: 
,09-23 09:44:06.040  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-23 09:44:06.040  5442  5488 I jxcore-log: 
,09-23 09:44:06.542  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-23 09:44:06.542  5442  5488 I jxcore-log: 
,09-23 09:44:06.662  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-23 09:44:06.662  5442  5488 I jxcore-log: 
,09-23 09:44:06.870  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-23 09:44:06.870  5442  5488 I jxcore-log: 
,09-23 09:44:06.877  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-23 09:44:06.877  5442  5488 I jxcore-log: 
,09-23 09:44:06.883  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-23 09:44:06.883  5442  5488 I jxcore-log: 
,09-23 09:44:06.888  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-23 09:44:06.888  5442  5488 I jxcore-log: 
,09-23 09:44:06.916  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-23 09:44:06.916  5442  5488 I jxcore-log: 
,09-23 09:44:06.951  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-23 09:44:06.951  5442  5488 I jxcore-log: 
,09-23 09:44:06.958  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-23 09:44:06.958  5442  5488 I jxcore-log: 
,09-23 09:44:06.964  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-23 09:44:06.964  5442  5488 I jxcore-log: 
,09-23 09:44:06.979  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-23 09:44:06.979  5442  5488 I jxcore-log: 
,09-23 09:44:06.983  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-23 09:44:06.983  5442  5488 I jxcore-log: 
,09-23 09:44:06.988  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-23 09:44:06.988  5442  5488 I jxcore-log: 
,09-23 09:44:07.000  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-23 09:44:07.000  5442  5488 I jxcore-log: 
,09-23 09:44:07.020  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-23 09:44:07.020  5442  5488 I jxcore-log: 
,09-23 09:44:07.029  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-23 09:44:07.029  5442  5488 I jxcore-log: 
,09-23 09:44:07.040  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-23 09:44:07.040  5442  5488 I jxcore-log: 
,09-23 09:44:07.048  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-23 09:44:07.048  5442  5488 I jxcore-log: 
,09-23 09:44:07.060  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-23 09:44:07.060  5442  5488 I jxcore-log: 
,09-23 09:44:07.070  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-23 09:44:07.070  5442  5488 I jxcore-log: 
,09-23 09:44:07.074  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-23 09:44:07.074  5442  5488 I jxcore-log: 
,09-23 09:44:07.093  5442  5488 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-23 09:44:07.093  5442  5488 I jxcore-log: 
,09-23 09:44:07.103  5442  5488 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-23 09:44:07.104  5442  5488 I jxcore-log: 2016-09-23 13:44:07 - INFO testUtils: 'BLE multiple advertisement supported'
09-23 09:44:07.104  5442  5488 I jxcore-log: 
,09-23 09:44:07.109  5442  5488 I jxcore-log: [TypeError: testRunner.run is not a function]
09-23 09:44:07.109  5442  5488 I jxcore-log: 
,09-23 09:44:07.358  5442  5488 I jxcore-log: 2016-09-23 13:44:07 - DEBUG CoordinatedClient: 'connected to the test server'
09-23 09:44:07.358  5442  5488 I jxcore-log: 
,09-23 09:44:12.183   928  5739 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 09:44:14.118   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:15.119   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:16.120   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:16.611   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:44:17.121   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:18.123   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:19.124   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 09:44:24.125   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:25.126   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:26.127   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:27.129   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:28.130   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:29.131   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-23 09:44:39.132   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:40.133   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:41.134   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:42.136   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:43.137   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:44:44.137   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-23 09:44:56.616   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:44:59.139   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:00.139   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:01.140   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:02.141   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:03.142   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:04.143   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 09:45:16.618   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:45:24.145   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:25.146   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:26.147   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:27.148   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:28.150   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:45:29.151   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 09:45:54.152   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 09:45:54.152   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 09:45:56.620   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:46:14.153   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:15.155   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:16.156   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:16.625   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:46:17.157   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:18.158   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:19.159   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 09:46:24.160   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:25.162   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:26.163   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:27.165   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:28.166   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:29.167   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-23 09:46:36.627   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:46:39.169   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:40.171   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:41.172   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:42.174   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:43.175   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:46:44.176   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-23 09:46:59.178   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:00.179   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:01.180   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:02.181   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:03.183   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:04.184   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 09:47:09.235  5442  5488 I jxcore-log: 2016-09-23 13:47:09 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-23 09:47:09.235  5442  5488 I jxcore-log: 
,09-23 09:47:16.632   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:47:24.185   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:25.187   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:26.188   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:47:27.190   535   535 I ServiceManager: Waiting for service AtCmdFwd...

```
