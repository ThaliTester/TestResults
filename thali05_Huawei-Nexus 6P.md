#### Test 8728295445538d6_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-29 06:30:11.064   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-29 06:30:11.064   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 06:30:13.120  5675  5675 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-29 06:30:13.125  5675  5675 D AndroidRuntime: CheckJNI is OFF
09-29 06:30:13.159  5675  5675 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-29 06:30:13.205  5675  5675 I Radio-JNI: register_android_hardware_Radio DONE
09-29 06:30:13.221  5675  5675 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-29 06:30:13.239   928  4102 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-29 06:30:13.295   928  4102 I ActivityManager: Start proc 5684:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-29 06:30:13.323  5675  5675 D AndroidRuntime: Shutting down VM
,09-29 06:30:13.643   928  3624 I WindowManager: Screenshot max retries 4 of Token{55b360d ActivityRecord{976e8a4 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{baca83c u0 Starting com.test.thalitest} drawState=2
,09-29 06:30:13.711  5684  5684 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-29 06:30:13.746  5684  5684 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-29 06:30:13.772  5684  5684 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 905-923)
,09-29 06:30:13.772  5684  5684 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-29 06:30:13.792  5684  5684 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33d7683}
,09-29 06:30:13.793  5684  5684 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-29 06:30:13.793  5684  5684 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-29 06:30:13.797  5684  5684 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-29 06:30:13.798  5684  5684 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-29 06:30:13.818   928  3027 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 06:30:13.841  5684  5684 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-29 06:30:13.849  5684  5684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-29 06:30:13.849  5684  5684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-29 06:30:13.849  5684  5684 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-29 06:30:13.849  5684  5684 I Adreno  : Build Date                       : 12/06/15
09-29 06:30:13.849  5684  5684 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-29 06:30:13.849  5684  5684 I Adreno  : Local Branch                     : mybranch17112971
09-29 06:30:13.849  5684  5684 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-29 06:30:13.849  5684  5684 I Adreno  : Remote Branch                    : NONE
09-29 06:30:13.849  5684  5684 I Adreno  : Reconstruct Branch               : NOTHING
,09-29 06:30:13.914   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18897c3:true
,09-29 06:30:13.944   401   401 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16086]" dev="sockfs" ino=16086 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 06:30:13.944   401   401 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[16086]" dev="sockfs" ino=16086 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 06:30:13.957  5684  5684 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-29 06:30:13.969  5684  5684 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-29 06:30:14.001  5684  5721 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-29 06:30:13.997   401   401 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32081]" dev="sockfs" ino=32081 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-29 06:30:13.997   401   401 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32081]" dev="sockfs" ino=32081 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-29 06:30:14.000   938   938 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16098]" dev="sockfs" ino=16098 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-29 06:30:14.000   938   938 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16098]" dev="sockfs" ino=16098 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 06:30:14.010  5684  5708 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-29 06:30:14.037  5684  5721 I OpenGLRenderer: Initialized EGL, version 1.4
,09-29 06:30:14.112   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +465ms (total +842ms)
,09-29 06:30:14.161  5684  5684 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5684
,09-29 06:30:14.265  5684  5684 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-29 06:30:14.526  5684  5723 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -588515024
,09-29 06:30:14.549  5684  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-29 06:30:14.549  5684  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-29 06:30:14.549  5684  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-29 06:30:14.549  5684  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-29 06:30:14.549  5684  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-29 06:30:14.550  5684  5723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8fe3d8 added. We now have 1 listener(s)
,09-29 06:30:14.559  5684  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-29 06:30:14.561  5684  5723 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:30:14.562  5684  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:30:14.563  5684  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-29 06:30:14.572  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-29 06:30:14.573  5684  5723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98adf97 added. We now have 1 listener(s)
09-29 06:30:14.573  5684  5723 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:30:14.581   928  3028 D WifiService: New client listening to asynchronous messages
,09-29 06:30:14.583  5684  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 06:30:14.583  5684  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-29 06:30:14.583  5684  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-29 06:30:14.584  5684  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-29 06:30:14.584  5684  5723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-29 06:30:14.590  5684  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:30:14.590  5684  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-29 06:30:14.599  5684  5723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:14.599  5684  5723 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:30:14.599  5684  5723 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-29 06:30:14.600  5684  5723 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:30:14.601  5684  5723 I io.jxcore.node.LifeCycleMonitor: start: OK
09-29 06:30:14.603  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:14.609  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:14.632  5684  5684 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-29 06:30:15.385  5684  5684 I Choreographer: Skipped 43 frames!  The application may be doing too much work on its main thread.
,09-29 06:30:15.754  5684  5693 I art     : Background sticky concurrent mark sweep GC freed 77138(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.130ms total 240.445ms
,09-29 06:30:15.936  5684  5730 W jxcore-log: Initializing JXcore engine
09-29 06:30:15.936  5684  5730 W jxcore-log: JXcore engine is ready
,09-29 06:30:15.984  5730  5730 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12665 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-29 06:30:15.984  5730  5730 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[17477]" dev="sockfs" ino=17477 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-29 06:30:15.984  5730  5730 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-29 06:30:15.984  5730  5730 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31551]" dev="sockfs" ino=31551 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-29 06:30:15.995  5684  5730 W jxcore-log: Starting JXcore engine
,09-29 06:30:16.050  5684  5730 W jxcore-log: Platform android
09-29 06:30:16.050  5684  5730 W jxcore-log: 
09-29 06:30:16.050  5684  5730 W jxcore-log: Process ARCH arm
09-29 06:30:16.050  5684  5730 W jxcore-log: 
,09-29 06:30:16.146  5684  5730 I jxcore-log: JXcore Cordova bridge is ready!
09-29 06:30:16.146  5684  5730 I jxcore-log: 
09-29 06:30:16.146  5684  5730 W jxcore-log: JXcore engine is started
,09-29 06:30:16.158  5684  5723 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-29 06:30:16.163  5684  5684 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-29 06:30:21.066   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:22.067   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:23.069   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:24.071   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:25.072   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:25.544  5684  5730 I jxcore-log: 2016-09-29 10:30:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 06:30:25.544  5684  5730 I jxcore-log: 
,09-29 06:30:25.546  5684  5730 I jxcore-log: 2016-09-29 10:30:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 06:30:25.546  5684  5730 I jxcore-log: 
,09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:25.550  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:30:25.551  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:30:25.553  5684  5730 I jxcore-log: 2016-09-29 10:30:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 06:30:25.553  5684  5730 I jxcore-log: 
,09-29 06:30:25.554  5684  5730 I jxcore-log: 2016-09-29 10:30:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 06:30:25.554  5684  5730 I jxcore-log: 
,09-29 06:30:25.794  5684  5730 I jxcore-log: 2016-09-29 10:30:25 - DEBUG UnitTest_app: 'Running unit tests'
09-29 06:30:25.794  5684  5730 I jxcore-log: 
09-29 06:30:25.795  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 06:30:25.795  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dc78f5 added. We now have 2 listener(s)
,09-29 06:30:25.796  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 06:30:25.796  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:30:25.796  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:30:25.796  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 06:30:25.796  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e38568a added. We now have 2 listener(s)
09-29 06:30:25.796  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:30:25.797  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 06:30:25.799  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:25.802  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:30:25.803  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:25.803  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:30:25.804  5684  5730 D executeNativeTests: Running unit tests
,09-29 06:30:25.810  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:25.816  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:25.842  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 06:30:25.842  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 added. We now have 3 listener(s)
,09-29 06:30:25.843  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:30:25.843  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 06:30:25.843  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 06:30:25.843  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 06:30:25.843  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 added. We now have 3 listener(s)
09-29 06:30:25.843  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:30:25.843  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:30:25.845  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:25.848  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:30:25.849  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:30:25.849  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:30:25.850  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 06:30:25.850  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:25.850  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:25.850  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:25.851  5684  5730 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-29 06:30:25.851  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 06:30:25.851  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-29 06:30:25.851  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-29 06:30:25.851  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-29 06:30:25.851  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-29 06:30:25.851  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:25.852  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:25.852  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:25.852  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 06:30:25.852  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:25.852  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:25.852  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:25.852  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:30:25.852  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 removed from the list
09-29 06:30:25.853  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:25.853  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 removed from the list
09-29 06:30:25.853  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:25.859  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:25.860  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:25.860  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.861  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:25.861  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:25.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:25.861  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:25.861  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:25.862  5684  5730 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-29 06:30:25.863  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:25.863  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:25.863  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:25.863  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:25.863  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:25.863  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.863  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:25.863  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:25.863  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:25.863  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:25.863  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:30:25.863  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:25.863  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.863  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:25.863  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.864  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:25.864  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:25.864  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:25.864  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 06:30:25.866  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 06:30:25.867  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:25.867  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:25.867  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:25.867  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:25.867  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:25.867  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.867  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:25.867  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:25.867  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:25.867  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:25.867  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:25.867  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:25.867  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.867  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:25.867  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:25.868  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:25.868  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:25.868  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:25.868  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:25.868  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-29 06:30:25.869  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:25.871  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:30:25.872  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:25.872  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:30:25.872  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:30:25.872  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 06:30:25.872  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 06:30:25.872  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:25.872  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 06:30:25.880  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:25.884  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:25.885  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 06:30:25.885  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 06:30:25.888  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 06:30:25.888  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 06:30:25.888  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 06:30:25.890  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-29 06:30:25.891  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-29 06:30:25.891  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 06:30:25.891  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 06:30:25.891  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 06:30:25.891  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 06:30:25.892  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 06:30:25.892  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:30:25.894  4651  4667 D BtGatt.GattService: registerClient() - UUID=f6b78c20-13ff-4358-8097-1e9c50ce0c9f
09-29 06:30:25.895  4651  4723 D BtGatt.GattService: onClientRegistered() - UUID=f6b78c20-13ff-4358-8097-1e9c50ce0c9f, clientIf=5
,09-29 06:30:25.896  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 06:30:25.897  4651  4890 D BtGatt.GattService: start scan with filters
09-29 06:30:25.902  4651  4729 D BtGatt.ScanManager: handling starting scan
09-29 06:30:25.903  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 06:30:25.903  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 06:30:25.903  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:30:25.903  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 06:30:25.904  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 06:30:25.904  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 06:30:25.904  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 06:30:25.906  4651  4729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:30:25.907  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:30:25.907  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 06:30:25.907  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:30:25.907  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 06:30:25.908  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
09-29 06:30:25.915  4651  4723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 06:30:25.915  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:25.916  4651  4729 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 06:30:25.922  4651  4723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 06:30:25.922  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:25.923  4651  4729 D BtGatt.ScanManager: Starting BLE batch scan
09-29 06:30:25.923  4651  4729 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 06:30:25.934  4651  4723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 06:30:25.934  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:25.941  4651  4723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 06:30:25.941  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:26.075   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 06:30:26.409  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-29 06:30:26.410  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:30:26.410  5684  5684 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 06:30:30.918  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 06:30:30.918  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-29 06:30:30.918  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 06:30:30.918  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:30.919  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 06:30:30.919  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:30.919  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 06:30:30.919  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 06:30:30.919  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:30:30.920  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:30:30.921  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 06:30:30.921  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 06:30:30.923  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:30:30.924  4651  4890 D BtGatt.GattService: stopScan() - queue size =1
,09-29 06:30:30.927  4651  4669 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 06:30:30.928  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 06:30:30.929  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-29 06:30:30.929  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 06:30:30.929  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-29 06:30:30.930  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-29 06:30:30.930  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 06:30:30.930  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 06:30:30.930  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 06:30:30.933  4651  4651 D BtGatt.ScanManager: awakened up at time 238084
09-29 06:30:30.934  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:30.935  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 06:30:30.936  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-29 06:30:30.936  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 06:30:30.937  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 06:30:30.939  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:30.941  4651  4723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 06:30:30.941  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:30.941  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:30.941  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:30.941  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:30.941  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 06:30:30.941  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:30.941  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:30.941  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:30.942  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:30.942  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:30.942  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:30.942  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:30.942  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:30.942  4651  4729 D BtGatt.ScanManager: stopping BLe Batch
09-29 06:30:30.954  4651  4723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 06:30:30.954  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:30.955  4651  4729 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 06:30:30.980  4651  4723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-29 06:30:30.980  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:30.980  4651  4723 D BtGatt.GattService: current time is 238131787946
09-29 06:30:30.981  4651  4723 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -78, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -78, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -80, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,09-29 06:30:30.984  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-29 06:30:30.986  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-29 06:30:30.986  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-29 06:30:30.986  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 06:30:30.987  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-29 06:30:30.987  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-29 06:30:31.076   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:31.446  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 06:30:32.081   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:33.086   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:34.090   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:35.091   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:35.944  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-29 06:30:35.955  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:35.968  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:30:35.975  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:35.976  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:30:35.976  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:30:35.976  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 06:30:35.976  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 06:30:35.976  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:35.976  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 06:30:35.984  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:35.987  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 06:30:35.988  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 06:30:35.990  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:35.994  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 06:30:35.994  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 06:30:35.995  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 06:30:36.003  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 06:30:36.003  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 06:30:36.003  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-29 06:30:36.003  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 06:30:36.003  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 06:30:36.004  5684  5730 D BluetoothAdapter: STATE_ON
,09-29 06:30:36.009  4651  5399 D BtGatt.GattService: registerClient() - UUID=49c16244-65d4-4691-a005-bab3acef4fa3
,09-29 06:30:36.010  4651  4723 D BtGatt.GattService: onClientRegistered() - UUID=49c16244-65d4-4691-a005-bab3acef4fa3, clientIf=5
09-29 06:30:36.011  5684  5695 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 06:30:36.011  4651  4891 D BtGatt.GattService: start scan with filters
,09-29 06:30:36.016  4651  4729 D BtGatt.ScanManager: handling starting scan
09-29 06:30:36.018  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 06:30:36.018  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 06:30:36.018  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-29 06:30:36.018  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-29 06:30:36.018  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 06:30:36.018  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 06:30:36.018  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 06:30:36.022  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:30:36.022  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 06:30:36.023  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:30:36.024  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 06:30:36.026  4651  4723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 06:30:36.026  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.027  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
09-29 06:30:36.027  4651  4729 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 06:30:36.031  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:36.031  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-29 06:30:36.031  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:36.031  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 06:30:36.031  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:36.031  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 06:30:36.031  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:36.031  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 06:30:36.031  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 06:30:36.031  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:30:36.031  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:30:36.032  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 06:30:36.032  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 06:30:36.032  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:30:36.033  4651  4891 D BtGatt.GattService: stopScan() - queue size =1
09-29 06:30:36.033  4651  4723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 06:30:36.034  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:36.034  4651  4893 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 06:30:36.034  4651  4729 D BtGatt.ScanManager: Starting BLE batch scan
09-29 06:30:36.034  4651  4729 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 06:30:36.034  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 06:30:36.034  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 06:30:36.034  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 06:30:36.034  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-29 06:30:36.034  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 06:30:36.034  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 06:30:36.034  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 06:30:36.034  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-29 06:30:36.036  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:36.037  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 06:30:36.037  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-29 06:30:36.037  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 06:30:36.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 06:30:36.038  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:36.039  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:36.039  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:36.039  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:36.039  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:36.039  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:36.039  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:36.039  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:36.039  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:36.039  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:36.040  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:36.040  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:36.040  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:36.042  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:36.042  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:36.043  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:36.043  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 06:30:36.043  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:36.043  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:36.044  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-29 06:30:36.046  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:36.047  4651  4723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 06:30:36.048  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:36.051  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:30:36.053  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:36.053  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:30:36.053  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:30:36.053  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 06:30:36.053  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 06:30:36.053  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:36.053  4651  4723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 06:30:36.053  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 06:30:36.053  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.057  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:36.059  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 06:30:36.059  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 06:30:36.061  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:36.061  4651  4723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 06:30:36.061  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:36.061  4651  4729 D BtGatt.ScanManager: stopping BLe Batch
,09-29 06:30:36.063  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 06:30:36.064  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 06:30:36.064  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 06:30:36.067  4651  4723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 06:30:36.067  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:36.067  4651  4729 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 06:30:36.067  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 06:30:36.067  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 06:30:36.067  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 06:30:36.067  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 06:30:36.067  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 06:30:36.068  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:30:36.071  4651  4667 D BtGatt.GattService: registerClient() - UUID=b525922e-b0a7-4033-84ba-7961242dd277
09-29 06:30:36.071  4651  4723 D BtGatt.GattService: onClientRegistered() - UUID=b525922e-b0a7-4033-84ba-7961242dd277, clientIf=5
,09-29 06:30:36.071  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 06:30:36.072  4651  4723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 06:30:36.072  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.072  4651  4890 D BtGatt.GattService: start scan with filters
,09-29 06:30:36.074  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 06:30:36.074  4651  4729 D BtGatt.ScanManager: handling starting scan
09-29 06:30:36.074  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-29 06:30:36.075  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:30:36.075  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 06:30:36.075  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 06:30:36.075  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 06:30:36.075  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 06:30:36.077  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:30:36.078  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 06:30:36.078  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:30:36.079  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 06:30:36.080  4651  4723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 06:30:36.080  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:36.080  4651  4729 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 06:30:36.081  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
,09-29 06:30:36.085  4651  4723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 06:30:36.085  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.086  4651  4729 D BtGatt.ScanManager: Starting BLE batch scan
09-29 06:30:36.086  4651  4729 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 06:30:36.092   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 06:30:36.095  4651  4723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 06:30:36.095  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.100  4651  4723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 06:30:36.100  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:36.581  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-29 06:30:36.582  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 06:30:36.582  5684  5684 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 06:30:37.173   928  3029 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 06:30:40.207   928  3029 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 06:30:41.084  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 06:30:41.084  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:41.084  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 06:30:41.085  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:41.085  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 06:30:41.085  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:41.085  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 06:30:41.085  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 06:30:41.086  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:30:41.086  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:30:41.086  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-29 06:30:41.086  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 06:30:41.090  5684  5730 D BluetoothAdapter: STATE_ON
,09-29 06:30:41.093  4651  5400 D BtGatt.GattService: stopScan() - queue size =1
,09-29 06:30:41.095  4651  4667 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 06:30:41.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 06:30:41.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 06:30:41.097  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 06:30:41.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:30:41.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 06:30:41.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-29 06:30:41.098  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 06:30:41.098  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 06:30:41.102  4651  4651 D BtGatt.ScanManager: awakened up at time 248252
09-29 06:30:41.104  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:41.105  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 06:30:41.105  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 06:30:41.105  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 06:30:41.105  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 06:30:41.106  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:41.108  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:41.108  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:41.108  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:41.109  4651  4723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 06:30:41.109  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:41.110  4651  4729 D BtGatt.ScanManager: stopping BLe Batch
,09-29 06:30:41.121  4651  4723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 06:30:41.121  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:30:41.122  4651  4729 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 06:30:41.149  4651  4723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-29 06:30:41.150  4651  4723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:30:41.150  4651  4723 D BtGatt.GattService: current time is 248301178892
09-29 06:30:41.150  4651  4723 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -90, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -74, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -84, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-29 06:30:41.150  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-29 06:30:41.151  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-29 06:30:41.151  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-29 06:30:41.151  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 06:30:41.151  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-29 06:30:41.151  4651  4723 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-29 06:30:41.612  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 06:30:41.613  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:41.613  5684  5684 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 06:30:46.096   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:46.110  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 06:30:46.110  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.110  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.111  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 06:30:46.111  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.111  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:30:46.111  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:46.111  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.112  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.112  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.112  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.112  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:46.114  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.114  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.118  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 06:30:46.119  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.119  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.120  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
,09-29 06:30:46.123  5684  5730 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-29 06:30:46.125  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 06:30:46.125  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 06:30:46.125  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 06:30:46.126  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.126  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.126  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.126  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:46.126  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.127  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.127  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.127  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:30:46.127  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.127  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.127  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:46.127  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.133  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.134  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.134  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.134  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
,09-29 06:30:46.139  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-29 06:30:46.140  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.142  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.142  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.142  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.143  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:46.143  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.143  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.143  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.143  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.143  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.143  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:30:46.143  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.143  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.143  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.143  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.145  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.146  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.146  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:46.146  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.147  5684  5730 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-29 06:30:46.147  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.147  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.147  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.147  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.148  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:46.148  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.148  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.148  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.148  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.148  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.148  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.148  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.148  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.148  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.148  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:46.150  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.150  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.150  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.150  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.151  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-29 06:30:46.152  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.152  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.152  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.152  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.152  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.152  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.152  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.153  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.153  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.153  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.153  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.153  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.153  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.153  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.153  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.156  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.156  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 06:30:46.156  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.156  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.157  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 06:30:46.158  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:46.158  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:46.158  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 06:30:46.158  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 06:30:46.158  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 06:30:46.158  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 06:30:46.158  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:46.158  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 06:30:46.159  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.159  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.159  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.159  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.159  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.159  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.159  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.159  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.159  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:46.160  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.160  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:30:46.160  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.160  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.160  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.160  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.163  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.163  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 06:30:46.163  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.163  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.164  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 06:30:46.165  5684  5730 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 06:30:46.165  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 06:30:46.168  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 06:30:46.168  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 06:30:46.168  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 06:30:46.169  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 06:30:46.170  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 06:30:46.170  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 06:30:46.170  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 06:30:46.170  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 06:30:46.170  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-29 06:30:46.170  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 06:30:46.170  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-29 06:30:46.170  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 06:30:46.170  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 06:30:46.171  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-29 06:30:46.171  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 06:30:46.171  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 06:30:46.171  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-29 06:30:46.174  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-29 06:30:46.177  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-29 06:30:46.177  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-29 06:30:46.178  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-29 06:30:46.178  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-29 06:30:46.178  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-29 06:30:46.178  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 06:30:46.178  5684  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-29 06:30:46.178  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-29 06:30:46.178  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-29 06:30:46.178  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-29 06:30:46.178  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-29 06:30:46.179  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.179  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 06:30:46.180  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.180  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.180  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.180  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.180  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.180  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-29 06:30:46.182  5684  5732 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,09-29 06:30:46.182  5684  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:30:46.182  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.182  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.182  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.182  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.182  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:46.183  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:46.183  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:46.183  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.180  4893  4893 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32115]" dev="sockfs" ino=32115 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 06:30:46.180  4893  4893 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32115]" dev="sockfs" ino=32115 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 06:30:46.184  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.184  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.184  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.184  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.184  5684  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-29 06:30:46.184  5684  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
,09-29 06:30:46.184  5684  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-29 06:30:46.185  5684  5730 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-29 06:30:46.185  5684  5732 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-29 06:30:46.185  5684  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-29 06:30:46.185  5684  5732 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-29 06:30:46.185  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.186  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 06:30:46.186  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.186  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.186  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.186  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.186  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.186  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.186  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.186  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.186  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.187  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.187  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.187  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.187  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.191  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.191  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.191  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:46.192  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.192  5684  5730 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-29 06:30:46.192  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.193  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.193  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.193  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.193  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.193  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.193  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:46.193  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.193  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.193  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.193  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.193  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.193  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.193  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.193  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.194  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 06:30:46.194  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.194  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.194  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.195  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-29 06:30:46.195  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-29 06:30:46.195  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 06:30:46.196  5684  5730 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-29 06:30:46.196  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-29 06:30:46.196  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-29 06:30:46.196  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 06:30:46.196  5684  5730 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-29 06:30:46.196  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 06:30:46.196  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 06:30:46.196  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 06:30:46.196  5684  5730 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-29 06:30:46.196  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:46.196  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:46.196  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:46.196  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.196  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.196  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.196  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.197  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.197  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.197  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.197  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.197  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:46.197  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.197  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.197  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.198  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:46.198  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:46.198  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.198  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.199  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:46.199  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.199  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:46.199  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:46.199  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:46.199  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:46.199  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:46.199  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:46.199  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:46.199  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:47.099   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:48.103   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:49.107   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:50.110   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:30:51.112   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 06:30:51.201  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:51.201  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
,09-29 06:30:51.201  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:51.201  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.202  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:51.202  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:51.202  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.202  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:51.203  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:51.203  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:51.203  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 06:30:51.203  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:30:51.203  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:51.203  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:51.204  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.204  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.204  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.204  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:30:51.204  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.205  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.205  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.205  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.209  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:51.209  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:51.209  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.210  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
,09-29 06:30:51.215  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 06:30:51.217  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:30:51.223  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-29 06:30:51.226  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 06:30:51.226  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,09-29 06:30:51.227  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 06:30:51.227  5684  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-29 06:30:51.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-29 06:30:51.227  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 06:30:51.228  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 06:30:51.228  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:51.229  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 06:30:51.229  5684  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:30:51.230  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-29 06:30:51.230  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 06:30:51.230  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.230  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-29 06:30:51.230  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 06:30:51.231  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.231  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 06:30:51.231  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.231  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-29 06:30:51.231  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:30:51.231  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:30:51.232  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.232  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.230  4893  4893 W Binder_5: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30684]" dev="sockfs" ino=30684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 06:30:51.230  4893  4893 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30684]" dev="sockfs" ino=30684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 06:30:51.236  5684  5734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 06:30:51.237  5684  5734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 06:30:51.237  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:51.237  5684  5734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-29 06:30:51.237  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.237  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:51.237  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:51.237  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:30:51.238  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:30:51.238  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 06:30:51.238  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:51.238  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:51.238  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.238  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.238  5684  5684 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 06:30:51.238  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-29 06:30:51.238  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.239  5684  5684 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:51.239  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.239  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.239  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:51.239  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.239  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.239  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.243  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:51.243  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:51.243  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.243  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
,09-29 06:30:51.247  5684  5730 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-29 06:30:51.248  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-29 06:30:51.248  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 06:30:51.248  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 06:30:51.249  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 06:30:51.249  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:51.249  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:51.249  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:51.249  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:51.249  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.250  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.250  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 06:30:51.250  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.251  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.251  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
,09-29 06:30:51.252  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:51.252  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.254  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.254  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.254  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.259  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:51.259  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:51.260  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.260  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.266  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:51.267  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:51.267  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:51.267  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:51.267  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.267  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:51.267  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:51.267  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.267  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.267  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.267  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:51.267  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.267  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.267  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.267  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.269  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 06:30:51.269  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:51.269  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.269  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.270  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:30:51.271  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:30:51.271  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:30:51.271  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:30:51.271  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.271  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.271  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:30:51.271  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b27848 not in the list
09-29 06:30:51.271  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:51.271  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.271  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:51.271  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.271  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.271  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:51.271  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:51.274  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:30:51.274  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:30:51.274  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:30:51.274  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45356e1 not in the list
09-29 06:30:51.275  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-29 06:30:51.275  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 06:30:51.275  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-29 06:30:51.275  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 06:30:51.275  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-29 06:30:51.276  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 06:30:51.277  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-29 06:30:51.277  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-29 06:30:51.278  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-29 06:30:51.279  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 06:30:51.279  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-29 06:30:51.279  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 06:30:51.279  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-29 06:30:51.279  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-29 06:30:51.280  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-29 06:30:51.280  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-29 06:30:51.281  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-29 06:30:51.281  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-29 06:30:51.281  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-29 06:30:51.281  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-29 06:30:51.282  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:30:51.282  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c8aacdb added. We now have 3 listener(s)
09-29 06:30:51.283  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:30:51.286  5684  5730 D BluetoothAdapter: enable(): BT is already enabled..!
09-29 06:30:51.287   928  3204 D WifiService: setWifiEnabled: true pid=5684, uid=10077
09-29 06:30:51.287   928  3204 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 06:30:51.312  4651  4866 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-29 06:30:51.313  4651  4871 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-29 06:30:51.743  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 06:30:53.830   928  3027 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 06:30:56.294  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 06:30:56.295  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4188378 added. We now have 4 listener(s)
09-29 06:30:56.295  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:30:56.311  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:56.311  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4188378 removed from the list
09-29 06:30:56.311  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:56.311  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:56.312  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:30:56.315  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:30:56.316  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4eba51 added. We now have 4 listener(s)
09-29 06:30:56.316  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:30:56.320  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:30:56.320  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4eba51 removed from the list
09-29 06:30:56.320  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:30:56.320  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:30:56.320  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:30:56.321  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 06:30:56.322  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f032b6 added. We now have 4 listener(s)
09-29 06:30:56.322  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:30:56.328   928  3900 D WifiService: setWifiEnabled: false pid=5684, uid=10077
09-29 06:30:56.329   928  3900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 06:30:56.337   928  3027 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-29 06:30:56.337   928  3027 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-29 06:30:56.338   928  3027 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 06:30:56.338   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:30:56.344  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:30:56.345  4651  4719 D BluetoothAdapterState: Current state: ON, message: 23
09-29 06:30:56.345  4651  4719 D BluetoothAdapterProperties: Setting state to 13
,09-29 06:30:56.345  4651  4719 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-29 06:30:56.346  4651  4719 D BluetoothAdapterProperties: onBluetoothDisable()
09-29 06:30:56.348  4651  4719 I BluetoothAdapterState: Entering PendingCommandState
09-29 06:30:56.351  4651  4723 D BluetoothAdapterProperties: Scan Mode:20
09-29 06:30:56.351  4651  4719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 06:30:56.353  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:56.353  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:30:56.354  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.354  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:56.354  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:30:56.357  4651  4651 D HeadsetService: Received stop request...Stopping profile...
,09-29 06:30:56.363  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:56.364   928  5423 D DhcpClient: Clearing IP address
09-29 06:30:56.365   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-29 06:30:56.365  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:56.369  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:56.369  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:30:56.370  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.370  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:56.372   510   927 D CommandListener: Setting iface cfg
09-29 06:30:56.374   928   941 I ActivityManager: Start proc 5738:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-29 06:30:56.376   928  5424 D DhcpClient: Receive thread stopped
09-29 06:30:56.376  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:56.376  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:30:56.377  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.378  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:30:56.380   928   928 D BluetoothHeadset: Proxy object disconnected
,09-29 06:30:56.380   928   928 D BluetoothHeadset: Proxy object disconnected
,09-29 06:30:56.380   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 06:30:56.380  4651  4651 D BluetoothMapService: onReceive
09-29 06:30:56.380  3863  3898 D BluetoothHeadset: Proxy object disconnected
09-29 06:30:56.380  3183  3195 D BluetoothHeadset: Proxy object disconnected
,09-29 06:30:56.381  3183  3183 D HeadsetProfile: Bluetooth service disconnected
,09-29 06:30:56.381  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.382  4651  4651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 06:30:56.382  3630  5480 V NativeCrypto: Read error: ssl=0x7f782e6a00: I/O error during system call, Connection timed out
09-29 06:30:56.382  4651  4651 D BluetoothMapService: STATE_TURNING_OFF
09-29 06:30:56.383  4651  4651 D A2dpService: Received stop request...Stopping profile...
09-29 06:30:56.383  4651  4875 D A2dpStateMachine: Exit Disconnected: -1
09-29 06:30:56.385  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.386   928   928 D BluetoothA2dp: Proxy object disconnected
09-29 06:30:56.386  3183  3183 D BluetoothA2dp: Proxy object disconnected
09-29 06:30:56.386  4651  4651 V BluetoothAdapterState: isTurningOff()=true
09-29 06:30:56.386  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.386  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:30:56.386  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:30:56.387  4651  4651 D HidService: Received stop request...Stopping profile...
09-29 06:30:56.387  3630  5480 V NativeCrypto: SSL shutdown failed: ssl=0x7f782e6a00: I/O error during system call, Broken pipe
09-29 06:30:56.388  4651  4651 D HidService: Stopping Bluetooth HidService
09-29 06:30:56.389  3183  3183 D BluetoothInputDevice: Proxy object disconnected
09-29 06:30:56.389  3183  3183 D HidProfile: Bluetooth service disconnected
09-29 06:30:56.390   928  3914 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-29 06:30:56.391   928  5421 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-29 06:30:56.393  4651  4651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 06:30:56.393  4651  4651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 06:30:56.393  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.394  4651  4651 D BluetoothMapService: MAP Service closeService in
09-29 06:30:56.394  4651  4651 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 06:30:56.394  4651  4866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:30:56.394  4651  4866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:30:56.394  4651  4866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:30:56.394  4651  4651 D ObexServerSockets0: shutdown(block = true)
09-29 06:30:56.394  4651  4723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 06:30:56.395  4651  4895 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-29 06:30:56.395   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-29 06:30:56.395  4651  4723 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-29 06:30:56.395   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-29 06:30:56.395   928  5421 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-29 06:30:56.397   540   540 E Parcel  : Reading a NULL string not supported here.
09-29 06:30:56.398  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:30:56.398  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:30:56.399  4651  4651 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-29 06:30:56.399  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 06:30:56.399  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:30:56.399  4651  4651 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 06:30:56.399  4651  4896 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 06:30:56.400  4651  4871 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 06:30:56.400  4651  4651 I BtOppRfcommListener: stopping Accept Thread
09-29 06:30:56.401  4651  5364 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 06:30:56.402   928   928 D RttService: SCAN_AVAILABLE : 1
09-29 06:30:56.403  4651  5364 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 06:30:56.403   928  3136 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 06:30:56.404   928  3029 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-29 06:30:56.406  3827  3965 W QCNEJ   : |CORE| network lost: 100
,09-29 06:30:56.406  4651  4651 D HealthService: Received stop request...Stopping profile...
,09-29 06:30:56.406  3827  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-29 06:30:56.408  4651  4651 V BluetoothAdapterState: isTurningOff()=true
,09-29 06:30:56.408  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.408  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:30:56.408  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:30:56.410   928  3027 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-29 06:30:56.411  4651  4651 D PanService: Received stop request...Stopping profile...
09-29 06:30:56.415  4651  4723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-29 06:30:56.415  4651  4866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:30:56.415  4651  4651 V BluetoothAdapterState: isTurningOff()=true
09-29 06:30:56.415  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.415  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:30:56.415  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:30:56.415  4651  4866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:30:56.415  4651  4651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-29 06:30:56.416  4651  4866 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 06:30:56.416  4651  4651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 06:30:56.416  4651  4866 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 06:30:56.416  4651  4866 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 06:30:56.416  4651  4866 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 06:30:56.416  4651  4651 D BluetoothMapService: Received stop request...Stopping profile...
09-29 06:30:56.416  4651  4651 D BluetoothMapService: stop()
09-29 06:30:56.418  4651  4651 D BluetoothMapAppObserver: deinitObservers()
09-29 06:30:56.418  4651  4651 D BluetoothMapAppObserver: removeReceiver()
09-29 06:30:56.418  4651  4723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 06:30:56.418   928  3027 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 06:30:56.420  4651  4651 D SapService: Received stop request...Stopping profile...
09-29 06:30:56.420  4651  4651 V SapService: stop()
,09-29 06:30:56.423  4651  4651 V BluetoothAdapterState: isTurningOff()=true
09-29 06:30:56.423  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.423  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:30:56.423  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:30:56.423  4651  4651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 06:30:56.424  4651  4723 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 06:30:56.424  4651  4651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-29 06:30:56.424  4651  4651 V BluetoothAdapterState: isTurningOff()=true
,09-29 06:30:56.424  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.424  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 06:30:56.424  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:30:56.424  4651  4651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 06:30:56.424  4651  4651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 06:30:56.425  4651  4651 D BluetoothMapService: MAP Service closeService in
09-29 06:30:56.425  4651  4651 V BluetoothAdapterState: isTurningOff()=true
09-29 06:30:56.425  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.425  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 06:30:56.426  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:30:56.426  4651  4651 D BluetoothMapService: cleanup()
,09-29 06:30:56.426  4651  4651 D BluetoothMapService: MAP Service closeService in
,09-29 06:30:56.426  4651  4651 V BluetoothAdapterState: isTurningOff()=true
09-29 06:30:56.426  4651  4651 V BluetoothAdapterState: isTurningOn()=false
09-29 06:30:56.426  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 06:30:56.426  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:30:56.426  4651  4719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 06:30:56.426  4651  4719 D BluetoothAdapterProperties: Setting state to 15
09-29 06:30:56.426  4651  4719 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 06:30:56.427  3183  3183 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 06:30:56.427  3183  3183 D PanProfile: Bluetooth service disconnected
09-29 06:30:56.427  3183  4031 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 06:30:56.427  4651  4719 I BluetoothAdapterState: Entering BleOnState
09-29 06:30:56.428  3183  3183 D BluetoothMap: Proxy object disconnected
,09-29 06:30:56.428  3183  3183 D MapProfile: Bluetooth service disconnected
09-29 06:30:56.429  3863  3889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:30:56.429   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 06:30:56.433  3183  3198 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 06:30:56.433   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:30:56.433   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:30:56.434  3183  3195 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:30:56.434  3183  4031 D BluetoothMap: onBluetoothStateChange: up=false
09-29 06:30:56.434   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:30:56.435  3183  3198 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 06:30:56.435  3183  3195 D BluetoothPan: onBluetoothStateChange on: false
09-29 06:30:56.436  4651  4719 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-29 06:30:56.436  4651  4719 D BluetoothAdapterProperties: Setting state to 16
09-29 06:30:56.436  4651  4719 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 06:30:56.437   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-29 06:30:56.437  4651  4719 D BluetoothAdapterProperties: onBleDisable
09-29 06:30:56.437  4651  4719 I BluetoothAdapterState: Entering PendingCommandState
09-29 06:30:56.438  4651  4720 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 06:30:56.438  4651  4723 D BluetoothAdapterProperties: Scan Mode:20
09-29 06:30:56.439  4651  4866 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 06:30:56.439  4651  4866 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 06:30:56.441  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:30:56.441  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:30:56.441  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.442  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:30:56.444  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:30:56.445  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:30:56.446  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.446  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:30:56.448  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:30:56.448  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:30:56.450  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.452  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.453  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.454  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-29 06:30:56.465   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 06:30:56.465   510   927 D CommandListener: Clearing all IP addresses on wlan0
09-29 06:30:56.466   928  3029 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-29 06:30:56.466   928  3029 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 06:30:56.466   510   927 D TetherController: Setting IP forward enable = 0
,09-29 06:30:56.469   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-29 06:30:56.473  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.474  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.475  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.474  5335  5335 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ae2c34e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-29 06:30:56.478  5093  5116 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-29 06:30:56.478  5093  5116 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-29 06:30:56.478  5093  5116 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-29 06:30:56.478  5093  5116 E SarControlService: no key has been found,reset the power
09-29 06:30:56.478   928  3027 D DhcpClient: doQuit
09-29 06:30:56.479  5093  5130 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 06:30:56.479   928  3027 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 06:30:56.479  5093  5130 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 06:30:56.479  5093  5130 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 06:30:56.479  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 06:30:56.479  5118  5118 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 06:30:56.479  3493  3493 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 06:30:56.480   928  5423 D DhcpClient: onQuitting
09-29 06:30:56.480  5093  5130 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 06:30:56.481  5093  5130 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 06:30:56.481  5093  5130 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 06:30:56.483  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:30:56.483  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:30:56.482  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 06:30:56.483  5118  5118 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 06:30:56.484  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.484  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:30:56.485  5118  5132 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5238524 HexData = [00000000ea03000000000000ffffffff]
09-29 06:30:56.485  5118  5132 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 06:30:56.485  5118  5132 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-29 06:30:56.485  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 06:30:56.485  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:30:56.485  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:30:56.485  5093  5103 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 06:30:56.485  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.485  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:30:56.487  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:30:56.487  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:30:56.487  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:30:56.487  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:30:56.493  5118  5132 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5238524 HexData = [00000000eb03000000000000ffffffff]
,09-29 06:30:56.493  5118  5132 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 06:30:56.494  5118  5132 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-29 06:30:56.495  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 06:30:56.496  5093  5104 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-29 06:30:56.497  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 06:30:56.506  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 06:30:56.507  3493  3493 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-29 06:30:56.513  3493  3493 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-29 06:30:56.515   510   920 W SocketClient: write error (Broken pipe)
,09-29 06:30:56.515   510   920 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-29 06:30:56.515   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c7d9a0b:true
09-29 06:30:56.515   510   920 W SocketListener: Error sending broadcast (Broken pipe)
,09-29 06:30:56.522   928  3204 I ActivityManager: Start proc 5767:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-29 06:30:56.532   510   927 E Netd    : netlink response contains error (No such file or directory)
,09-29 06:30:56.536   510   927 D TetherController: Setting IP forward enable = 0
,09-29 06:30:56.537   928  3029 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-29 06:30:56.537   928  3029 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 06:30:56.539  5738  5738 D LocalBluetoothProfileManager: Adding local MAP profile
,09-29 06:30:56.544  5738  5738 D BluetoothMap: Create BluetoothMap proxy object
,09-29 06:30:56.548  3493  3493 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 06:30:56.556  3493  3493 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-29 06:30:56.557  5738  5738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-29 06:30:56.565  5767  5767 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-29 06:30:56.570  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-29 06:30:56.577   928  3932 I ActivityManager: Killing 5033:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-29 06:30:56.648  4651  4723 I bt_hci  : shut_down
,09-29 06:30:56.651  4651  4730 D bt_hwcfg: hw_epilog_process
,09-29 06:30:56.652  4651  4730 I bt_vendor: low_power_mode_cb
,09-29 06:30:56.654  4651  4730 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-29 06:30:56.655  4651  4730 I bt_vendor: epilog_cb
09-29 06:30:56.655  4651  4730 I bt_hci  : epilog_finished_callback
,09-29 06:30:56.657  4651  4723 I bt_hci_h4: hal_close
,09-29 06:30:56.658  4651  4723 I bt_userial_vendor: device fd = 54 close
,09-29 06:30:56.659   928  3027 D wifi    : In wifi stop Hal
09-29 06:30:56.659   928  3027 D wifi    : halHandle = 0x7f76916540, mVM = 0x7f92f4d140, mCls = 0x100a02
09-29 06:30:56.659  5068  5068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 06:30:56.659   928  3492 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 06:30:56.659   928  3492 D WifiHAL : Got a signal to exit!!!
09-29 06:30:56.659   928  3492 I WifiHAL : Exit wifi_event_loop
09-29 06:30:56.660   928  3027 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-29 06:30:56.660   928  3027 E WifiHAL : Event processing terminated
09-29 06:30:56.660   928  3027 D wifi    : In wifi cleaned up handler
09-29 06:30:56.660   928  3027 I WifiHAL : Internal cleanup completed
09-29 06:30:56.662  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:30:56.662  4097  4275 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 06:30:56.664  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:56.666  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:30:56.677   928  3492 D wifi    : set interface wlan0 flags (DOWN)
,09-29 06:30:56.677   928  3027 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 06:30:56.771  4651  4720 D bt_stack_manager: event_shut_down_stack finished.
,09-29 06:30:56.771  4651  4719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 06:30:56.773  4651  4719 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-29 06:30:56.773  4651  4651 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 06:30:56.774  4651  4651 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 06:30:56.774  4651  4651 D BtGatt.GattService: stop()
09-29 06:30:56.774  4651  4651 D BtGatt.AdvertiseManager: advertise clients cleared
09-29 06:30:56.776  4651  4651 V BluetoothAdapterState: isTurningOff()=false
09-29 06:30:56.776  4651  4651 V BluetoothAdapterState: isTurningOn()=false
,09-29 06:30:56.776  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:30:56.776  4651  4651 V BluetoothAdapterState: isBleTurningOff()=true
09-29 06:30:56.777  4651  4719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 06:30:56.777  4651  4719 D BluetoothAdapterProperties: Setting state to 10
09-29 06:30:56.777  4651  4719 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 06:30:56.777  4651  4719 I BluetoothAdapterState: Entering OffState
,09-29 06:30:56.778   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-29 06:30:56.790  4651  4651 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 06:30:56.790  4651  4651 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-29 06:30:56.790  4651  4651 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-29 06:30:56.792  4651  4720 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-29 06:30:56.807  4651  4720 D bt_stack_manager: event_clean_up_stack finished.
,09-29 06:30:56.808  4651  4651 I art     : System.exit called, status: 0
09-29 06:30:56.808  4651  4651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 06:30:56.820  5767  5767 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-29 06:30:56.820  5767  5767 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.820  5767  5767 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.820  5767  5767 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.820  5767  5767 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.k.d(PG:583)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.820  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.821  5767  5767 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.821  5767  5767 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.821  5767  5767 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:30:56.821  5767  5767 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:30:56.827  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 06:30:56.864   928  3204 I ActivityManager: Process com.android.bluetooth (pid 4651) has died
09-29 06:30:56.866  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-29 06:30:56.867  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 06:30:56.868   928  4102 I ActivityManager: Killing 5451:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
09-29 06:30:56.880   928   945 D Tethering: InitialState.processMessage what=4
,09-29 06:30:56.902   928  4102 I ActivityManager: Start proc 5801:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-29 06:30:56.903   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 06:30:56.961  5801  5801 D AdapterServiceConfig: Adding HeadsetService
09-29 06:30:56.961  5801  5801 D AdapterServiceConfig: Adding A2dpService
09-29 06:30:56.961  5801  5801 D AdapterServiceConfig: Adding HidService
,09-29 06:30:56.961  5801  5801 D AdapterServiceConfig: Adding HealthService
09-29 06:30:56.961  5801  5801 D AdapterServiceConfig: Adding PanService
09-29 06:30:56.961  5801  5801 D AdapterServiceConfig: Adding GattService
09-29 06:30:56.962  5801  5801 D AdapterServiceConfig: Adding BluetoothMapService
09-29 06:30:56.962  5801  5801 D AdapterServiceConfig: Adding SapService
,09-29 06:30:56.967   928  4102 I ActivityManager: Killing 5463:com.android.chrome/u0a39 (adj 15): empty #17
,09-29 06:30:57.027  3791  3791 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-29 06:30:57.031  3791  3791 D SystemUpdateService: onCreate
,09-29 06:30:57.034  3791  3791 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 06:30:57.049  3791  3791 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-29 06:30:57.055  3791  5814 I SystemUpdateService: active receiver: enabled
,09-29 06:30:57.060  3791  5449 I iu.UploadsManager: num queued entries: 0
,09-29 06:30:57.061  3791  5449 I iu.UploadsManager: num updated entries: 0
09-29 06:30:57.061  3791  5449 I iu.SyncManager: NEXT; no task
,09-29 06:30:57.067  3791  3791 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 06:30:57.069  3791  3791 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 06:30:57.071  3791  5814 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 06:30:57.081   928  3208 I ActivityManager: Start proc 5816:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-29 06:30:57.082  3791  5814 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-29 06:30:57.082  3791  5814 I SystemUpdateService: now status is 0 (complete)
,09-29 06:30:57.084  3791  5814 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-29 06:30:57.085  3791  5814 I SystemUpdateService: file has been verified
09-29 06:30:57.085  3791  5814 I SystemUpdateService: OTA package size = 21989297
,09-29 06:30:57.099  3791  5814 I SystemUpdateService: showing system update notification
,09-29 06:30:57.117  5816  5816 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-29 06:30:57.123  5816  5816 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 06:30:57.130  5816  5816 D SprintDMHelper: simOperator: 
09-29 06:30:57.131  5816  5816 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 06:30:57.143   928  4102 I ActivityManager: Start proc 5828:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-29 06:30:57.156  3791  3791 D SystemUpdateService: onDestroy
,09-29 06:30:57.158   928  3927 I ActivityManager: Killing 5482:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-29 06:30:57.251  5068  5842 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-29 06:30:57.253   928  3624 I ActivityManager: Start proc 5843:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-29 06:30:57.255   928  3643 I ActivityManager: Killing 5335:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-29 06:30:57.277  5767  5795 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-29 06:30:57.289   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5573865:true
,09-29 06:30:57.317  5843  5843 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-29 06:30:57.507   928  3208 I ActivityManager: Killing 4734:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-29 06:30:57.551   928   939 I ActivityManager: Start proc 5857:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-29 06:30:57.581  5857  5857 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-29 06:30:57.590   928  3208 I ActivityManager: Killing 5540:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-29 06:31:01.367   928  3624 D WifiService: setWifiEnabled: true pid=5684, uid=10077
09-29 06:31:01.368   928  3624 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 06:31:01.378   510   927 D SoftapController: Softap fwReload - Ok
,09-29 06:31:01.385   510   927 D CommandListener: Setting iface cfg
09-29 06:31:01.385   510   927 D CommandListener: Trying to bring down wlan0
09-29 06:31:01.387   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-29 06:31:01.392   928  3027 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 06:31:02.107   928  3027 D wifi    : set interface wlan0 flags (UP)
09-29 06:31:02.110   928  3027 I WifiHAL : Initializing wifi
09-29 06:31:02.111   928  3027 I WifiHAL : Creating socket
09-29 06:31:02.117   928  3027 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-29 06:31:02.117   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-29 06:31:02.117   928  3027 D wifi    : Did set static halHandle = 0x7f76916540
09-29 06:31:02.118   928  3027 D wifi    : halHandle = 0x7f76916540, mVM = 0x7f92f4d140, mCls = 0x1018e6
09-29 06:31:02.118   928  3027 D wifi    : array field set
09-29 06:31:02.118   928  3027 I WifiNative-HAL: interface[0] = wlan0
09-29 06:31:02.122   928  5875 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547450086720
09-29 06:31:02.122   928  5875 D wifi    : waitForHalEvents called, vm = 0x7f92f4d140, obj = 0x1018e6, env = 0x7f746509c0
,09-29 06:31:02.195  5876  5876 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 06:31:02.220  5876  5876 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 06:31:02.223   928  3027 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 06:31:02.227  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:02.228  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:02.229  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:02.235  5876  5876 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 06:31:02.235  5876  5876 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 06:31:02.256  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:02.256  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:02.256  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:02.256  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:02.256   928  3027 D WifiConfigStore: Loading config and enabling all networks 
09-29 06:31:02.257  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:02.257  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:02.257  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:02.257  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:02.258  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:02.259  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:02.259  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:02.259  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:31:02.266   928  3027 D WifiConfigStore: loaded 0 passpoint configs
,09-29 06:31:02.266   928  3027 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 06:31:02.266   928  3027 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-29 06:31:02.267   928  3027 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-29 06:31:02.268   928  3027 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 06:31:02.268   928  3027 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 06:31:02.268   928  3027 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 06:31:02.268   928  3027 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 06:31:02.273   928  3027 D WifiNative-HAL: Setting external_sim to 1
09-29 06:31:02.274   928  3027 D wifi    : setting dfs flag to true, 0x7f7a3baa60
09-29 06:31:02.275   928  3027 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 06:31:02.275   928  3027 D wifi    : setting scan oui 0x7f7a3baa60
,09-29 06:31:02.275   928  3027 D WifiHAL : Sending mac address OUI
,09-29 06:31:02.276  5068  5068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 06:31:02.281   928  3027 E native  : do suspend false
,09-29 06:31:02.292   928  3027 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-29 06:31:02.292   928   928 D RttService: SCAN_AVAILABLE : 3
09-29 06:31:02.293   510   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-29 06:31:02.293   928  3136 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 06:31:02.294   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:02.298   928  3016 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
09-29 06:31:02.298   928  3016 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 06:31:02.310   928  3016 D WifiNative-HAL: p2pGetDeviceAddress
09-29 06:31:02.311   928  3016 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 06:31:02.317   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=269468 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,09-29 06:31:05.477  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:05.482  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:05.488  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:05.495  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:05.547   928  3027 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 06:31:05.548   928  3027 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 06:31:05.548   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:31:05.564   928  3027 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 06:31:05.609   928  3027 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 06:31:05.614  5876  5876 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 06:31:06.059  5876  5876 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 06:31:06.109  5876  5876 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 06:31:06.110  5876  5876 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 06:31:06.113   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:06.116   928  3027 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 06:31:06.116   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:31:06.116   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 06:31:06.131   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:31:06.143   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:06.148   928  3027 D WifiStateMachine: Start Dhcp Watchdog 2
,09-29 06:31:06.162   928  3027 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-29 06:31:06.162   928  3029 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-29 06:31:06.162   928  3029 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-29 06:31:06.168   928  5884 D DhcpClient: Receive thread started
,09-29 06:31:06.264   928  3027 E native  : do suspend false
,09-29 06:31:06.298   928  5883 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 06:31:06.319   928  5884 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172567, domain null
,09-29 06:31:06.321   928  5883 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172567 seconds
,09-29 06:31:06.323   928  5883 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 06:31:06.339   928  5884 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-29 06:31:06.340   928  5883 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-29 06:31:06.344   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:06.349   928  3027 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 06:31:06.356   928  5883 D DhcpClient: Scheduling renewal in 86399s
,09-29 06:31:06.376   928  3027 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-29 06:31:06.377   928  3027 D WifiConfigStore: No blacklist allowed without epno enabled
,09-29 06:31:06.377   928  3900 D WifiService: setWifiEnabled: false pid=5684, uid=10077
09-29 06:31:06.377   928  3900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-29 06:31:06.378   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-29 06:31:06.380   928  3027 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 06:31:06.383   928  3029 D ConnectivityService: Adding iface wlan0 to network 101
,09-29 06:31:06.406   928  3027 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-29 06:31:06.406   928  3027 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-29 06:31:06.406   928  3027 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 06:31:06.406   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:31:06.416   928  5883 D DhcpClient: Clearing IP address
,09-29 06:31:06.428   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-29 06:31:06.429   928  3029 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-29 06:31:06.430   928  3029 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-29 06:31:06.435   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:06.436   928  3029 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-29 06:31:06.443   928  5884 D DhcpClient: Receive thread stopped
,09-29 06:31:06.448   928  3029 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-29 06:31:06.454   928  3029 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-29 06:31:06.456   540   540 E Parcel  : Reading a NULL string not supported here.
09-29 06:31:06.456   928   928 D RttService: SCAN_AVAILABLE : 1
,09-29 06:31:06.457   928  3136 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 06:31:06.461   928  3029 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 06:31:06.465   928  3029 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-29 06:31:06.465   928  3029 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-29 06:31:06.465   928  3029 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-29 06:31:06.465   928  3029 D ConnectivityService:    accepting network in place of null
09-29 06:31:06.466   928  3029 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 06:31:06.474   928  3027 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 06:31:06.474   928  3027 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 06:31:06.488   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 06:31:06.508   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-29 06:31:06.509   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-29 06:31:06.512   928  3029 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-29 06:31:06.512   928  3029 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 06:31:06.512  3827  3965 W QCNEJ   : |CORE| network available: 101
09-29 06:31:06.513   928  3027 D DhcpClient: doQuit
09-29 06:31:06.513   928  3027 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 06:31:06.514  3827  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-29 06:31:06.514  5876  5876 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 06:31:06.514   928  5883 D DhcpClient: onQuitting
,09-29 06:31:06.516  3827  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-29 06:31:06.516  3827  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-29 06:31:06.518   928  3029 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-29 06:31:06.518   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-29 06:31:06.519   928  3027 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-29 06:31:06.519   928   945 D Tethering: MasterInitialState.processMessage what=3
09-29 06:31:06.519   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-29 06:31:06.523  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:06.523  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:31:06.523  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.523  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:31:06.524   928  3029 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-29 06:31:06.525  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:06.525  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:31:06.525  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.525  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:06.526  3827  3965 W QCNEJ   : |CORE| network lost: 101
09-29 06:31:06.527  3827  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-29 06:31:06.528  5876  5876 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-29 06:31:06.528  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:06.528  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:06.528  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.528  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:31:06.529  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:06.529  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:06.530  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:06.530  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:06.533  5876  5876 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-29 06:31:06.540  3791  3791 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-29 06:31:06.543  3791  3791 D SystemUpdateService: onCreate
,09-29 06:31:06.548  3791  3791 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 06:31:06.553   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 06:31:06.554  3791  5895 I SystemUpdateService: active receiver: enabled
,09-29 06:31:06.564  3791  3791 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-29 06:31:06.565  3791  3791 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 06:31:06.568  5816  5816 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 06:31:06.574  5816  5816 D SprintDMHelper: simOperator: 
,09-29 06:31:06.574  5816  5816 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-29 06:31:06.575   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 06:31:06.576   928  3029 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-29 06:31:06.576   928  3029 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-29 06:31:06.577  3791  5895 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 06:31:06.581   928   945 D Tethering: MasterInitialState.processMessage what=3
09-29 06:31:06.582  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:06.583  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:06.584  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:06.592  3791  5895 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-29 06:31:06.592  3791  5895 I SystemUpdateService: now status is 0 (complete)
09-29 06:31:06.592  3791  5895 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-29 06:31:06.593  3791  5895 I SystemUpdateService: file has been verified
09-29 06:31:06.593  3791  5895 I SystemUpdateService: OTA package size = 21989297
,09-29 06:31:06.599  5876  5876 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 06:31:06.600  3791  3791 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 06:31:06.602  3791  3791 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 06:31:06.609  5876  5876 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-29 06:31:06.610  3791  5895 I SystemUpdateService: showing system update notification
,09-29 06:31:06.627  3791  3791 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 06:31:06.628  3791  3791 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 06:31:06.629   510   927 E Netd    : netlink response contains error (No such file or directory)
09-29 06:31:06.630  5816  5816 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 06:31:06.633  5816  5816 D SprintDMHelper: simOperator: 
,09-29 06:31:06.633  5816  5816 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 06:31:06.657  3791  5906 I SystemUpdateService: active receiver: enabled
,09-29 06:31:06.669  3791  5906 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 06:31:06.671  3791  5906 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-29 06:31:06.671  3791  5906 I SystemUpdateService: now status is 0 (complete)
09-29 06:31:06.671  3791  5906 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 06:31:06.671  3791  5906 I SystemUpdateService: file has been verified
09-29 06:31:06.672  3791  5906 I SystemUpdateService: OTA package size = 21989297
,09-29 06:31:06.678  3791  5906 I SystemUpdateService: showing system update notification
,09-29 06:31:06.690  3791  3791 D SystemUpdateService: onDestroy
,09-29 06:31:06.712   928  3027 D wifi    : In wifi stop Hal
,09-29 06:31:06.712   928  3027 D wifi    : halHandle = 0x7f76916540, mVM = 0x7f92f4d140, mCls = 0x1018e6
09-29 06:31:06.712   928  5875 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 06:31:06.712   928  5875 D WifiHAL : Got a signal to exit!!!
09-29 06:31:06.712   928  5875 I WifiHAL : Exit wifi_event_loop
09-29 06:31:06.712   928  3027 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 06:31:06.713   928  3027 E WifiHAL : Event processing terminated
09-29 06:31:06.713   928  3027 D wifi    : In wifi cleaned up handler
09-29 06:31:06.713   928  3027 I WifiHAL : Internal cleanup completed
09-29 06:31:06.713  5068  5068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 06:31:06.715  4097  4275 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 06:31:06.716  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:06.717  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:06.718  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:06.737   928  5875 D wifi    : set interface wlan0 flags (DOWN)
09-29 06:31:06.738   928  3027 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 06:31:06.949   928   945 D Tethering: InitialState.processMessage what=4
,09-29 06:31:06.956   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 06:31:07.117   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:07.515   928  3029 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-29 06:31:08.120   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:09.123   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:10.127   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:11.129   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-29 06:31:11.426   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@95ffcb4:true
,09-29 06:31:11.426  5801  5801 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 06:31:11.433  5801  5801 I bt_bluedroid: init
,09-29 06:31:11.435  5801  5908 I BluetoothAdapterState: Entering OffState
,09-29 06:31:11.438  5801  5909 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-29 06:31:11.439  5801  5909 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 06:31:11.439  5801  5909 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 06:31:11.439  5801  5909 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-29 06:31:11.441  5801  5801 I bt_bluedroid: get_profile_interface socket
,09-29 06:31:11.444  5801  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 06:31:11.445  5801  5801 I bt_bluedroid: get_profile_interface sdp
09-29 06:31:11.448  5801  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 06:31:11.456  5801  5813 I bt_bluedroid: config_hci_snoop_log
,09-29 06:31:11.459   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 06:31:11.469  5801  5908 D BluetoothAdapterState: Current state: OFF, message: 0
09-29 06:31:11.469  5801  5908 D BluetoothAdapterProperties: Setting state to 14
09-29 06:31:11.469  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 06:31:11.473  5801  5908 D BluetoothBondStateMachine: make
,09-29 06:31:11.476   928  5881 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-29 06:31:11.476   928  3029 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 06:31:11.478  5801  5913 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 06:31:11.482  5801  5908 I BluetoothAdapterState: Entering PendingCommandState
,09-29 06:31:11.484  5801  5801 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 06:31:11.488  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:11.489  5801  5801 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 06:31:11.490  5801  5801 D BtGatt.GattService: Received start request. Starting profile...
,09-29 06:31:11.490  5801  5801 D BtGatt.GattService: start()
09-29 06:31:11.491  5801  5801 I bt_bluedroid: get_profile_interface gatt
,09-29 06:31:11.492  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:11.492  5801  5801 D BtGatt.AdvertiseManager: advertise manager created
,09-29 06:31:11.501  5801  5801 V BluetoothAdapterState: isTurningOff()=false
,09-29 06:31:11.502  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:11.502  5801  5801 V BluetoothAdapterState: isBleTurningOn()=true
09-29 06:31:11.502  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:11.502  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 06:31:11.505  5801  5908 I bt_bluedroid: bt_bluedroid
,09-29 06:31:11.506  5801  5909 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 06:31:11.506  5801  5909 I bt_hci  : start_up
,09-29 06:31:11.516  5801  5909 I bt_vendor: alloc value 0xf3af8871
09-29 06:31:11.516  5801  5909 I bt_vendor: init
09-29 06:31:11.516  5801  5909 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-29 06:31:11.516  5801  5909 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 06:31:11.631  5801  5909 D bt_hci  : start_up starting async portion
09-29 06:31:11.632  5801  5916 I bt_hci  : event_finish_startup
,09-29 06:31:11.632  5801  5916 I bt_hci_h4: hal_open
09-29 06:31:11.633  5801  5916 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 06:31:11.636  5801  5916 I bt_userial_vendor: device fd = 54 open
,09-29 06:31:11.630  5917  5917 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 06:31:11.652  5801  5916 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 06:31:11.657  5801  5916 D bt_hwcfg: Chipset BCM4358A3
,09-29 06:31:11.657  5801  5916 D bt_hwcfg: Target name = [BCM4358A3]
09-29 06:31:11.658  5801  5916 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 06:31:12.415  5801  5916 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-29 06:31:12.416  5801  5916 D bt_hwcfg: Settlement delay -- 100 ms
,09-29 06:31:12.416  5801  5916 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 06:31:12.554  5801  5916 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 06:31:12.555  5801  5916 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 06:31:12.557  5801  5916 I bt_hwcfg: vendor lib fwcfg completed
,09-29 06:31:12.558  5801  5916 I bt_vendor: firmware callback
,09-29 06:31:12.558  5801  5916 I bt_hci  : firmware_config_callback
,09-29 06:31:12.569  5801  5919 I bt_btu  : btu_task pending for preload complete event
,09-29 06:31:12.570  5801  5919 I bt_btu_task: Bluetooth chip preload is complete
09-29 06:31:12.570  5801  5919 I bt_btu  : btu_task received preload complete event
,09-29 06:31:12.579  5801  5919 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 06:31:12.579  5801  5919 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 06:31:12.579  5801  5919 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 06:31:12.579  5801  5919 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_SMP
,09-29 06:31:12.580  5801  5919 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 06:31:12.581  5801  5919 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 06:31:12.681  5801  5919 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3a76549
,09-29 06:31:12.681  5801  5919 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3a76549 
,09-29 06:31:12.700  5801  5912 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 06:31:12.702  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 06:31:12.702  5801  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 06:31:12.706  5801  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 06:31:12.709  5801  5912 D BluetoothAdapterProperties: Scan Mode:20
,09-29 06:31:12.710  5801  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 06:31:12.710  5801  5912 D bt_hci  : do_postload posting postload work item
09-29 06:31:12.710  5801  5916 I bt_hci  : event_postload
09-29 06:31:12.710  5801  5916 I bt_vendor: sco_config_cb
09-29 06:31:12.710  5801  5916 I bt_hci  : sco_config_callback postload finished.
09-29 06:31:12.714  5801  5912 D bt_bte_conf: Device ID record 1 : primary
,09-29 06:31:12.714  5801  5912 D bt_bte_conf:   vendorId            = 000f
09-29 06:31:12.714  5801  5912 D bt_bte_conf:   vendorIdSource      = 0001
09-29 06:31:12.714  5801  5912 D bt_bte_conf:   product             = 1200
09-29 06:31:12.714  5801  5912 D bt_bte_conf:   version             = 1436
09-29 06:31:12.714  5801  5912 D bt_bte_conf:   clientExecutableURL = 
09-29 06:31:12.714  5801  5912 D bt_bte_conf:   serviceDescription  = 
,09-29 06:31:12.714  5801  5912 D bt_bte_conf:   documentationURL    = 
09-29 06:31:12.715  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:12.715  5801  5912 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 06:31:12.715  5801  5909 D bt_stack_manager: event_start_up_stack finished
09-29 06:31:12.716  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 06:31:12.717  5801  5908 D BluetoothAdapterProperties: Setting state to 15
09-29 06:31:12.717  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 06:31:12.717  5801  5908 I BluetoothAdapterState: Entering BleOnState
09-29 06:31:12.719  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:12.722  5801  5908 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 06:31:12.722  5801  5908 D BluetoothAdapterProperties: Setting state to 11
09-29 06:31:12.722  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-29 06:31:12.726  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:12.729  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:12.730  5801  5801 D HeadsetService: Received start request. Starting profile...
,09-29 06:31:12.733  5801  5801 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 06:31:12.734  5801  5801 D HeadsetStateMachine: make
,09-29 06:31:12.735  5801  5916 I bt_vendor: low_power_mode_cb
09-29 06:31:12.739  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:12.744  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:12.747  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:12.749  5801  5908 I BluetoothAdapterState: Entering PendingCommandState
,09-29 06:31:12.755  5801  5801 D HeadsetStateMachine: max_hf_connections = 1
09-29 06:31:12.755  5801  5801 I bt_bluedroid: get_profile_interface handsfree
09-29 06:31:12.755  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 06:31:12.756  5801  5912 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-29 06:31:12.760  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:12.760  5801  5801 D A2dpService: Received start request. Starting profile...
09-29 06:31:12.761  5801  5801 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 06:31:12.762  5801  5801 I bt_bluedroid: get_profile_interface avrcp
,09-29 06:31:12.768  5801  5801 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 06:31:12.769  5801  5801 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 06:31:12.769  5801  5801 D A2dpStateMachine: make
09-29 06:31:12.770  5801  5801 I bt_bluedroid: get_profile_interface a2dp
,09-29 06:31:12.772  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-29 06:31:12.773  5801  5928 D A2dpStateMachine: Enter Disconnected: -2
,09-29 06:31:12.774  5801  5801 I BluetoothHidServiceJni: classInitNative: succeeds
09-29 06:31:12.775  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:12.777  5801  5801 D HidService: Received start request. Starting profile...
,09-29 06:31:12.777  5738  5738 D BluetoothInputDevice: Proxy object connected
09-29 06:31:12.777  5801  5801 I bt_bluedroid: get_profile_interface hidhost
09-29 06:31:12.777  5801  5801 D HidService: setHidService(): set to: null
09-29 06:31:12.777  5801  5912 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a5756d
09-29 06:31:12.778  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 06:31:12.778  5738  5738 D HidProfile: Bluetooth service connected
09-29 06:31:12.778  5801  5801 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 06:31:12.780  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:12.780  5801  5801 D HealthService: Received start request. Starting profile...
,09-29 06:31:12.782  5801  5801 I bt_bluedroid: get_profile_interface health
,09-29 06:31:12.783  5801  5801 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 06:31:12.783  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:12.784  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 06:31:12.785  5801  5801 D PanService: Received start request. Starting profile...
09-29 06:31:12.785  5801  5801 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 06:31:12.785  5801  5801 I bt_bluedroid: get_profile_interface pan
09-29 06:31:12.785  5738  5738 D PanProfile: Bluetooth service connected
09-29 06:31:12.785  5801  5912 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 06:31:12.788  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:12.789  5801  5801 D BluetoothMapService: Received start request. Starting profile...
09-29 06:31:12.789  5801  5801 D BluetoothMapService: start()
09-29 06:31:12.791  5738  5738 D BluetoothMap: Proxy object connected
09-29 06:31:12.792  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 06:31:12.793  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 06:31:12.793  5801  5801 D BluetoothMapAppObserver: createReceiver()
09-29 06:31:12.794  5738  5738 D MapProfile: Bluetooth service connected
09-29 06:31:12.794  5738  5738 D BluetoothMap: getConnectedDevices()
09-29 06:31:12.795  5801  5801 D BluetoothMapAppObserver: initObservers()
09-29 06:31:12.795  5801  5801 D BluetoothMapAppObserver: getEnabledAccountItems()
09-29 06:31:12.795  5738  5738 D BluetoothMap: Bluetooth is Not enabled
09-29 06:31:12.801  5801  5801 V SapService: SapBinder()
09-29 06:31:12.801  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:12.804  5801  5801 D SapService: Received start request. Starting profile...
09-29 06:31:12.804  5801  5801 V SapService: start()
,09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:12.807  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:31:12.808  5801  5925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:12.808  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:12.808  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 06:31:12.810  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:12.810  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:12.810  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:12.810  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:31:12.811  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 06:31:12.811  5801  5908 D BluetoothAdapterProperties: ScanMode =  20
09-29 06:31:12.811  5801  5908 D BluetoothAdapterProperties: State =  11
,09-29 06:31:12.811  5801  5908 D BluetoothAdapterProperties: Setting state to 12
09-29 06:31:12.811  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 06:31:12.812  5801  5908 I BluetoothAdapterState: Entering OnState
09-29 06:31:12.813  5801  5912 D BluetoothAdapterProperties: Scan Mode:21
09-29 06:31:12.813  5738  5752 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 06:31:12.814  5801  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 06:31:12.814  3183  3198 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 06:31:12.814  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-29 06:31:12.817  5738  5749 D BluetoothMap: onBluetoothStateChange: up=true
09-29 06:31:12.818  5738  5752 D BluetoothPan: onBluetoothStateChange on: true
09-29 06:31:12.818  3863  3889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:12.818   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:12.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:12.819  3183  4031 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 06:31:12.820   928   928 D BluetoothA2dp: Proxy object connected
,09-29 06:31:12.821  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 06:31:12.821   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:12.821  3183  3183 D BluetoothInputDevice: Proxy object connected
09-29 06:31:12.821  5738  5749 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 06:31:12.821  3183  3183 D HidProfile: Bluetooth service connected
09-29 06:31:12.821  5801  5801 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 06:31:12.822  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:12.823   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:12.823  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 06:31:12.823  3183  3198 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-29 06:31:12.823  3183  4031 D BluetoothMap: onBluetoothStateChange: up=true
09-29 06:31:12.825  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:31:12.825   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:12.825  3183  3183 D BluetoothMap: Proxy object connected
09-29 06:31:12.825  3183  3183 D MapProfile: Bluetooth service connected
09-29 06:31:12.825  3183  3183 D BluetoothMap: getConnectedDevices()
09-29 06:31:12.825  3183  4031 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:12.826  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:12.827  5801  5801 D ObexServerSockets: Succeed to create listening sockets 
09-29 06:31:12.827  5801  5801 D ObexServerSockets0: startAccept()
09-29 06:31:12.827  5801  5801 D ObexServerSockets0: prepareForNewConnect()
09-29 06:31:12.827  3183  3195 D BluetoothPan: onBluetoothStateChange on: true
09-29 06:31:12.827  3183  3183 D BluetoothA2dp: Proxy object connected
,09-29 06:31:12.828  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:12.832   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 06:31:12.832  3183  3183 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 06:31:12.832  3183  3183 D PanProfile: Bluetooth service connected
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:12.833  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:12.833  5801  5801 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 06:31:12.833  5801  5801 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 06:31:12.834  5801  5933 D ObexServerSockets0: Accepting socket connection...
09-29 06:31:12.834  5801  5935 D ObexServerSockets0: Accepting socket connection...
09-29 06:31:12.834  5801  5801 D BluetoothMapService: onReceive
09-29 06:31:12.834  5801  5801 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 06:31:12.834  5801  5801 D BluetoothMapService: STATE_ON
,09-29 06:31:12.836  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:12.836  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 06:31:12.837  5801  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:31:12.838  5738  5738 D LocalBluetoothProfileManager: Adding local A2DP profile
09-29 06:31:12.838  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:12.839  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:12.840  5801  5936 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 06:31:12.840  5801  5936 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 06:31:12.841  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:12.844  5738  5738 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-29 06:31:12.851  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 06:31:12.853  5738  5738 D BluetoothA2dp: Proxy object connected
,09-29 06:31:12.859  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 06:31:12.859  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-29 06:31:12.859  5801  5801 D ObexServerSockets0: prepareForNewConnect()
,09-29 06:31:12.864  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 06:31:12.872  3183  3183 D BluetoothPbap: Proxy object connected
,09-29 06:31:12.872  3183  3183 D PbapServerProfile: Bluetooth service connected
09-29 06:31:12.873  5738  5738 D BluetoothPbap: Proxy object connected
09-29 06:31:12.873  5738  5738 D PbapServerProfile: Bluetooth service connected
,09-29 06:31:12.883  5801  5940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 06:31:12.900  5801  5944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 06:31:12.901  5801  5944 I BtOppRfcommListener: Accept thread started.
,09-29 06:31:12.920   928   928 D BluetoothHeadset: Proxy object connected
,09-29 06:31:12.920   928   928 D BluetoothHeadset: Proxy object connected
,09-29 06:31:12.920   928   928 D BluetoothHeadset: Proxy object connected
09-29 06:31:12.921  3863  4066 D BluetoothHeadset: Proxy object connected
09-29 06:31:12.921  3183  3195 D BluetoothHeadset: Proxy object connected
09-29 06:31:12.921  3183  3183 D HeadsetProfile: Bluetooth service connected
09-29 06:31:12.921   928   945 D BluetoothHeadset: Proxy object connected
,09-29 06:31:12.923   928   945 D BluetoothHeadset: Proxy object connected
09-29 06:31:12.923  3183  4031 D BluetoothHeadset: Proxy object connected
09-29 06:31:12.923  3183  3183 D HeadsetProfile: Bluetooth service connected
09-29 06:31:12.925   928   945 D BluetoothHeadset: Proxy object connected
,09-29 06:31:12.948  5738  5752 D BluetoothHeadset: Proxy object connected
,09-29 06:31:12.949  5738  5738 D HeadsetProfile: Bluetooth service connected
,09-29 06:31:14.470   928  3029 D ConnectivityService: handlePromptUnvalidated 101
,09-29 06:31:16.403  5801  5908 D BluetoothAdapterState: Current state: ON, message: 23
09-29 06:31:16.403  5801  5908 D BluetoothAdapterProperties: Setting state to 13
09-29 06:31:16.403  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-29 06:31:16.404  5801  5908 D BluetoothAdapterProperties: onBluetoothDisable()
09-29 06:31:16.406  5801  5908 I BluetoothAdapterState: Entering PendingCommandState
,09-29 06:31:16.414  5801  5801 D BluetoothMapService: onReceive
09-29 06:31:16.414  5801  5801 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 06:31:16.415  5801  5801 D BluetoothMapService: STATE_TURNING_OFF
09-29 06:31:16.417  5801  5912 D BluetoothAdapterProperties: Scan Mode:20
,09-29 06:31:16.418  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 06:31:16.418  5801  5801 D BluetoothMapService: MAP Service closeService in
09-29 06:31:16.418  5801  5801 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 06:31:16.418  5801  5801 D ObexServerSockets0: shutdown(block = true)
09-29 06:31:16.419  5801  5933 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-29 06:31:16.422  5801  5801 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 06:31:16.422  5801  5801 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 06:31:16.422  5801  5935 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 06:31:16.422  5801  5921 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 06:31:16.423  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 06:31:16.423  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:16.423  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:16.424  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:16.424  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:16.426  5801  5801 I BtOppRfcommListener: stopping Accept Thread
09-29 06:31:16.427  5801  5944 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-29 06:31:16.427  5801  5944 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 06:31:16.428  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:16.428  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:16.429  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:16.430  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:16.433  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:16.433  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:16.434  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 06:31:16.434  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:16.434  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-29 06:31:16.437  5801  5801 D HeadsetService: Received stop request...Stopping profile...
,09-29 06:31:16.439  5738  5752 D BluetoothHeadset: Proxy object disconnected
,09-29 06:31:16.439   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 06:31:16.440   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 06:31:16.440   928   928 D BluetoothHeadset: Proxy object disconnected
09-29 06:31:16.440  3863  3898 D BluetoothHeadset: Proxy object disconnected
09-29 06:31:16.441  5738  5738 D HeadsetProfile: Bluetooth service disconnected
09-29 06:31:16.442  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:16.442  3183  3195 D BluetoothHeadset: Proxy object disconnected
09-29 06:31:16.443  3183  3183 D HeadsetProfile: Bluetooth service disconnected
09-29 06:31:16.444  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:16.445  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 06:31:16.446  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:16.449  5801  5801 D A2dpService: Received stop request...Stopping profile...
,09-29 06:31:16.449  5801  5928 D A2dpStateMachine: Exit Disconnected: -1
09-29 06:31:16.450   928   928 D BluetoothA2dp: Proxy object disconnected
09-29 06:31:16.451  5738  5738 D BluetoothA2dp: Proxy object disconnected
09-29 06:31:16.451  3183  3183 D BluetoothA2dp: Proxy object disconnected
09-29 06:31:16.451  5801  5801 D HidService: Received stop request...Stopping profile...
09-29 06:31:16.451  5801  5801 D HidService: Stopping Bluetooth HidService
09-29 06:31:16.452  3183  3183 D BluetoothInputDevice: Proxy object disconnected
09-29 06:31:16.452  3183  3183 D HidProfile: Bluetooth service disconnected
09-29 06:31:16.452  5738  5738 D BluetoothInputDevice: Proxy object disconnected
09-29 06:31:16.452  5738  5738 D HidProfile: Bluetooth service disconnected
09-29 06:31:16.452  5801  5801 D HealthService: Received stop request...Stopping profile...
09-29 06:31:16.454  5801  5801 D PanService: Received stop request...Stopping profile...
09-29 06:31:16.454  3183  3183 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 06:31:16.454  3183  3183 D PanProfile: Bluetooth service disconnected
09-29 06:31:16.455  5738  5738 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 06:31:16.455  5738  5738 D PanProfile: Bluetooth service disconnected
09-29 06:31:16.455  5801  5801 D BluetoothMapService: Received stop request...Stopping profile...
09-29 06:31:16.455  5801  5801 D BluetoothMapService: stop()
09-29 06:31:16.456  5801  5801 D BluetoothMapAppObserver: deinitObservers()
09-29 06:31:16.456  5801  5801 D BluetoothMapAppObserver: removeReceiver()
,09-29 06:31:16.457  3183  3183 D BluetoothMap: Proxy object disconnected
09-29 06:31:16.457  3183  3183 D MapProfile: Bluetooth service disconnected
,09-29 06:31:16.458  5801  5801 V BluetoothAdapterState: isTurningOff()=true
09-29 06:31:16.458  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.458  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.458  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:16.458  5738  5738 D BluetoothMap: Proxy object disconnected
09-29 06:31:16.458  5738  5738 D MapProfile: Bluetooth service disconnected
,09-29 06:31:16.459  5801  5801 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 06:31:16.460  5801  5801 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 06:31:16.460  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 06:31:16.460  5801  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:31:16.460  5801  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:31:16.460  5801  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 06:31:16.461  5801  5801 D SapService: Received stop request...Stopping profile...
09-29 06:31:16.461  5801  5801 V SapService: stop()
09-29 06:31:16.462  5801  5912 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-29 06:31:16.463  3183  3183 D BluetoothPbap: Proxy object disconnected
09-29 06:31:16.464  3183  3183 D PbapServerProfile: Bluetooth service disconnected
,09-29 06:31:16.464  5801  5801 V BluetoothAdapterState: isTurningOff()=true
,09-29 06:31:16.464  5801  5801 V BluetoothAdapterState: isTurningOn()=false
,09-29 06:31:16.464  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 06:31:16.464  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:31:16.466  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-29 06:31:16.466  5801  5801 V BluetoothAdapterState: isTurningOff()=true
09-29 06:31:16.466  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.466  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.466  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:16.466  5801  5801 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 06:31:16.466  5801  5801 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 06:31:16.467  5801  5801 V BluetoothAdapterState: isTurningOff()=true
09-29 06:31:16.467  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.467  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.467  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:16.467  5801  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:31:16.467  5801  5801 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-29 06:31:16.467  5801  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:31:16.467  5738  5738 D BluetoothPbap: Proxy object disconnected
09-29 06:31:16.467  5738  5738 D PbapServerProfile: Bluetooth service disconnected
09-29 06:31:16.467  5801  5919 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 06:31:16.467  5801  5919 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 06:31:16.467  5801  5801 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 06:31:16.467  5801  5919 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 06:31:16.467  5801  5919 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-29 06:31:16.467  5801  5801 V BluetoothAdapterState: isTurningOff()=true
09-29 06:31:16.467  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.468  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.468  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:16.468  5801  5801 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 06:31:16.468  5801  5801 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-29 06:31:16.468  5801  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 06:31:16.469  5801  5912 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 06:31:16.469  5801  5801 D BluetoothMapService: MAP Service closeService in
,09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isTurningOff()=true
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:16.469  5801  5801 D BluetoothMapService: cleanup()
09-29 06:31:16.469  5801  5801 D BluetoothMapService: MAP Service closeService in
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isTurningOff()=true
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.469  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:16.470  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-29 06:31:16.470  5801  5908 D BluetoothAdapterProperties: Setting state to 15
09-29 06:31:16.470  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 06:31:16.470  5801  5908 I BluetoothAdapterState: Entering BleOnState
09-29 06:31:16.471  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 06:31:16.472  3183  3195 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 06:31:16.473  5738  5752 D BluetoothMap: onBluetoothStateChange: up=false
,09-29 06:31:16.474  5738  5749 D BluetoothPan: onBluetoothStateChange on: false
09-29 06:31:16.474  3863  4067 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:31:16.474   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 06:31:16.475  3183  3198 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 06:31:16.475   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:31:16.475  5738  5752 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 06:31:16.476   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:31:16.476  3183  4031 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:31:16.476  3183  3195 D BluetoothMap: onBluetoothStateChange: up=false
09-29 06:31:16.477   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:31:16.477  3183  3198 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-29 06:31:16.477  5738  5749 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 06:31:16.478  5738  5752 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 06:31:16.478  3183  4031 D BluetoothPan: onBluetoothStateChange on: false
09-29 06:31:16.479  5801  5908 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 06:31:16.479  5801  5908 D BluetoothAdapterProperties: Setting state to 16
09-29 06:31:16.479  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 06:31:16.480  5801  5908 D BluetoothAdapterProperties: onBleDisable
09-29 06:31:16.480  5801  5908 I BluetoothAdapterState: Entering PendingCommandState
09-29 06:31:16.481  5801  5909 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 06:31:16.481  5801  5912 D BluetoothAdapterProperties: Scan Mode:20
09-29 06:31:16.483  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 06:31:16.483  5801  5919 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 06:31:16.483  5801  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 06:31:16.483  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:16.485  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:16.486  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:16.489  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:16.490  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 06:31:16.490  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:16.492  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:16.496  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-29 06:31:16.701  5801  5912 I bt_hci  : shut_down
,09-29 06:31:16.704  5801  5916 D bt_hwcfg: hw_epilog_process
09-29 06:31:16.706  5801  5916 I bt_vendor: low_power_mode_cb
,09-29 06:31:16.709  5801  5916 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-29 06:31:16.709  5801  5916 I bt_vendor: epilog_cb
09-29 06:31:16.709  5801  5916 I bt_hci  : epilog_finished_callback
,09-29 06:31:16.714  5801  5912 I bt_hci_h4: hal_close
,09-29 06:31:16.716  5801  5912 I bt_userial_vendor: device fd = 54 close
,09-29 06:31:16.836  5801  5909 D bt_stack_manager: event_shut_down_stack finished.
,09-29 06:31:16.837  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 06:31:16.840  5801  5908 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-29 06:31:16.841  5801  5801 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 06:31:16.843  5801  5801 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 06:31:16.843  5801  5801 D BtGatt.GattService: stop()
09-29 06:31:16.843  5801  5801 D BtGatt.AdvertiseManager: advertise clients cleared
,09-29 06:31:16.847  5801  5801 V BluetoothAdapterState: isTurningOff()=false
,09-29 06:31:16.848  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:16.848  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:16.848  5801  5801 V BluetoothAdapterState: isBleTurningOff()=true
09-29 06:31:16.848  5801  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-29 06:31:16.850  5801  5908 D BluetoothAdapterProperties: Setting state to 10
09-29 06:31:16.850  5801  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-29 06:31:16.851  5801  5908 I BluetoothAdapterState: Entering OffState
09-29 06:31:16.852   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-29 06:31:16.861  5801  5801 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 06:31:16.861  5801  5801 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 06:31:16.861  5801  5801 I BluetoothServiceJni: cleanupNative: return from cleanup
09-29 06:31:16.863  5801  5909 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-29 06:31:16.868  5801  5801 I art     : System.exit called, status: 0
,09-29 06:31:16.868  5801  5801 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 06:31:16.894   928  3624 I ActivityManager: Process com.android.bluetooth (pid 5801) has died
,09-29 06:31:21.402  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:21.403  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:31:21.410  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:31:21.410  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f032b6 removed from the list
,09-29 06:31:21.410  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:31:21.410  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:31:21.411  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:21.413  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:21.413  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0e5f24 added. We now have 4 listener(s)
,09-29 06:31:21.414  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:21.416  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:21.416  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0e5f24 removed from the list
,09-29 06:31:21.416  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:21.416  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:21.417  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:21.418  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 06:31:21.420  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f3aa8d added. We now have 4 listener(s)
09-29 06:31:21.420  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:31:26.433  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:26.468   928   945 I ActivityManager: Start proc 5953:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 06:31:26.556  5953  5953 D AdapterServiceConfig: Adding HeadsetService
09-29 06:31:26.557  5953  5953 D AdapterServiceConfig: Adding A2dpService
09-29 06:31:26.557  5953  5953 D AdapterServiceConfig: Adding HidService
,09-29 06:31:26.557  5953  5953 D AdapterServiceConfig: Adding HealthService
09-29 06:31:26.557  5953  5953 D AdapterServiceConfig: Adding PanService
09-29 06:31:26.557  5953  5953 D AdapterServiceConfig: Adding GattService
09-29 06:31:26.557  5953  5953 D AdapterServiceConfig: Adding BluetoothMapService
09-29 06:31:26.558  5953  5953 D AdapterServiceConfig: Adding SapService
,09-29 06:31:26.569   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a45f29d:true
,09-29 06:31:26.569  5953  5953 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 06:31:26.573  5953  5953 I bt_bluedroid: init
,09-29 06:31:26.574  5953  5965 I BluetoothAdapterState: Entering OffState
,09-29 06:31:26.575  5953  5966 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-29 06:31:26.576  5953  5966 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 06:31:26.576  5953  5966 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 06:31:26.576  5953  5966 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-29 06:31:26.577  5953  5953 I bt_bluedroid: get_profile_interface socket
,09-29 06:31:26.578  5953  5969 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 06:31:26.579  5953  5953 I bt_bluedroid: get_profile_interface sdp
09-29 06:31:26.580  5953  5969 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 06:31:26.585  5953  5963 I bt_bluedroid: config_hci_snoop_log
09-29 06:31:26.586   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 06:31:26.591  5953  5965 D BluetoothAdapterState: Current state: OFF, message: 0
09-29 06:31:26.592  5953  5965 D BluetoothAdapterProperties: Setting state to 14
09-29 06:31:26.592  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 06:31:26.594  5953  5965 D BluetoothBondStateMachine: make
,09-29 06:31:26.596  5953  5970 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 06:31:26.599  5953  5965 I BluetoothAdapterState: Entering PendingCommandState
,09-29 06:31:26.601  5953  5953 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 06:31:26.603  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:26.604  5953  5953 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 06:31:26.605  5953  5953 D BtGatt.GattService: Received start request. Starting profile...
09-29 06:31:26.605  5953  5953 D BtGatt.GattService: start()
09-29 06:31:26.605  5953  5953 I bt_bluedroid: get_profile_interface gatt
09-29 06:31:26.606  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:26.606  5953  5953 D BtGatt.AdvertiseManager: advertise manager created
,09-29 06:31:26.613  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:26.613  5953  5953 V BluetoothAdapterState: isTurningOn()=false
09-29 06:31:26.613  5953  5953 V BluetoothAdapterState: isBleTurningOn()=true
,09-29 06:31:26.613  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:26.614  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 06:31:26.615  5953  5965 I bt_bluedroid: bt_bluedroid
,09-29 06:31:26.616  5953  5966 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-29 06:31:26.616  5953  5966 I bt_hci  : start_up
,09-29 06:31:26.624  5953  5966 I bt_vendor: alloc value 0xf3b75871
,09-29 06:31:26.624  5953  5966 I bt_vendor: init
09-29 06:31:26.624  5953  5966 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 06:31:26.624  5953  5966 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 06:31:26.738  5953  5966 D bt_hci  : start_up starting async portion
,09-29 06:31:26.739  5953  5973 I bt_hci  : event_finish_startup
09-29 06:31:26.739  5953  5973 I bt_hci_h4: hal_open
09-29 06:31:26.740  5953  5973 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 06:31:26.737  5974  5974 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 06:31:26.742  5953  5973 I bt_userial_vendor: device fd = 54 open
,09-29 06:31:26.760  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 06:31:26.764  5953  5973 D bt_hwcfg: Chipset BCM4358A3
,09-29 06:31:26.764  5953  5973 D bt_hwcfg: Target name = [BCM4358A3]
09-29 06:31:26.764  5953  5973 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 06:31:27.554  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 06:31:27.555  5953  5973 D bt_hwcfg: Settlement delay -- 100 ms
09-29 06:31:27.555  5953  5973 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 06:31:27.692  5953  5973 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-29 06:31:27.693  5953  5973 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 06:31:27.695  5953  5973 I bt_hwcfg: vendor lib fwcfg completed
,09-29 06:31:27.695  5953  5973 I bt_vendor: firmware callback
09-29 06:31:27.695  5953  5973 I bt_hci  : firmware_config_callback
,09-29 06:31:27.707  5953  5976 I bt_btu  : btu_task pending for preload complete event
,09-29 06:31:27.707  5953  5976 I bt_btu_task: Bluetooth chip preload is complete
,09-29 06:31:27.707  5953  5976 I bt_btu  : btu_task received preload complete event
,09-29 06:31:27.716  5953  5976 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 06:31:27.716  5953  5976 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 06:31:27.716  5953  5976 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 06:31:27.716  5953  5976 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 06:31:27.716  5953  5976 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-29 06:31:27.716  5953  5976 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_SDP
,09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 06:31:27.717  5953  5976 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 06:31:27.807  5953  5976 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3af3549
,09-29 06:31:27.807  5953  5976 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3af3549 
,09-29 06:31:27.829  5953  5969 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 06:31:27.831  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 06:31:27.832  5953  5969 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 06:31:27.834  5953  5969 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 06:31:27.836  5953  5969 D BluetoothAdapterProperties: Scan Mode:20
,09-29 06:31:27.836  5953  5969 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 06:31:27.837  5953  5969 D bt_hci  : do_postload posting postload work item
09-29 06:31:27.837  5953  5973 I bt_hci  : event_postload
09-29 06:31:27.837  5953  5973 I bt_vendor: sco_config_cb
09-29 06:31:27.837  5953  5973 I bt_hci  : sco_config_callback postload finished.
,09-29 06:31:27.841  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:27.843  5953  5969 D bt_bte_conf: Device ID record 1 : primary
09-29 06:31:27.843  5953  5969 D bt_bte_conf:   vendorId            = 000f
09-29 06:31:27.844  5953  5969 D bt_bte_conf:   vendorIdSource      = 0001
09-29 06:31:27.844  5953  5969 D bt_bte_conf:   product             = 1200
09-29 06:31:27.844  5953  5969 D bt_bte_conf:   version             = 1436
09-29 06:31:27.844  5953  5969 D bt_bte_conf:   clientExecutableURL = 
09-29 06:31:27.844  5953  5969 D bt_bte_conf:   serviceDescription  = 
09-29 06:31:27.844  5953  5969 D bt_bte_conf:   documentationURL    = 
09-29 06:31:27.844  5953  5969 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-29 06:31:27.844  5953  5966 D bt_stack_manager: event_start_up_stack finished
,09-29 06:31:27.845  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 06:31:27.846  5953  5965 D BluetoothAdapterProperties: Setting state to 15
09-29 06:31:27.846  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 06:31:27.850  5953  5965 I BluetoothAdapterState: Entering BleOnState
09-29 06:31:27.844  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:27.865  5953  5965 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 06:31:27.865  5953  5965 D BluetoothAdapterProperties: Setting state to 11
09-29 06:31:27.865  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-29 06:31:27.866  5953  5973 I bt_vendor: low_power_mode_cb
,09-29 06:31:27.874  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:27.876  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:27.875  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:27.879  5953  5953 D HeadsetService: Received start request. Starting profile...
09-29 06:31:27.881  5953  5953 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 06:31:27.881  5953  5953 D HeadsetStateMachine: make
09-29 06:31:27.883  5953  5965 I BluetoothAdapterState: Entering PendingCommandState
,09-29 06:31:27.890  5953  5953 D HeadsetStateMachine: max_hf_connections = 1
,09-29 06:31:27.890  5953  5953 I bt_bluedroid: get_profile_interface handsfree
,09-29 06:31:27.891  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 06:31:27.891  5953  5969 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-29 06:31:27.893  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:27.894  5953  5953 D A2dpService: Received start request. Starting profile...
,09-29 06:31:27.894  5953  5953 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 06:31:27.895  5953  5953 I bt_bluedroid: get_profile_interface avrcp
,09-29 06:31:27.901  5953  5953 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 06:31:27.901  5953  5953 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 06:31:27.901  5953  5953 D A2dpStateMachine: make
09-29 06:31:27.903  5953  5953 I bt_bluedroid: get_profile_interface a2dp
09-29 06:31:27.903  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-29 06:31:27.905  5953  5984 D A2dpStateMachine: Enter Disconnected: -2
09-29 06:31:27.905  5953  5953 I BluetoothHidServiceJni: classInitNative: succeeds
,09-29 06:31:27.906  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:27.907  5953  5953 D HidService: Received start request. Starting profile...
09-29 06:31:27.907  5953  5953 I bt_bluedroid: get_profile_interface hidhost
,09-29 06:31:27.907  5953  5953 D HidService: setHidService(): set to: null
09-29 06:31:27.907  5953  5969 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ad456d
09-29 06:31:27.908  5953  5969 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 06:31:27.909  5953  5953 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 06:31:27.910  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:27.911  5953  5953 D HealthService: Received start request. Starting profile...
09-29 06:31:27.911  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 06:31:27.913  5953  5953 I bt_bluedroid: get_profile_interface health
,09-29 06:31:27.914  5953  5953 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 06:31:27.914  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:27.915  5953  5953 D PanService: Received start request. Starting profile...
09-29 06:31:27.915  5953  5953 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 06:31:27.915  5953  5953 I bt_bluedroid: get_profile_interface pan
09-29 06:31:27.916  5953  5969 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-29 06:31:27.918  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:27.918  5953  5953 D BluetoothMapService: Received start request. Starting profile...
09-29 06:31:27.918  5953  5953 D BluetoothMapService: start()
09-29 06:31:27.921  5953  5953 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-29 06:31:27.922  5953  5953 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 06:31:27.922  5953  5953 D BluetoothMapAppObserver: createReceiver()
,09-29 06:31:27.923  5953  5953 D BluetoothMapAppObserver: initObservers()
09-29 06:31:27.923  5953  5953 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 06:31:27.930  5953  5953 V SapService: SapBinder()
,09-29 06:31:27.930  5953  5953 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
09-29 06:31:27.931  5953  5953 D SapService: Received start request. Starting profile...
09-29 06:31:27.931  5953  5953 V SapService: start()
,09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:27.934  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.935  5953  5982 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:27.935  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:27.936  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:27.937  5953  5953 V BluetoothAdapterState: isTurningOff()=false
09-29 06:31:27.937  5953  5953 V BluetoothAdapterState: isTurningOn()=true
09-29 06:31:27.937  5953  5953 V BluetoothAdapterState: isBleTurningOn()=false
09-29 06:31:27.937  5953  5953 V BluetoothAdapterState: isBleTurningOff()=false
09-29 06:31:27.937  5953  5965 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 06:31:27.937  5953  5965 D BluetoothAdapterProperties: ScanMode =  20
09-29 06:31:27.937  5953  5965 D BluetoothAdapterProperties: State =  11
09-29 06:31:27.938  5953  5965 D BluetoothAdapterProperties: Setting state to 12
,09-29 06:31:27.938  5953  5965 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 06:31:27.938  5953  5965 I BluetoothAdapterState: Entering OnState
09-29 06:31:27.938  5738  5752 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 06:31:27.939  5953  5969 D BluetoothAdapterProperties: Scan Mode:21
09-29 06:31:27.939  5953  5969 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 06:31:27.939  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-29 06:31:27.940  3183  4031 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 06:31:27.942  5738  5752 D BluetoothMap: onBluetoothStateChange: up=true
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:27.943  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:27.944  5738  5749 D BluetoothPan: onBluetoothStateChange on: true
09-29 06:31:27.945  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:27.947  3863  4067 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:27.947   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:27.948  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 06:31:27.948  3183  3195 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 06:31:27.949  5953  5953 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 06:31:27.949  5953  5953 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 06:31:27.950  3183  3183 D BluetoothInputDevice: Proxy object connected
09-29 06:31:27.950  5738  5738 D BluetoothInputDevice: Proxy object connected
09-29 06:31:27.950  5738  5738 D HidProfile: Bluetooth service connected
09-29 06:31:27.950  3183  3183 D HidProfile: Bluetooth service connected
09-29 06:31:27.950  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:27.950   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:27.950  5738  5749 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 06:31:27.951  5953  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:31:27.951   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:27.952  3183  4031 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:27.952  3183  3195 D BluetoothMap: onBluetoothStateChange: up=true
09-29 06:31:27.952  5953  5953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:31:27.953   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:27.954  3183  3183 D BluetoothMap: Proxy object connected
09-29 06:31:27.954  3183  3198 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 06:31:27.954  3183  3183 D MapProfile: Bluetooth service connected
09-29 06:31:27.954  3183  3183 D BluetoothMap: getConnectedDevices()
09-29 06:31:27.954  5953  5953 D ObexServerSockets: Succeed to create listening sockets 
09-29 06:31:27.954  5953  5953 D ObexServerSockets0: startAccept()
09-29 06:31:27.954  5953  5953 D ObexServerSockets0: prepareForNewConnect()
09-29 06:31:27.955  5738  5752 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 06:31:27.958  5953  5953 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 06:31:27.958  5953  5953 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 06:31:27.958  5738  5749 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 06:31:27.959  5953  5991 D ObexServerSockets0: Accepting socket connection...
09-29 06:31:27.960  3183  3195 D BluetoothPan: onBluetoothStateChange on: true
09-29 06:31:27.960  5953  5990 D ObexServerSockets0: Accepting socket connection...
,09-29 06:31:27.960  3183  3183 D BluetoothA2dp: Proxy object connected
09-29 06:31:27.960   928   928 D BluetoothA2dp: Proxy object connected
09-29 06:31:27.962  3183  3183 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 06:31:27.962  3183  3183 D PanProfile: Bluetooth service connected
09-29 06:31:27.963  5738  5738 D BluetoothMap: Proxy object connected
09-29 06:31:27.963  5738  5738 D MapProfile: Bluetooth service connected
09-29 06:31:27.963  5738  5738 D BluetoothMap: getConnectedDevices()
09-29 06:31:27.963  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 06:31:27.964   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 06:31:27.965  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:27.966  5953  5953 D BluetoothMapService: onReceive
09-29 06:31:27.966  5953  5953 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 06:31:27.966  5953  5953 D BluetoothMapService: STATE_ON
09-29 06:31:27.967  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:27.967  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 06:31:27.967  5738  5738 D PanProfile: Bluetooth service connected
09-29 06:31:27.968  5738  5738 D BluetoothA2dp: Proxy object connected
09-29 06:31:27.969  5953  5995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 06:31:27.970  5953  5995 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 06:31:27.970  5953  5995 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-29 06:31:27.975  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 06:31:27.981  3630  3630 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 06:31:27.982  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-29 06:31:27.992  5738  5738 D BluetoothPbap: Proxy object connected
09-29 06:31:27.992  5738  5738 D PbapServerProfile: Bluetooth service connected
09-29 06:31:27.993  3183  3183 D BluetoothPbap: Proxy object connected
09-29 06:31:27.994  5953  5953 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 06:31:27.994  5953  5953 D ObexServerSockets0: prepareForNewConnect()
09-29 06:31:27.994  3183  3183 D PbapServerProfile: Bluetooth service connected
,09-29 06:31:27.998  5953  5999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 06:31:28.012  5953  6003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 06:31:28.014  5953  6003 I BtOppRfcommListener: Accept thread started.
,09-29 06:31:28.051  5738  5989 D BluetoothHeadset: Proxy object connected
,09-29 06:31:28.051   928   945 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.051   928   945 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.051   928   928 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.051   928   928 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.051   928   928 D BluetoothHeadset: Proxy object connected
,09-29 06:31:28.051  3863  3889 D BluetoothHeadset: Proxy object connected
,09-29 06:31:28.052  3183  4031 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.052  3183  3195 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.053  5738  5738 D HeadsetProfile: Bluetooth service connected
09-29 06:31:28.053  3183  3183 D HeadsetProfile: Bluetooth service connected
09-29 06:31:28.053   928   945 D BluetoothHeadset: Proxy object connected
09-29 06:31:28.056  3183  3183 D HeadsetProfile: Bluetooth service connected
,09-29 06:31:28.061  5738  5749 D BluetoothHeadset: Proxy object connected
,09-29 06:31:28.061  5738  5738 D HeadsetProfile: Bluetooth service connected
,09-29 06:31:31.133   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:31.453  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:31.461  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:31.462  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:31:31.462  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f3aa8d removed from the list
09-29 06:31:31.463  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:31.463  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:31.463  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:31.465  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:31.465  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c4c442 added. We now have 4 listener(s)
09-29 06:31:31.465  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:31:31.470   928  3932 D WifiService: setWifiEnabled: false pid=5684, uid=10077
09-29 06:31:31.471   928  3932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 06:31:32.137   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:33.138   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:34.143   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:35.147   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:31:36.150   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-29 06:31:36.483  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:36.484   928  3208 D WifiService: setWifiEnabled: true pid=5684, uid=10077
09-29 06:31:36.484   928  3208 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 06:31:36.497   510   927 D SoftapController: Softap fwReload - Ok
,09-29 06:31:36.503   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:36.504   510   927 D CommandListener: Trying to bring down wlan0
09-29 06:31:36.506   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-29 06:31:36.512   928  3027 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 06:31:37.303   928  3027 D wifi    : set interface wlan0 flags (UP)
09-29 06:31:37.304   928  3027 I WifiHAL : Initializing wifi
09-29 06:31:37.304   928  3027 I WifiHAL : Creating socket
,09-29 06:31:37.311   928  3027 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-29 06:31:37.311   928  3027 D wifi    : Did set static halHandle = 0x7f76916540
09-29 06:31:37.312   928  3027 D wifi    : halHandle = 0x7f76916540, mVM = 0x7f92f4d140, mCls = 0x15e2
09-29 06:31:37.313   928  3027 D wifi    : array field set
,09-29 06:31:37.314   928  3027 I WifiNative-HAL: interface[0] = wlan0
09-29 06:31:37.316   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-29 06:31:37.320   928  6008 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547450086720
09-29 06:31:37.320   928  6008 D wifi    : waitForHalEvents called, vm = 0x7f92f4d140, obj = 0x15e2, env = 0x7f76e3d440
,09-29 06:31:37.381  6009  6009 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 06:31:37.403  6009  6009 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 06:31:37.421   928  3027 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 06:31:37.428  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:37.429  6009  6009 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-29 06:31:37.429  6009  6009 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
09-29 06:31:37.432  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:37.448   928  3027 D WifiConfigStore: Loading config and enabling all networks 
,09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:37.451  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:37.455  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:37.458  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:37.460  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 06:31:37.466   928  3027 D WifiConfigStore: loaded 0 passpoint configs
09-29 06:31:37.466   928  3027 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-29 06:31:37.467   928  3027 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-29 06:31:37.468   928  3027 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-29 06:31:37.468   928  3027 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 06:31:37.469   928  3027 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 06:31:37.469   928  3027 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 06:31:37.469   928  3027 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 06:31:37.472   928  3027 D WifiNative-HAL: Setting external_sim to 1
09-29 06:31:37.472  5068  5068 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 06:31:37.472   928  3027 D wifi    : setting dfs flag to true, 0x7f7a3ba100
09-29 06:31:37.473   928  3027 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 06:31:37.473   928  3027 D wifi    : setting scan oui 0x7f7a3ba100
09-29 06:31:37.473   928  3027 D WifiHAL : Sending mac address OUI
,09-29 06:31:37.477   928  3027 E native  : do suspend false
,09-29 06:31:37.490   928  3027 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-29 06:31:37.490   928   928 D RttService: SCAN_AVAILABLE : 3
09-29 06:31:37.490   510   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-29 06:31:37.490   928  3136 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-29 06:31:37.491   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:37.496   928  3016 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-29 06:31:37.496   928  3016 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 06:31:37.505   928  3016 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 06:31:37.509   928  3016 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-29 06:31:37.509   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304660 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-29 06:31:40.700  6009  6009 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:40.711  6009  6009 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:40.718  6009  6009 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:40.725  6009  6009 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 06:31:40.758   928  3027 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 06:31:40.760   928  3027 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 06:31:40.760   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:31:40.778   928  3027 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 06:31:40.815   928  3027 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 06:31:40.818  6009  6009 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 06:31:41.333  6009  6009 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 06:31:41.426  6009  6009 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 06:31:41.427  6009  6009 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 06:31:41.442   928  3027 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 06:31:41.442   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-29 06:31:41.444   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 06:31:41.461   928  3027 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 06:31:41.475   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:41.481   928  3027 D WifiStateMachine: Start Dhcp Watchdog 3
,09-29 06:31:41.487   928  6014 D DhcpClient: Receive thread started
,09-29 06:31:41.493   928  3027 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-29 06:31:41.493   928  3029 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-29 06:31:41.493   928  3029 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 06:31:41.502  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 06:31:41.505  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 06:31:41.506  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:41.506  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c4c442 removed from the list
09-29 06:31:41.506  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:41.506  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:41.506  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:31:41.510  5684  6015 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-29 06:31:41.510  5684  6015 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 06:31:41.587   928  3027 E native  : do suspend false
,09-29 06:31:41.611   928  6013 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 06:31:41.627   928  6014 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-29 06:31:41.628   928  6013 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-29 06:31:41.630   928  6013 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 06:31:41.644   928  6014 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-29 06:31:41.645   928  6013 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-29 06:31:41.650   510   927 D CommandListener: Setting iface cfg
,09-29 06:31:41.655   928  3027 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 06:31:41.663   928  6013 D DhcpClient: Scheduling renewal in 86399s
,09-29 06:31:41.674   928  3027 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-29 06:31:41.676   928  3027 D WifiConfigStore: No blacklist allowed without epno enabled
09-29 06:31:41.676   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-29 06:31:41.678   928  3029 D ConnectivityService: Adding iface wlan0 to network 102
,09-29 06:31:41.684   928  3027 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 06:31:41.722   928  3029 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-29 06:31:41.722   928  3029 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-29 06:31:41.724   928  3029 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-29 06:31:41.725   928  3029 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-29 06:31:41.727   928  3029 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-29 06:31:41.743   928  3029 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 06:31:41.750   928  3029 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-29 06:31:41.750   928  3029 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-29 06:31:41.750   928  3029 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-29 06:31:41.750   928  3029 D ConnectivityService:    accepting network in place of null
09-29 06:31:41.750   928  3027 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 06:31:41.750   928  3027 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 06:31:41.751   928  3029 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 06:31:41.771   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 06:31:41.792   928  6012 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 06:31:41.793   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 06:31:41.797   928  3029 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-29 06:31:41.797   928  3029 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 06:31:41.798  3827  3965 W QCNEJ   : |CORE| network available: 102
09-29 06:31:41.799   928  3029 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-29 06:31:41.799   928   945 D Tethering: MasterInitialState.processMessage what=3
09-29 06:31:41.803  3827  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-29 06:31:41.804  3827  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-29 06:31:41.805  3827  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:41.811  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:31:41.813  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:31:41.816  5093  5116 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 06:31:41.816  5093  5116 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 06:31:41.816  5093  5116 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-29 06:31:41.816  5093  5116 E SarControlService: no key has been found,reset the power
09-29 06:31:41.817  5093  5130 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 06:31:41.817  5093  5130 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 06:31:41.817  5093  5130 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 06:31:41.817  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 06:31:41.817  5118  5118 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:41.818  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:31:41.818  5093  5130 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-29 06:31:41.821  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:31:41.818  5093  5130 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-29 06:31:41.824  3791  3791 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 06:31:41.822  5093  5130 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 06:31:41.827  5118  5132 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5238524 HexData = [00000000ec03000000000000ffffffff]
09-29 06:31:41.827  5118  5132 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-29 06:31:41.827  5118  5132 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-29 06:31:41.827  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 06:31:41.828  5118  5118 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 06:31:41.828  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 06:31:41.828  5093  5104 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 06:31:41.832  5118  5132 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@5238524 HexData = [00000000ed03000000000000ffffffff]
09-29 06:31:41.832  5118  5132 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 06:31:41.832  5118  5132 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-29 06:31:41.833  5118  5118 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 06:31:41.833  5093  5103 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 06:31:41.834  3791  3791 D SystemUpdateService: onCreate
,09-29 06:31:41.837  3791  3791 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 06:31:41.848  3791  3791 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-29 06:31:41.853  3791  5449 I iu.UploadsManager: num queued entries: 0
09-29 06:31:41.853  3791  5449 I iu.UploadsManager: num updated entries: 0
,09-29 06:31:41.854  3791  5449 I iu.SyncManager: NEXT; no task
,09-29 06:31:41.857  3791  6025 I SystemUpdateService: active receiver: enabled
,09-29 06:31:41.861  3791  3791 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 06:31:41.862  3791  3791 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 06:31:41.864  5816  5816 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 06:31:41.868  5816  5816 D SprintDMHelper: simOperator: 
09-29 06:31:41.868  5816  5816 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 06:31:41.881   928  6011 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-29 06:31:41.907  3791  6025 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 06:31:41.914  3791  6025 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-29 06:31:41.914  3791  6025 I SystemUpdateService: now status is 0 (complete)
09-29 06:31:41.914  3791  6025 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 06:31:41.914  3791  6025 I SystemUpdateService: file has been verified
09-29 06:31:41.914  3791  6025 I SystemUpdateService: OTA package size = 21989297
,09-29 06:31:41.922  3791  6025 I SystemUpdateService: showing system update notification
,09-29 06:31:41.934  3791  3791 D SystemUpdateService: onDestroy
,09-29 06:31:41.936   928  6011 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 29 Sep 2016 10:31:41 GMT], X-Android-Received-Millis=[1475145101935], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475145101904]}
09-29 06:31:41.937   928  3029 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-29 06:31:41.937   928  3029 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-29 06:31:41.937   928  3029 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-29 06:31:41.938   928  3029 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 06:31:41.978  5068  6030 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-29 06:31:44.526   928  3029 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 06:31:44.536  5684  6015 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-29 06:31:44.536  5684  6037 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-29 06:31:44.537  5684  6037 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-29 06:31:44.537  5684  6015 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-29 06:31:44.539  5684  6015 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:44.539  5684  6037 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:44.540  5684  6015 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:44.541  5684  6037 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:44.543  5684  6039 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:44.543  5684  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:44.544  5684  6037 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-29 06:31:44.546  5684  6015 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 06:31:44.549  5684  6040 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:44.549  5684  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 06:31:44.550  5684  6041 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:44.550  5684  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:44.550  5684  6042 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:44.550  5684  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:44.550  5684  6041 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:44.550  5684  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:44.550  5684  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:44.550  5684  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:31:44.551  5684  6040 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
09-29 06:31:44.551  5684  6041 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 06:31:44.551  5684  6040 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:44.551  5684  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:44.551  5684  6041 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 06:31:44.551  5684  6040 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
09-29 06:31:44.552  5684  6040 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-29 06:31:44.552  5684  6040 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:44.552  5684  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:44.553  5684  6039 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:31:44.554  5684  6039 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:31:44.554  5684  6039 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:31:44.554  5684  6039 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-29 06:31:44.554  5684  6039 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:44.554  5684  6039 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-29 06:31:44.555  5684  6042 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:44.555  5684  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:44.555  5684  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:44.555  5684  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:44.555  5684  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:31:44.555  5684  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:44.556  5684  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:31:44.556  5684  6042 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:31:44.556  5684  6042 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:31:44.556  5684  6042 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 06:31:44.557  5684  6042 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-29 06:31:44.557  5684  6042 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:44.557  5684  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 06:31:47.520  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-29 06:31:47.522  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-29 06:31:47.534  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@196fd71 Bundle[{}]
,09-29 06:31:47.535  5684  5730 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-29 06:31:47.536  5684  5730 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-29 06:31:47.538  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-29 06:31:47.540  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-29 06:31:47.542  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-29 06:31:47.545  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-29 06:31:47.558  5684  5730 I System.out: Running OutgoingSocketThread
,09-29 06:31:47.561  5684  6043 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-29 06:31:47.562  5684  6043 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 06:31:49.756   928  3029 D ConnectivityService: handlePromptUnvalidated 102
,09-29 06:31:50.575  5684  6044 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-29 06:31:50.575  5684  6044 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 06:31:50.576  5684  6044 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:50.576  5684  6043 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-29 06:31:50.576  5684  6043 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 06:31:50.576  5684  6043 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:50.578  5684  6044 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 06:31:50.578  5684  6043 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 06:31:50.580  5684  6046 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:50.580  5684  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 06:31:50.581  5684  6047 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:50.581  5684  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:31:50.583  5684  6043 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-29 06:31:50.584  5684  6044 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-29 06:31:50.587  5684  6048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:50.587  5684  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:31:50.588  5684  6049 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:50.588  5684  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 06:31:50.588  5684  6048 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:50.588  5684  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:31:50.588  5684  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:50.588  5684  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:31:50.588  5684  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:31:50.588  5684  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:50.589  5684  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:31:50.589  5684  6048 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:31:50.589  5684  6048 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-29 06:31:50.589  5684  6048 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 06:31:50.590  5684  6048 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:50.590  5684  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 06:31:50.590  5684  6049 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:50.590  5684  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:50.590  5684  6047 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): Socket closed
09-29 06:31:50.590  5684  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:50.590  5684  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:50.590  5684  6047 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:50.590  5684  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-29 06:31:50.590  5684  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:31:50.590  5684  6046 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:50.590  5684  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:50.590  5684  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 06:31:50.591  5684  6047 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:31:50.591  5684  6047 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:50.591  5684  6049 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:31:50.591  5684  6046 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:31:50.591  5684  6047 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:50.591  5684  6047 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 06:31:50.591  5684  6046 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-29 06:31:50.591  5684  6049 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:31:50.591  5684  6046 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
,09-29 06:31:50.591  5684  6049 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:31:50.591  5684  6049 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 06:31:50.592  5684  6046 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 06:31:50.592  5684  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 06:31:50.592  5684  6049 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
09-29 06:31:50.592  5684  6049 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 06:31:50.592  5684  6049 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 06:31:52.514   928  3027 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-29 06:31:53.576  5684  5730 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
09-29 06:31:53.577  5684  5730 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-29 06:31:53.578  5684  5730 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-29 06:31:53.583  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.584  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59fdc53 added. We now have 3 listener(s)
,09-29 06:31:53.588  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.589  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 06:31:53.590  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.590  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.590  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5644990 added. We now have 4 listener(s)
09-29 06:31:53.590  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.591  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:31:53.598  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:53.607  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:31:53.610  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.611  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:31:53.611  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.611  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ee28e added. We now have 4 listener(s)
,09-29 06:31:53.614  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.614  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.614  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.614  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.614  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@841eaaf added. We now have 5 listener(s)
09-29 06:31:53.615  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.615  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:31:53.615  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:31:53.615  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:31:53.615  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.615  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:31:53.615  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.615  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.616  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.616  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59fdc53 removed from the list
09-29 06:31:53.616  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.616  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5644990 removed from the list
09-29 06:31:53.617  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:53.621  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:53.622  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 06:31:53.622  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.623  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.623  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.624  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.624  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.625  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.625  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5644990 not in the list
09-29 06:31:53.625  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.625  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.626  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.626  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.626  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:31:53.626  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@841eaaf removed from the list
09-29 06:31:53.627  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.627  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.627  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.627  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.627  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.627  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5ee28e removed from the list
09-29 06:31:53.628  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.628  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec6ebc added. We now have 3 listener(s)
09-29 06:31:53.630  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.630  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.630  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 06:31:53.630  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.630  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed09e45 added. We now have 4 listener(s)
09-29 06:31:53.630  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.632  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:31:53.636  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:53.641  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:31:53.644  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.644  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:31:53.644  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.645  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c82cb added. We now have 4 listener(s)
,09-29 06:31:53.646  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 06:31:53.647  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.647  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.647  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.647  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6fbaa8 added. We now have 5 listener(s)
09-29 06:31:53.647  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.647  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:31:53.647  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 06:31:53.647  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 06:31:53.647  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:31:53.647  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 06:31:53.648  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:53.651  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 06:31:53.651  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 06:31:53.651  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:53.655  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 06:31:53.656  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 06:31:53.656  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 06:31:53.660  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 06:31:53.660  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-29 06:31:53.660  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 06:31:53.661  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 06:31:53.661  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 06:31:53.661  5684  5730 D BluetoothAdapter: STATE_ON
,09-29 06:31:53.665  5953  5981 D BtGatt.GattService: registerClient() - UUID=7d2991f6-c437-44ee-a441-8e0904b00991
09-29 06:31:53.666  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=7d2991f6-c437-44ee-a441-8e0904b00991, clientIf=5
,09-29 06:31:53.667  5684  5695 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 06:31:53.668  5953  5993 D BtGatt.GattService: start scan with filters
,09-29 06:31:53.671  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 06:31:53.672  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 06:31:53.672  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:31:53.672  5953  5972 D BtGatt.ScanManager: handling starting scan
09-29 06:31:53.672  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 06:31:53.672  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 06:31:53.672  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 06:31:53.672  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 06:31:53.674  5953  5972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66c2c8a
,09-29 06:31:53.675  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:31:53.675  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 06:31:53.675  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:31:53.676  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 06:31:53.679  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-29 06:31:53.679  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 06:31:53.679  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-29 06:31:53.679  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.679  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 06:31:53.679  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.680  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 06:31:53.680  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 06:31:53.680  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:31:53.680  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:31:53.680  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-29 06:31:53.680  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 06:31:53.681  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:31:53.682  5953  5964 D BtGatt.GattService: stopScan() - queue size =1
09-29 06:31:53.683  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-29 06:31:53.683  5953  5981 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 06:31:53.683  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.683  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 06:31:53.683  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 06:31:53.683  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-29 06:31:53.683  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:31:53.683  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 06:31:53.683  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 06:31:53.683  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 06:31:53.683  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 06:31:53.683  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-29 06:31:53.685  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 06:31:53.686  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 06:31:53.686  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 06:31:53.686  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 06:31:53.686  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 06:31:53.687  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.688  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:31:53.688  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:31:53.688  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:31:53.690  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 06:31:53.690  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.690  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:31:53.690  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:31:53.690  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:31:53.691  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.691  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
,09-29 06:31:53.691  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:31:53.691  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 06:31:53.691  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.691  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.691  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.691  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec6ebc removed from the list
09-29 06:31:53.691  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.691  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed09e45 removed from the list
09-29 06:31:53.691  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:53.691  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.692  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.692  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.695  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.695  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.695  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.695  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed09e45 not in the list
09-29 06:31:53.695  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.695  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.697  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6fbaa8 removed from the list
09-29 06:31:53.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.697  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.697  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.697  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.697  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c82cb removed from the list
09-29 06:31:53.698  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.698  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@,759d954 added. We now have 3 listener(s)
09-29 06:31:53.699  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.700  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.700  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.700  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.700  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7150fd added. We now have 4 listener(s)
09-29 06:31:53.700  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.701  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 06:31:53.702  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 06:31:53.702  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.703  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:53.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:31:53.708  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 06:31:53.708  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.711  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:31:53.711  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:31:53.711  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.711  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3288043 added. We now have 4 listener(s)
,09-29 06:31:53.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 06:31:53.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.714  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.715  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.715  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:53.715  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62536c0 added. We now have 5 listener(s)
09-29 06:31:53.715  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.715  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:31:53.716  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 06:31:53.716  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.716  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:31:53.716  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 06:31:53.716  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 06:31:53.716  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
09-29 06:31:53.716  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 06:31:53.716  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 06:31:53.718  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:53.719  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 06:31:53.719  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 06:31:53.723  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 06:31:53.723  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 06:31:53.723  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.723  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 06:31:53.724  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 06:31:53.724  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 06:31:53.727  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 06:31:53.727  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 06:31:53.727  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 06:31:53.727  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 06:31:53.727  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-29 06:31:53.728  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:31:53.729  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 06:31:53.729  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.730  5953  5981 D BtGatt.GattService: registerClient() - UUID=8af43af0-58fb-4001-8b1d-0901ecb57b0e
09-29 06:31:53.731  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=8af43af0-58fb-4001-8b1d-0901ecb57b0e, clientIf=5
,09-29 06:31:53.731  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 06:31:53.732  5953  5964 D BtGatt.GattService: start scan with filters
,09-29 06:31:53.734  5953  5972 D BtGatt.ScanManager: handling starting scan
09-29 06:31:53.735  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 06:31:53.735  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 06:31:53.735  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:31:53.735  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 06:31:53.736  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 06:31:53.736  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-29 06:31:53.736  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 06:31:53.739  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 06:31:53.739  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 06:31:53.739  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 06:31:53.740  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 06:31:53.741  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 06:31:53.741  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.741  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 06:31:53.743  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 06:31:53.743  5684  5730 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-29 06:31:53.743  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:31:53.743  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:31:53.743  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:31:53.743  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.744  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.744  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 06:31:53.744  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.744  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.744  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@759d954 removed from the list
09-29 06:31:53.744  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:31:53.744  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7150fd removed from the list
09-29 06:31:53.744  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:53.744  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.745  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.745  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-29 06:31:53.745  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.745  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-29 06:31:53.746  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 06:31:53.746  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.746  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
09-29 06:31:53.746  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.746  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 06:31:53.746  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.746  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.747  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7150fd not in the list
09-29 06:31:53.747  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 06:31:53.747  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:31:53.747  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:31:53.747  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-29 06:31:53.747  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 06:31:53.749  5684  5730 D BluetoothAdapter: STATE_ON
09-29 06:31:53.749  5953  5981 D BtGatt.GattService: stopScan() - queue size =1
,09-29 06:31:53.750  5953  5992 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 06:31:53.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 06:31:53.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-29 06:31:53.751  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 06:31:53.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:31:53.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 06:31:53.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 06:31:53.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 06:31:53.751  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 06:31:53.752  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:31:53.752  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 06:31:53.752  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 06:31:53.752  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 06:31:53.752  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-29 06:31:53.753  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:31:53.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.754  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:31:53.754  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62536c0 removed from the list
09-29 06:31:53.754  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:31:53.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.754  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:31:53.754  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.754  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.754  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.754  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-29 06:31:53.755  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3288043 removed from the list
09-29 06:31:53.755  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.755  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86feec added. We now have 3 listener(s)
09-29 06:31:53.756  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.757  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.757  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.757  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.757  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 06:31:53.757  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.757  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaea2b5 added. We now have 4 listener(s)
09-29 06:31:53.757  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.757  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:31:53.762  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 06:31:53.762  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.764  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:31:53.770  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 06:31:53.770  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.770  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
,09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:53.772  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:31:53.775  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 06:31:53.775  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.775  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 06:31:53.776  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.777  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 06:31:53.777  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 06:31:53.777  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e7b4bb added. We now have 4 listener(s)
09-29 06:31:53.778  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.778  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.778  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.778  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.779  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65b1dd8 added. We now have 5 listener(s)
09-29 06:31:53.779  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.779  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:31:53.779  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 06:31:53.779  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 06:31:53.779  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:31:53.779  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 06:31:53.780  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 06:31:53.780  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.781  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:31:53.783  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 06:31:53.783  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 06:31:53.784  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:53.786  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 06:31:53.786  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 06:31:53.786  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 06:31:53.788  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 06:31:53.788  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 06:31:53.789  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-29 06:31:53.790  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 06:31:53.790  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-29 06:31:53.791  5684  5730 D BluetoothAdapter: STATE_ON
,09-29 06:31:53.793  5953  5981 D BtGatt.GattService: registerClient() - UUID=7168baf4-90f4-4b50-8385-f8e3e9d498b6
09-29 06:31:53.794  5953  5969 D BtGatt.GattService: onClientRegistered() - UUID=7168baf4-90f4-4b50-8385-f8e3e9d498b6, clientIf=5
,09-29 06:31:53.794  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 06:31:53.795  5953  5964 D BtGatt.GattService: start scan with filters
,09-29 06:31:53.797  5953  5972 D BtGatt.ScanManager: handling starting scan
09-29 06:31:53.798  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 06:31:53.798  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 06:31:53.798  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:31:53.798  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-29 06:31:53.798  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 06:31:53.798  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 06:31:53.798  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 06:31:53.800  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 06:31:53.801  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 06:31:53.801  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 06:31:53.802  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 06:31:53.803  5953  5969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 06:31:53.803  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.803  5953  5972 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 06:31:53.808  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 06:31:53.808  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:31:53.808  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:31:53.808  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.808  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.808  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 06:31:53.808  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 06:31:53.808  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.808  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.808  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.808  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86feec removed from the list
09-29 06:31:53.809  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.809  5953  5972 D BtGatt.ScanManager: Starting BLE batch scan
09-29 06:31:53.809  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaea2b5 removed from the list
09-29 06:31:53.809  5953  5972 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 06:31:53.809  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:53.809  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.809  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.809  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-29 06:31:53.809  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:31:53.809  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.811  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.811  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.811  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 06:31:53.811  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaea2b5 not in the list
09-29 06:31:53.811  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 06:31:53.811  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 06:31:53.811  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 06:31:53.811  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 06:31:53.811  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 06:31:53.812  5684  5730 D BluetoothAdapter: STATE_ON
,09-29 06:31:53.812  5953  5993 D BtGatt.GattService: stopScan() - queue size =1
09-29 06:31:53.813  5953  5994 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 06:31:53.813  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 06:31:53.814  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 06:31:53.814  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 06:31:53.814  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 06:31:53.814  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 06:31:53.814  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 06:31:53.814  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 06:31:53.814  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 06:31:53.815  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:31:53.815  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 06:31:53.815  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 06:31:53.815  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 06:31:53.815  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 06:31:53.815  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:31:53.817  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.817  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.817  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.817  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65b1dd8 removed from the list
09-29 06:31:53.817  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.817  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:31:53.817  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:31:53.817  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.817  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 06:31:53.817  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.817  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 06:31:53.817  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.817  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e7b4bb removed from the list
09-29 06:31:53.818  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.818  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9503f84 added. We now have 3 listener(s)
09-29 06:31:53.818  5953  5969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 06:31:53.818  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.820  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.820  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 06:31:53.820  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.821  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.821  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9d736d added. We now have 4 listener(s)
09-29 06:31:53.821  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:31:53.822  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:31:53.823  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 06:31:53.824  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:53.825  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:31:53.829  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:31:53.831  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:31:53.831  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:31:53.831  5953  5969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 06:31:53.831  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:31:53.831  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.831  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eda0033 added. We now have 4 listener(s)
09-29 06:31:53.831  5953  5972 D BtGatt.ScanManager: stopping BLe Batch
09-29 06:31:53.832  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:31:53.832  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:31:53.832  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:31:53.832  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:31:53.833  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953cff0 added. We now have 5 listener(s)
09-29 06:31:53.833  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:31:53.833  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:31:53.833  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 06:31:53.833  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 06:31:53.833  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.833  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.833  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 06:31:53.833  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.833  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.833  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9503f84 removed from the list
,09-29 06:31:53.833  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.833  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9d736d removed from the list
09-29 06:31:53.834  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:53.834  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-29 06:31:53.834  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:31:53.835  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.835  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 06:31:53.836  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.836  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.836  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.836  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9d736d not in the list
09-29 06:31:53.836  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 06:31:53.836  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.837  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 06:31:53.837  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 06:31:53.837  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 06:31:53.837  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@953cff0 removed from the list
09-29 06:31:53.837  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 06:31:53.837  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 06:31:53.837  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 06:31:53.837  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 06:31:53.838  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 06:31:53.838  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 06:31:53.838  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eda0033 removed from the list
09-29 06:31:53.838  5953  5969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 06:31:53.838  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 06:31:53.838  5953  5972 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-29 06:31:53.838  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-29 06:31:53.838  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 06:31:53.839  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-29 06:31:53.839  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:31:53.839  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-29 06:31:53.839  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 06:31:53.844  5953  5969 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 06:31:53.844  5953  5969 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 06:31:54.189  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 06:31:54.255  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 06:31:54.320  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 06:31:56.001  5684  6050 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 06:31:56.001  5684  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:31:56.809  5684  6050 W !!      : call onHalfStreamCopied
,09-29 06:31:56.809  5684  6050 I testCopyDataAndClose: closing input stream
,09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 06:31:57.594  5684  6050 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-29 06:31:57.595  5684  6050 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 06:31:57.595  5684  6050 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-29 06:32:01.151   542   542 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-29 06:32:01.151   542   542 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 06:32:01.319  5684  6051 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:01.319  5684  6051 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:32:03.320  5684  5730 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 192. Connection data: Peer properties: [null null].
09-29 06:32:03.320  5684  5730 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:32:03.320  5684  5730 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 192, name: My test thread name)
,09-29 06:32:03.331  5684  6051 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-29 06:32:03.331  5684  6051 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:03.331  5684  6051 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-29 06:32:03.516  5684  6052 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 06:32:03.516  5684  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 06:32:05.120  5684  6052 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-29 06:32:08.857  5684  6053 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:08.857  5684  6053 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:32:08.857  5684  6053 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:08.857  5684  6053 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:08.858  5684  6053 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-29 06:32:08.861  5684  5730 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 06:32:08.865  5684  6054 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:08.865  5684  6054 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 06:32:08.865  5684  6054 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
09-29 06:32:08.866  5684  6054 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:08.866  5684  6054 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-29 06:32:08.866  5684  6054 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-29 06:32:08.866  5684  6054 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-29 06:32:08.866  5684  6054 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-29 06:32:08.872  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-29 06:32:08.872  5684  5730 I jxcore-log: 
09-29 06:32:08.872  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Number of passed tests:  83'
09-29 06:32:08.872  5684  5730 I jxcore-log: 
,09-29 06:32:08.872  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Number of failed tests:  1'
09-29 06:32:08.872  5684  5730 I jxcore-log: 
09-29 06:32:08.872  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-29 06:32:08.872  5684  5730 I jxcore-log: 
09-29 06:32:08.873  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Total duration:  103028'
09-29 06:32:08.873  5684  5730 I jxcore-log: 
09-29 06:32:08.874  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Failures: 
09-29 06:32:08.874  5684  5730 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-29 06:32:08.874  5684  5730 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-29 06:32:08.874  5684  5730 I jxcore-log:      but: was ""
09-29 06:32:08.874  5684  5730 I jxcore-log: '
09-29 06:32:08.874  5684  5730 I jxcore-log: 
,09-29 06:32:08.874  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-29 06:32:08.874  5684  5730 I jxcore-log: 
,09-29 06:32:08.875  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-29 06:32:08.875  5684  5730 I jxcore-log: 
09-29 06:32:08.878  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.878  5684  5730 I jxcore-log: 
09-29 06:32:08.879  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.879  5684  5730 I jxcore-log: 
09-29 06:32:08.879  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.879  5684  5730 I jxcore-log: 
,09-29 06:32:08.879  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.879  5684  5730 I jxcore-log: 
09-29 06:32:08.880  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-29 06:32:08.880  5684  5730 I jxcore-log: 
09-29 06:32:08.880  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 06:32:08.880  5684  5730 I jxcore-log: 
09-29 06:32:08.881  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.881  5684  5730 I jxcore-log: 
09-29 06:32:08.881  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.881  5684  5730 I jxcore-log: 
09-29 06:32:08.881  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-29 06:32:08.881  5684  5730 I jxcore-log: 
09-29 06:32:08.881  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 06:32:08.881  5684  5730 I jxcore-log: 
,09-29 06:32:08.881  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 06:32:08.881  5684  5730 I jxcore-log: 
09-29 06:32:08.882  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.882  5684  5730 I jxcore-log: 
09-29 06:32:08.882  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.882  5684  5730 I jxcore-log: 
09-29 06:32:08.882  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.882  5684  5730 I jxcore-log: 
09-29 06:32:08.882  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.882  5684  5730 I jxcore-log: 
,09-29 06:32:08.883  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.883  5684  5730 I jxcore-log: 
09-29 06:32:08.883  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.883  5684  5730 I jxcore-log: 
09-29 06:32:08.883  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.883  5684  5730 I jxcore-log: 
09-29 06:32:08.884  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.884  5684  5730 I jxcore-log: 
09-29 06:32:08.884  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.884  5684  5730 I jxcore-log: 
09-29 06:32:08.884  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.884  5684  5730 I jxcore-log: 
09-29 06:32:08.884  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.884  5684  5730 I jxcore-log: 
,09-29 06:32:08.886  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.886  5684  5730 I jxcore-log: 
09-29 06:32:08.886  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.886  5684  5730 I jxcore-log: 
09-29 06:32:08.886  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.886  5684  5730 I jxcore-log: 
09-29 06:32:08.887  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.887  5684  5730 I jxcore-log: 
09-29 06:32:08.887  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.887  5684  5730 I jxcore-log: 
09-29 06:32:08.887  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.887  5684  5730 I jxcore-log: 
,09-29 06:32:08.887  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.887  5684  5730 I jxcore-log: 
09-29 06:32:08.887  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.887  5684  5730 I jxcore-log: 
09-29 06:32:08.888  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.888  5684  5730 I jxcore-log: 
09-29 06:32:08.888  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.888  5684  5730 I jxcore-log: 
09-29 06:32:08.888  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.888  5684  5730 I jxcore-log: 
09-29 06:32:08.888  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.888  5684  5730 I jxcore-log: 
,09-29 06:32:08.889  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 06:32:08.889  5684  5730 I jxcore-log: 
09-29 06:32:08.889  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.889  5684  5730 I jxcore-log: 
09-29 06:32:08.889  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.889  5684  5730 I jxcore-log: 
09-29 06:32:08.889  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 06:32:08.889  5684  5730 I jxcore-log: 
09-29 06:32:08.889  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.889  5684  5730 I jxcore-log: 
09-29 06:32:08.890  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.890  5684  5730 I jxcore-log: 
,09-29 06:32:08.890  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.890  5684  5730 I jxcore-log: 
09-29 06:32:08.890  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.890  5684  5730 I jxcore-log: 
09-29 06:32:08.890  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:32:08.890  5684  5730 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-29 06:32:08.891  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.891  5684  5730 I jxcore-log: 
09-29 06:32:08.891  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.891  5684  5730 I jxcore-log: 
09-29 06:32:08.891  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 06:32:08.891  5684  5730 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-29 06:32:08.891  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:08.891  5684  5730 I jxcore-log: 
,09-29 06:32:08.891  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 06:32:08.891  5684  5730 I jxcore-log: 
09-29 06:32:08.892  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 06:32:08.892  5684  5730 I jxcore-log: 
09-29 06:32:08.892  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 06:32:08.892  5684  5730 I jxcore-log: 
,09-29 06:32:08.898  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-29 06:32:08.898  5684  5730 I jxcore-log: 
,09-29 06:32:08.898  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - WARN testUtils: 'myNameCallback not set!'
09-29 06:32:08.898  5684  5730 I jxcore-log: 
09-29 06:32:08.899  5684  5730 I jxcore-log: 2016-09-29 10:32:08 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-29 06:32:08.899  5684  5730 I jxcore-log: 
,09-29 06:32:08.902  5684  5684 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-29 06:32:10.824  5684  5730 I jxcore-log: 2016-09-29 10:32:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-29 06:32:10.824  5684  5730 I jxcore-log: 
,09-29 06:32:11.140  5684  5730 I jxcore-log: 2016-09-29 10:32:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-29 06:32:11.140  5684  5730 I jxcore-log: 
,09-29 06:32:11.153  5684  5730 I jxcore-log: 2016-09-29 10:32:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-29 06:32:11.153  5684  5730 I jxcore-log: 
,09-29 06:32:12.222  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-29 06:32:12.222  5684  5730 I jxcore-log: 
,09-29 06:32:12.374  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-29 06:32:12.374  5684  5730 I jxcore-log: 
,09-29 06:32:12.378  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-29 06:32:12.378  5684  5730 I jxcore-log: 
,09-29 06:32:12.383  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-29 06:32:12.383  5684  5730 I jxcore-log: 
,09-29 06:32:12.922  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-29 06:32:12.922  5684  5730 I jxcore-log: 
,09-29 06:32:12.973  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-29 06:32:12.973  5684  5730 I jxcore-log: 
,09-29 06:32:12.985  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-29 06:32:12.985  5684  5730 I jxcore-log: 
,09-29 06:32:12.989  5684  5730 I jxcore-log: 2016-09-29 10:32:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-29 06:32:12.989  5684  5730 I jxcore-log: 
,09-29 06:32:13.260  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-29 06:32:13.260  5684  5730 I jxcore-log: 
,09-29 06:32:13.381  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-29 06:32:13.381  5684  5730 I jxcore-log: 
,09-29 06:32:13.606  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-29 06:32:13.606  5684  5730 I jxcore-log: 
,09-29 06:32:13.616  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js',
09-29 06:32:13.616  5684  5730 I jxcore-log: 
,09-29 06:32:13.620  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-29 06:32:13.620  5684  5730 I jxcore-log: 
,09-29 06:32:13.752  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-29 06:32:13.752  5684  5730 I jxcore-log: 
,09-29 06:32:13.760  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-29 06:32:13.760  5684  5730 I jxcore-log: 
,09-29 06:32:13.786  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-29 06:32:13.786  5684  5730 I jxcore-log: 
,09-29 06:32:13.819  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-29 06:32:13.819  5684  5730 I jxcore-log: 
,09-29 06:32:13.826  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-29 06:32:13.826  5684  5730 I jxcore-log: 
,09-29 06:32:13.831  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-29 06:32:13.831  5684  5730 I jxcore-log: 
,09-29 06:32:13.844  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-29 06:32:13.844  5684  5730 I jxcore-log: 
,09-29 06:32:13.848  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-29 06:32:13.848  5684  5730 I jxcore-log: 
,09-29 06:32:13.853  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-29 06:32:13.853  5684  5730 I jxcore-log: 
,09-29 06:32:13.858  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-29 06:32:13.858  5684  5730 I jxcore-log: 
,09-29 06:32:13.870  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-29 06:32:13.870  5684  5730 I jxcore-log: 
,09-29 06:32:13.888  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-29 06:32:13.888  5684  5730 I jxcore-log: 
,09-29 06:32:13.897  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-29 06:32:13.897  5684  5730 I jxcore-log: 
,09-29 06:32:13.907  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-29 06:32:13.907  5684  5730 I jxcore-log: 
,09-29 06:32:13.915  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-29 06:32:13.915  5684  5730 I jxcore-log: 
,09-29 06:32:13.926  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-29 06:32:13.926  5684  5730 I jxcore-log: 
,09-29 06:32:13.934  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-29 06:32:13.934  5684  5730 I jxcore-log: 
,09-29 06:32:13.938  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-29 06:32:13.938  5684  5730 I jxcore-log: 
,09-29 06:32:13.956  5684  5730 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-29 06:32:13.957  5684  5730 I jxcore-log: 2016-09-29 10:32:13 - INFO testUtils: 'BLE multiple advertisement supported'
09-29 06:32:13.957  5684  5730 I jxcore-log: 
,09-29 06:32:14.122  5684  5730 I jxcore-log: 2016-09-29 10:32:14 - DEBUG CoordinatedClient: 'connected to the test server'
09-29 06:32:14.122  5684  5730 I jxcore-log: 
,09-29 06:32:14.701  5684  5730 I jxcore-log: TAP version 13
09-29 06:32:14.701  5684  5730 I jxcore-log: 
,09-29 06:32:14.743  5684  5730 I jxcore-log: # setup
09-29 06:32:14.743  5684  5730 I jxcore-log: 
,09-29 06:32:15.641  5684  5730 I jxcore-log: # calling createNativeListener directly rejects
09-29 06:32:15.641  5684  5730 I jxcore-log: 
,09-29 06:32:15.687  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:15.687  5684  5730 I jxcore-log: 
,09-29 06:32:15.694  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'listening 47327'
09-29 06:32:15.694  5684  5730 I jxcore-log: 
,09-29 06:32:15.700  5684  5730 I jxcore-log: ok 1 Should throw
09-29 06:32:15.700  5684  5730 I jxcore-log: 
,09-29 06:32:15.711  5684  5730 I jxcore-log: # teardown,
09-29 06:32:15.711  5684  5730 I jxcore-log: 
,09-29 06:32:15.770  5684  5730 I jxcore-log: # setup
09-29 06:32:15.770  5684  5730 I jxcore-log: 
,09-29 06:32:15.866  5684  5730 I jxcore-log: # emits incomingConnectionState
09-29 06:32:15.866  5684  5730 I jxcore-log: 
,09-29 06:32:15.921  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:15.921  5684  5730 I jxcore-log: 
,09-29 06:32:15.926  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'listening 41605'
09-29 06:32:15.926  5684  5730 I jxcore-log: 
,09-29 06:32:15.937  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:15.937  5684  5730 I jxcore-log: 
,09-29 06:32:15.941  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:15.941  5684  5730 I jxcore-log: 
,09-29 06:32:15.955  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'new mux'
09-29 06:32:15.955  5684  5730 I jxcore-log: 
,09-29 06:32:15.961  5684  5730 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-29 06:32:15.961  5684  5730 I jxcore-log: 
,09-29 06:32:15.980  5684  5730 I jxcore-log: 2016-09-29 10:32:15 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:15.980  5684  5730 I jxcore-log: 
,09-29 06:32:15.981  5684  5730 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-29 06:32:15.981  5684  5730 I jxcore-log: 
,09-29 06:32:15.990  5684  5730 I jxcore-log: # teardown
09-29 06:32:15.990  5684  5730 I jxcore-log: 
,09-29 06:32:16.029  5684  5730 I jxcore-log: # setup
09-29 06:32:16.029  5684  5730 I jxcore-log: 
,09-29 06:32:16.093  5684  5730 I jxcore-log: # emits routerPortConnectionFailed
09-29 06:32:16.093  5684  5730 I jxcore-log: 
,09-29 06:32:16.153   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:16.165  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:16.165  5684  5730 I jxcore-log: 
,09-29 06:32:16.170  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'listening 41008'
09-29 06:32:16.170  5684  5730 I jxcore-log: 
,09-29 06:32:16.178  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:16.178  5684  5730 I jxcore-log: 
,09-29 06:32:16.180  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:16.180  5684  5730 I jxcore-log: 
,09-29 06:32:16.182  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new mux'
09-29 06:32:16.182  5684  5730 I jxcore-log: 
,09-29 06:32:16.213  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:16.213  5684  5730 I jxcore-log: 
,09-29 06:32:16.216  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:16.216  5684  5730 I jxcore-log: 
,09-29 06:32:16.220  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: ' $c@net.js:837:7
09-29 06:32:16.220  5684  5730 I jxcore-log: $09@net.js:829:13
09-29 06:32:16.220  5684  5730 I jxcore-log: '
09-29 06:32:16.220  5684  5730 I jxcore-log: 
,09-29 06:32:16.221  5684  5730 I jxcore-log: ok 4 tried to connect to right port
09-29 06:32:16.221  5684  5730 I jxcore-log: 
09-29 06:32:16.221  5684  5730 I jxcore-log: ok 5 failed due to refused connection
09-29 06:32:16.221  5684  5730 I jxcore-log: 
,09-29 06:32:16.222  5684  5730 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-29 06:32:16.222  5684  5730 I jxcore-log: 
,09-29 06:32:16.226  5684  5730 I jxcore-log: # teardown
09-29 06:32:16.226  5684  5730 I jxcore-log: 
,09-29 06:32:16.227  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:16.227  5684  5730 I jxcore-log: 
,09-29 06:32:16.307  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'mux close'
09-29 06:32:16.307  5684  5730 I jxcore-log: 
,09-29 06:32:16.317  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:16.317  5684  5730 I jxcore-log: 
,09-29 06:32:16.336  5684  5730 I jxcore-log: # setup
09-29 06:32:16.336  5684  5730 I jxcore-log: 
,09-29 06:32:16.441  5684  5730 I jxcore-log: # native server connections all up
09-29 06:32:16.441  5684  5730 I jxcore-log: 
,09-29 06:32:16.472  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:16.472  5684  5730 I jxcore-log: 
,09-29 06:32:16.477  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'listening 37603'
09-29 06:32:16.477  5684  5730 I jxcore-log: 
,09-29 06:32:16.486  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:16.486  5684  5730 I jxcore-log: 
,09-29 06:32:16.488  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:16.488  5684  5730 I jxcore-log: 
,09-29 06:32:16.489  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new mux'
09-29 06:32:16.489  5684  5730 I jxcore-log: 
,09-29 06:32:16.523  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:16.523  5684  5730 I jxcore-log: 
,09-29 06:32:16.528  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:16.528  5684  5730 I jxcore-log: 
,09-29 06:32:16.533  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:16.533  5684  5730 I jxcore-log: 
,09-29 06:32:16.537  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:16.537  5684  5730 I jxcore-log: 
,09-29 06:32:16.566  5684  5730 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-29 06:32:16.566  5684  5730 I jxcore-log: 
,09-29 06:32:16.567  5684  5730 I jxcore-log: ok 8 Send/recvd #1 should be same
09-29 06:32:16.567  5684  5730 I jxcore-log: 
,09-29 06:32:16.570  5684  5730 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-29 06:32:16.570  5684  5730 I jxcore-log: 
09-29 06:32:16.571  5684  5730 I jxcore-log: ok 10 Send/recvd #2 should be same
09-29 06:32:16.571  5684  5730 I jxcore-log: 
,09-29 06:32:16.577  5684  5730 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-29 06:32:16.577  5684  5730 I jxcore-log: 
,09-29 06:32:16.587  5684  5730 I jxcore-log: # teardown
09-29 06:32:16.587  5684  5730 I jxcore-log: 
,09-29 06:32:16.618  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:16.618  5684  5730 I jxcore-log: 
,09-29 06:32:16.623  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:16.623  5684  5730 I jxcore-log: 
,09-29 06:32:16.625  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'mux close'
09-29 06:32:16.625  5684  5730 I jxcore-log: 
,09-29 06:32:16.629  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:16.629  5684  5730 I jxcore-log: 
,09-29 06:32:16.641  5684  5730 I jxcore-log: # setup
09-29 06:32:16.641  5684  5730 I jxcore-log: 
,09-29 06:32:16.709  5684  5730 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-29 06:32:16.709  5684  5730 I jxcore-log: 
,09-29 06:32:16.788  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:16.788  5684  5730 I jxcore-log: 
,09-29 06:32:16.795  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'listening 48933'
09-29 06:32:16.795  5684  5730 I jxcore-log: 
,09-29 06:32:16.806  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:16.806  5684  5730 I jxcore-log: 
,09-29 06:32:16.808  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:16.808  5684  5730 I jxcore-log: 
,09-29 06:32:16.813  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new mux'
09-29 06:32:16.813  5684  5730 I jxcore-log: 
,09-29 06:32:16.827  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:16.827  5684  5730 I jxcore-log: 
,09-29 06:32:16.831  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:16.831  5684  5730 I jxcore-log: 
,09-29 06:32:16.849  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:16.849  5684  5730 I jxcore-log: 
,09-29 06:32:16.864  5684  5730 I jxcore-log: ok 12 socket shouldn't close until after stream
09-29 06:32:16.864  5684  5730 I jxcore-log: 
,09-29 06:32:16.865  5684  5730 I jxcore-log: ok 13 incoming remains open
09-29 06:32:16.865  5684  5730 I jxcore-log: 
,09-29 06:32:16.873  5684  5730 I jxcore-log: # teardown
09-29 06:32:16.873  5684  5730 I jxcore-log: 
,09-29 06:32:16.925  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'mux close'
09-29 06:32:16.925  5684  5730 I jxcore-log: 
,09-29 06:32:16.933  5684  5730 I jxcore-log: 2016-09-29 10:32:16 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:16.933  5684  5730 I jxcore-log: 
,09-29 06:32:16.941  5684  5730 I jxcore-log: # setup
09-29 06:32:16.941  5684  5730 I jxcore-log: 
,09-29 06:32:17.011  5684  5730 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-29 06:32:17.011  5684  5730 I jxcore-log: 
,09-29 06:32:17.053  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:17.053  5684  5730 I jxcore-log: 
,09-29 06:32:17.056  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'listening 40626'
09-29 06:32:17.056  5684  5730 I jxcore-log: 
,09-29 06:32:17.062  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.062  5684  5730 I jxcore-log: 
,09-29 06:32:17.063  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.063  5684  5730 I jxcore-log: 
09-29 06:32:17.064  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.064  5684  5730 I jxcore-log: 
,09-29 06:32:17.078  5684  5730 I jxcore-log: ok 14 we should not have gotten an error
09-29 06:32:17.078  5684  5730 I jxcore-log: 
,09-29 06:32:17.085  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.085  5684  5730 I jxcore-log: 
,09-29 06:32:17.090  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.090  5684  5730 I jxcore-log: 
,09-29 06:32:17.101  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.101  5684  5730 I jxcore-log: 
,09-29 06:32:17.103  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:17.103  5684  5730 I jxcore-log: 
,09-29 06:32:17.112  5684  5730 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-29 06:32:17.112  5684  5730 I jxcore-log: 
,09-29 06:32:17.113  5684  5730 I jxcore-log: ok 16 incoming is cleaned up
09-29 06:32:17.113  5684  5730 I jxcore-log: 
,09-29 06:32:17.120  5684  5730 I jxcore-log: # teardown
09-29 06:32:17.120  5684  5730 I jxcore-log: 
,09-29 06:32:17.153   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:17.158  5684  5730 I jxcore-log: # setup
09-29 06:32:17.158  5684  5730 I jxcore-log: 
,09-29 06:32:17.223  5684  5730 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-29 06:32:17.223  5684  5730 I jxcore-log: 
,09-29 06:32:17.271  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:17.271  5684  5730 I jxcore-log: 
,09-29 06:32:17.280  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'listening 48762'
09-29 06:32:17.280  5684  5730 I jxcore-log: 
,09-29 06:32:17.290  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.290  5684  5730 I jxcore-log: 
,09-29 06:32:17.294  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.294  5684  5730 I jxcore-log: 
,09-29 06:32:17.298  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.298  5684  5730 I jxcore-log: 
,09-29 06:32:17.311  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.311  5684  5730 I jxcore-log: 
,09-29 06:32:17.316  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.316  5684  5730 I jxcore-log: 
,09-29 06:32:17.334  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.334  5684  5730 I jxcore-log: 
,09-29 06:32:17.344  5684  5730 I jxcore-log: ok 17 stream was closed
09-29 06:32:17.344  5684  5730 I jxcore-log: 
,09-29 06:32:17.345  5684  5730 I jxcore-log: ok 18 incoming should survive
09-29 06:32:17.345  5684  5730 I jxcore-log: 
09-29 06:32:17.345  5684  5730 I jxcore-log: ok 19 mux should have no streams
09-29 06:32:17.345  5684  5730 I jxcore-log: 
,09-29 06:32:17.352  5684  5730 I jxcore-log: # teardown
09-29 06:32:17.352  5684  5730 I jxcore-log: 
,09-29 06:32:17.401  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'mux close'
09-29 06:32:17.401  5684  5730 I jxcore-log: 
,09-29 06:32:17.417  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:17.417  5684  5730 I jxcore-log: 
,09-29 06:32:17.429  5684  5730 I jxcore-log: # setup
09-29 06:32:17.429  5684  5730 I jxcore-log: 
,09-29 06:32:17.517  5684  5730 I jxcore-log: # native server - closing the whole server cleans everything up
09-29 06:32:17.517  5684  5730 I jxcore-log: 
,09-29 06:32:17.559  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:17.559  5684  5730 I jxcore-log: 
,09-29 06:32:17.563  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'listening 43935'
09-29 06:32:17.563  5684  5730 I jxcore-log: 
,09-29 06:32:17.571  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.571  5684  5730 I jxcore-log: 
,09-29 06:32:17.573  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.573  5684  5730 I jxcore-log: 
,09-29 06:32:17.575  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.575  5684  5730 I jxcore-log: 
,09-29 06:32:17.586  5684  5730 I jxcore-log: ok 20 we should not have gotten an error
09-29 06:32:17.586  5684  5730 I jxcore-log: 
,09-29 06:32:17.596  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.596  5684  5730 I jxcore-log: 
,09-29 06:32:17.601  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.601  5684  5730 I jxcore-log: 
,09-29 06:32:17.610  5684  5730 I jxcore-log: ok 21 Buffers are identical
09-29 06:32:17.610  5684  5730 I jxcore-log: 
09-29 06:32:17.613  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.613  5684  5730 I jxcore-log: 
09-29 06:32:17.615  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'mux close'
09-29 06:32:17.615  5684  5730 I jxcore-log: 
,09-29 06:32:17.618  5684  5730 I jxcore-log: ok 22 native server is nulled out
09-29 06:32:17.618  5684  5730 I jxcore-log: 
09-29 06:32:17.618  5684  5730 I jxcore-log: ok 23 native server should be closed
09-29 06:32:17.618  5684  5730 I jxcore-log: 
09-29 06:32:17.618  5684  5730 I jxcore-log: ok 24 incoming has been removed
09-29 06:32:17.618  5684  5730 I jxcore-log: 
09-29 06:32:17.619  5684  5730 I jxcore-log: ok 25 Incoming should be done
09-29 06:32:17.619  5684  5730 I jxcore-log: 
,09-29 06:32:17.620  5684  5730 I jxcore-log: ok 26 The mux object should be closed
09-29 06:32:17.620  5684  5730 I jxcore-log: 
,09-29 06:32:17.621  5684  5730 I jxcore-log: ok 27 The mux stream should be closed
09-29 06:32:17.621  5684  5730 I jxcore-log: 
09-29 06:32:17.622  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:17.622  5684  5730 I jxcore-log: 
,09-29 06:32:17.638  5684  5730 I jxcore-log: # teardown
09-29 06:32:17.638  5684  5730 I jxcore-log: 
,09-29 06:32:17.680  5684  5730 I jxcore-log: # setup
09-29 06:32:17.680  5684  5730 I jxcore-log: 
,09-29 06:32:17.738  5684  5730 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-29 06:32:17.738  5684  5730 I jxcore-log: 
,09-29 06:32:17.778  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:17.778  5684  5730 I jxcore-log: 
,09-29 06:32:17.784  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'listening 48365'
09-29 06:32:17.784  5684  5730 I jxcore-log: 
,09-29 06:32:17.805  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.805  5684  5730 I jxcore-log: 
,09-29 06:32:17.807  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.807  5684  5730 I jxcore-log: 
09-29 06:32:17.808  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.808  5684  5730 I jxcore-log: 
,09-29 06:32:17.812  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.812  5684  5730 I jxcore-log: 
09-29 06:32:17.813  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.813  5684  5730 I jxcore-log: 
,09-29 06:32:17.813  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.813  5684  5730 I jxcore-log: 
,09-29 06:32:17.815  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.815  5684  5730 I jxcore-log: 
09-29 06:32:17.815  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.815  5684  5730 I jxcore-log: 
09-29 06:32:17.816  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.816  5684  5730 I jxcore-log: 
,09-29 06:32:17.818  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.818  5684  5730 I jxcore-log: 
09-29 06:32:17.818  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.818  5684  5730 I jxcore-log: 
,09-29 06:32:17.819  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.819  5684  5730 I jxcore-log: 
,09-29 06:32:17.820  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.820  5684  5730 I jxcore-log: 
09-29 06:32:17.821  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.821  5684  5730 I jxcore-log: 
,09-29 06:32:17.823  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.823  5684  5730 I jxcore-log: 
09-29 06:32:17.825  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.825  5684  5730 I jxcore-log: 
09-29 06:32:17.825  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.825  5684  5730 I jxcore-log: 
,09-29 06:32:17.826  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.826  5684  5730 I jxcore-log: 
,09-29 06:32:17.830  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.830  5684  5730 I jxcore-log: 
09-29 06:32:17.831  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.831  5684  5730 I jxcore-log: 
,09-29 06:32:17.831  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.831  5684  5730 I jxcore-log: 
,09-29 06:32:17.833  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.833  5684  5730 I jxcore-log: 
09-29 06:32:17.833  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.833  5684  5730 I jxcore-log: 
09-29 06:32:17.833  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.833  5684  5730 I jxcore-log: 
,09-29 06:32:17.835  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.835  5684  5730 I jxcore-log: 
,09-29 06:32:17.835  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.835  5684  5730 I jxcore-log: 
09-29 06:32:17.836  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.836  5684  5730 I jxcore-log: 
,09-29 06:32:17.837  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:17.837  5684  5730 I jxcore-log: 
09-29 06:32:17.837  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:17.837  5684  5730 I jxcore-log: 
09-29 06:32:17.838  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new mux'
09-29 06:32:17.838  5684  5730 I jxcore-log: 
,09-29 06:32:17.887  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.887  5684  5730 I jxcore-log: 
,09-29 06:32:17.888  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.888  5684  5730 I jxcore-log: 
,09-29 06:32:17.889  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.889  5684  5730 I jxcore-log: 
09-29 06:32:17.890  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.890  5684  5730 I jxcore-log: 
09-29 06:32:17.891  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.891  5684  5730 I jxcore-log: 
,09-29 06:32:17.892  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.892  5684  5730 I jxcore-log: 
09-29 06:32:17.893  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.893  5684  5730 I jxcore-log: 
,09-29 06:32:17.894  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.894  5684  5730 I jxcore-log: 
09-29 06:32:17.895  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.895  5684  5730 I jxcore-log: 
,09-29 06:32:17.896  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.896  5684  5730 I jxcore-log: 
09-29 06:32:17.896  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.896  5684  5730 I jxcore-log: 
,09-29 06:32:17.897  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.897  5684  5730 I jxcore-log: 
09-29 06:32:17.898  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.898  5684  5730 I jxcore-log: 
09-29 06:32:17.898  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.898  5684  5730 I jxcore-log: 
,09-29 06:32:17.899  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.899  5684  5730 I jxcore-log: 
09-29 06:32:17.900  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.900  5684  5730 I jxcore-log: 
,09-29 06:32:17.901  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.901  5684  5730 I jxcore-log: 
09-29 06:32:17.902  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.902  5684  5730 I jxcore-log: 
09-29 06:32:17.902  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.902  5684  5730 I jxcore-log: 
,09-29 06:32:17.903  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.903  5684  5730 I jxcore-log: 
09-29 06:32:17.903  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.903  5684  5730 I jxcore-log: 
09-29 06:32:17.904  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.904  5684  5730 I jxcore-log: 
,09-29 06:32:17.905  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.905  5684  5730 I jxcore-log: 
09-29 06:32:17.905  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.905  5684  5730 I jxcore-log: 
09-29 06:32:17.906  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.906  5684  5730 I jxcore-log: 
09-29 06:32:17.907  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.907  5684  5730 I jxcore-log: 
09-29 06:32:17.908  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.908  5684  5730 I jxcore-log: 
09-29 06:32:17.908  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.908  5684  5730 I jxcore-log: 
,09-29 06:32:17.909  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.909  5684  5730 I jxcore-log: 
09-29 06:32:17.910  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.910  5684  5730 I jxcore-log: 
09-29 06:32:17.910  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.910  5684  5730 I jxcore-log: 
,09-29 06:32:17.911  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.911  5684  5730 I jxcore-log: 
09-29 06:32:17.912  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.912  5684  5730 I jxcore-log: 
,09-29 06:32:17.913  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.913  5684  5730 I jxcore-log: 
09-29 06:32:17.913  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.913  5684  5730 I jxcore-log: 
,09-29 06:32:17.914  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.914  5684  5730 I jxcore-log: 
09-29 06:32:17.914  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.914  5684  5730 I jxcore-log: 
,09-29 06:32:17.915  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.915  5684  5730 I jxcore-log: 
09-29 06:32:17.916  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.916  5684  5730 I jxcore-log: 
09-29 06:32:17.916  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.916  5684  5730 I jxcore-log: 
,09-29 06:32:17.917  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.917  5684  5730 I jxcore-log: 
09-29 06:32:17.918  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.918  5684  5730 I jxcore-log: 
,09-29 06:32:17.919  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.919  5684  5730 I jxcore-log: 
09-29 06:32:17.919  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.919  5684  5730 I jxcore-log: 
,09-29 06:32:17.920  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.920  5684  5730 I jxcore-log: 
09-29 06:32:17.921  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.921  5684  5730 I jxcore-log: 
09-29 06:32:17.921  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.921  5684  5730 I jxcore-log: 
,09-29 06:32:17.922  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.922  5684  5730 I jxcore-log: 
,09-29 06:32:17.927  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.927  5684  5730 I jxcore-log: 
,09-29 06:32:17.928  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.928  5684  5730 I jxcore-log: 
09-29 06:32:17.929  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.929  5684  5730 I jxcore-log: 
,09-29 06:32:17.930  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.930  5684  5730 I jxcore-log: 
09-29 06:32:17.931  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.931  5684  5730 I jxcore-log: 
,09-29 06:32:17.931  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.931  5684  5730 I jxcore-log: 
09-29 06:32:17.932  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.932  5684  5730 I jxcore-log: 
09-29 06:32:17.933  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.933  5684  5730 I jxcore-log: 
,09-29 06:32:17.934  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.934  5684  5730 I jxcore-log: 
09-29 06:32:17.934  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.934  5684  5730 I jxcore-log: 
09-29 06:32:17.935  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.935  5684  5730 I jxcore-log: 
,09-29 06:32:17.936  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.936  5684  5730 I jxcore-log: 
09-29 06:32:17.936  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.936  5684  5730 I jxcore-log: 
,09-29 06:32:17.937  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.937  5684  5730 I jxcore-log: 
09-29 06:32:17.937  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.937  5684  5730 I jxcore-log: 
09-29 06:32:17.938  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.938  5684  5730 I jxcore-log: 
,09-29 06:32:17.939  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.939  5684  5730 I jxcore-log: 
09-29 06:32:17.940  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.940  5684  5730 I jxcore-log: 
,09-29 06:32:17.940  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.940  5684  5730 I jxcore-log: 
09-29 06:32:17.941  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.941  5684  5730 I jxcore-log: 
,09-29 06:32:17.942  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.942  5684  5730 I jxcore-log: 
09-29 06:32:17.943  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.943  5684  5730 I jxcore-log: 
09-29 06:32:17.943  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.943  5684  5730 I jxcore-log: 
09-29 06:32:17.944  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.944  5684  5730 I jxcore-log: 
,09-29 06:32:17.945  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.945  5684  5730 I jxcore-log: 
09-29 06:32:17.945  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.945  5684  5730 I jxcore-log: 
09-29 06:32:17.946  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.946  5684  5730 I jxcore-log: 
,09-29 06:32:17.947  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.947  5684  5730 I jxcore-log: 
09-29 06:32:17.947  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.947  5684  5730 I jxcore-log: 
09-29 06:32:17.948  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.948  5684  5730 I jxcore-log: 
09-29 06:32:17.948  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:17.948  5684  5730 I jxcore-log: 
09-29 06:32:17.949  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:17.949  5684  5730 I jxcore-log: 
,09-29 06:32:17.993  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.993  5684  5730 I jxcore-log: 
,09-29 06:32:17.994  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.994  5684  5730 I jxcore-log: 
09-29 06:32:17.995  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.995  5684  5730 I jxcore-log: 
,09-29 06:32:17.996  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.996  5684  5730 I jxcore-log: 
09-29 06:32:17.997  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'mux close'
09-29 06:32:17.997  5684  5730 I jxcore-log: 
,09-29 06:32:17.997  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.997  5684  5730 I jxcore-log: 
09-29 06:32:17.998  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.998  5684  5730 I jxcore-log: 
,09-29 06:32:17.998  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.998  5684  5730 I jxcore-log: 
09-29 06:32:17.999  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:17.999  5684  5730 I jxcore-log: 
09-29 06:32:17.999  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'mux close'
09-29 06:32:17.999  5684  5730 I jxcore-log: 
,09-29 06:32:18.000  5684  5730 I jxcore-log: 2016-09-29 10:32:17 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.000  5684  5730 I jxcore-log: 
09-29 06:32:18.000  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.000  5684  5730 I jxcore-log: 
09-29 06:32:18.000  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.000  5684  5730 I jxcore-log: 
09-29 06:32:18.001  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.001  5684  5730 I jxcore-log: 
,09-29 06:32:18.002  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.002  5684  5730 I jxcore-log: 
09-29 06:32:18.002  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.002  5684  5730 I jxcore-log: 
09-29 06:32:18.003  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.003  5684  5730 I jxcore-log: 
,09-29 06:32:18.003  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.003  5684  5730 I jxcore-log: 
09-29 06:32:18.003  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.003  5684  5730 I jxcore-log: 
09-29 06:32:18.004  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.004  5684  5730 I jxcore-log: 
09-29 06:32:18.004  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.004  5684  5730 I jxcore-log: 
,09-29 06:32:18.005  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.005  5684  5730 I jxcore-log: 
09-29 06:32:18.005  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.005  5684  5730 I jxcore-log: 
09-29 06:32:18.006  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.006  5684  5730 I jxcore-log: 
09-29 06:32:18.006  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.006  5684  5730 I jxcore-log: 
,09-29 06:32:18.007  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.007  5684  5730 I jxcore-log: 
09-29 06:32:18.007  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.007  5684  5730 I jxcore-log: 
09-29 06:32:18.008  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.008  5684  5730 I jxcore-log: 
09-29 06:32:18.008  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.008  5684  5730 I jxcore-log: 
09-29 06:32:18.009  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.009  5684  5730 I jxcore-log: 
09-29 06:32:18.009  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.009  5684  5730 I jxcore-log: 
09-29 06:32:18.009  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.009  5684  5730 I jxcore-log: 
09-29 06:32:18.010  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.010  5684  5730 I jxcore-log: 
09-29 06:32:18.010  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.010  5684  5730 I jxcore-log: 
09-29 06:32:18.011  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.011  5684  5730 I jxcore-log: 
09-29 06:32:18.011  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.011  5684  5730 I jxcore-log: 
09-29 06:32:18.012  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.012  5684  5730 I jxcore-log: 
09-29 06:32:18.012  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.012  5684  5730 I jxcore-log: 
09-29 06:32:18.012  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.012  5684  5730 I jxcore-log: 
09-29 06:32:18.013  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.013  5684  5730 I jxcore-log: 
09-29 06:32:18.013  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.013  5684  5730 I jxcore-log: 
09-29 06:32:18.014  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.014  5684  5730 I jxcore-log: 
09-29 06:32:18.014  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.014  5684  5730 I jxcore-log: 
09-29 06:32:18.014  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.014  5684  5730 I jxcore-log: 
09-29 06:32:18.016  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.016  5684  5730 I jxcore-log: 
09-29 06:32:18.017  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.017  5684  5730 I jxcore-log: 
09-29 06:32:18.017  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.017  5684  5730 I jxcore-log: 
09-29 06:32:18.017  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.017  5684  5730 I jxcore-log: 
09-29 06:32:18.018  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:18.018  5684  5730 I jxcore-log: 
09-29 06:32:18.018  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'mux close'
09-29 06:32:18.018  5684  5730 I jxcore-log: 
09-29 06:32:18.020  5684  5730 I jxcore-log: ok 28 native server is nulled out
09-29 06:32:18.020  5684  5730 I jxcore-log: 
09-29 06:32:18.020  5684  5730 I jxcore-log: ok 29 native server should be closed
09-29 06:32:18.020  5684  5730 I jxcore-log: 
09-29 06:32:18.021  5684  5730 I jxcore-log: ok 30 incoming has been removed
09-29 06:32:18.021  5684  5730 I jxcore-log: 
09-29 06:32:18.023  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.023  5684  5730 I jxcore-log: 
09-29 06:32:18.024  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.024  5684  5730 I jxcore-log: 
09-29 06:32:18.024  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.024  5684  5730 I jxcore-log: 
09-29 06:32:18.025  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.025  5684  5730 I jxcore-log: 
09-29 06:32:18.025  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.025  5684  5730 I jxcore-log: 
09-29 06:32:18.025  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.025  5684  5730 I jxcore-log: 
09-29 06:32:18.025  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.025  5684  5730 I jxcore-log: 
09-29 06:32:18.025  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.025  5684  5730 I jxcore-log: 
09-29 06:32:18.026  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.026  5684  5730 I jxcore-log: 
09-29 06:32:18.026  5684  5730 I jxcore-log: 2016-09-29 10:32:18 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:18.026  5684  5730 I jxcore-log: 
,09-29 06:32:18.098  5684  5730 I jxcore-log: # teardown
09-29 06:32:18.098  5684  5730 I jxcore-log: 
,09-29 06:32:18.154   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:18.200  5684  5730 I jxcore-log: # setup
09-29 06:32:18.200  5684  5730 I jxcore-log: 
,09-29 06:32:19.156   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:20.008  5684  5730 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-29 06:32:20.008  5684  5730 I jxcore-log: 
,09-29 06:32:20.047  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:20.047  5684  5730 I jxcore-log: 
,09-29 06:32:20.054  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'listening 42646'
09-29 06:32:20.054  5684  5730 I jxcore-log: 
,09-29 06:32:20.064  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:20.064  5684  5730 I jxcore-log: 
,09-29 06:32:20.067  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:20.067  5684  5730 I jxcore-log: 
,09-29 06:32:20.070  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new mux'
09-29 06:32:20.070  5684  5730 I jxcore-log: 
,09-29 06:32:20.081  5684  5730 I jxcore-log: ok 31 we should not have gotten an error
09-29 06:32:20.081  5684  5730 I jxcore-log: 
,09-29 06:32:20.085  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:20.085  5684  5730 I jxcore-log: 
,09-29 06:32:20.088  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:20.088  5684  5730 I jxcore-log: 
,09-29 06:32:20.095  5684  5730 I jxcore-log: ok 32 Buffers are identical
09-29 06:32:20.095  5684  5730 I jxcore-log: 
,09-29 06:32:20.096  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:20.096  5684  5730 I jxcore-log: 
09-29 06:32:20.098  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'mux close'
09-29 06:32:20.098  5684  5730 I jxcore-log: 
,09-29 06:32:20.110  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:20.110  5684  5730 I jxcore-log: 
,09-29 06:32:20.111  5684  5730 I jxcore-log: ok 33 server should be fine
09-29 06:32:20.111  5684  5730 I jxcore-log: 
09-29 06:32:20.111  5684  5730 I jxcore-log: ok 34 server should be open
09-29 06:32:20.111  5684  5730 I jxcore-log: 
09-29 06:32:20.112  5684  5730 I jxcore-log: ok 35 incoming has been removed
09-29 06:32:20.112  5684  5730 I jxcore-log: 
09-29 06:32:20.112  5684  5730 I jxcore-log: ok 36 The mux object should be closed
09-29 06:32:20.112  5684  5730 I jxcore-log: 
09-29 06:32:20.112  5684  5730 I jxcore-log: ok 37 The mux stream should be closed
09-29 06:32:20.112  5684  5730 I jxcore-log: 
,09-29 06:32:20.120  5684  5730 I jxcore-log: # teardown
09-29 06:32:20.120  5684  5730 I jxcore-log: 
,09-29 06:32:20.157   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:20.165  5684  5730 I jxcore-log: # setup
09-29 06:32:20.165  5684  5730 I jxcore-log: 
,09-29 06:32:20.201  5684  5730 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-29 06:32:20.201  5684  5730 I jxcore-log: 
,09-29 06:32:20.256  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'creating native server'
09-29 06:32:20.256  5684  5730 I jxcore-log: 
,09-29 06:32:20.262  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'listening 43191'
09-29 06:32:20.262  5684  5730 I jxcore-log: 
,09-29 06:32:20.267  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new incoming socket'
09-29 06:32:20.267  5684  5730 I jxcore-log: 
,09-29 06:32:20.268  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'creating incoming mux'
09-29 06:32:20.268  5684  5730 I jxcore-log: 
,09-29 06:32:20.269  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new mux'
09-29 06:32:20.269  5684  5730 I jxcore-log: 
,09-29 06:32:20.275  5684  5730 I jxcore-log: ok 38 we should not have gotten an error
09-29 06:32:20.275  5684  5730 I jxcore-log: 
,09-29 06:32:20.279  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new stream: '
09-29 06:32:20.279  5684  5730 I jxcore-log: 
,09-29 06:32:20.282  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'new outgoing socket'
09-29 06:32:20.282  5684  5730 I jxcore-log: 
,09-29 06:32:20.291  5684  5730 I jxcore-log: ok 39 Buffers are identical
09-29 06:32:20.291  5684  5730 I jxcore-log: 
,09-29 06:32:20.297  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'incoming socket timeout'
09-29 06:32:20.297  5684  5730 I jxcore-log: 
,09-29 06:32:20.300  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'stream close:'
09-29 06:32:20.300  5684  5730 I jxcore-log: 
,09-29 06:32:20.303  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'mux close'
09-29 06:32:20.303  5684  5730 I jxcore-log: 
,09-29 06:32:20.308  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG createNativeListener: 'incoming socket close'
09-29 06:32:20.308  5684  5730 I jxcore-log: 
,09-29 06:32:20.308  5684  5730 I jxcore-log: ok 40 server should be fine
09-29 06:32:20.308  5684  5730 I jxcore-log: 
,09-29 06:32:20.310  5684  5730 I jxcore-log: ok 41 server should be open
09-29 06:32:20.310  5684  5730 I jxcore-log: 
09-29 06:32:20.311  5684  5730 I jxcore-log: ok 42 incoming has been removed
09-29 06:32:20.311  5684  5730 I jxcore-log: 
09-29 06:32:20.311  5684  5730 I jxcore-log: ok 43 The mux object should be closed
09-29 06:32:20.311  5684  5730 I jxcore-log: 
,09-29 06:32:20.312  5684  5730 I jxcore-log: ok 44 The mux stream should be closed
09-29 06:32:20.312  5684  5730 I jxcore-log: 
,09-29 06:32:20.318  5684  5730 I jxcore-log: # teardown
09-29 06:32:20.318  5684  5730 I jxcore-log: 
,09-29 06:32:20.370  5684  5730 I jxcore-log: # setup
09-29 06:32:20.370  5684  5730 I jxcore-log: 
,09-29 06:32:20.404  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-29 06:32:20.404  5684  5730 I jxcore-log: 
,09-29 06:32:20.593  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-29 06:32:20.593  5684  5730 I jxcore-log: 
,09-29 06:32:20.594  5684  5730 I jxcore-log: ok 45 Got right error
09-29 06:32:20.594  5684  5730 I jxcore-log: 
,09-29 06:32:20.599  5684  5730 I jxcore-log: # teardown
09-29 06:32:20.599  5684  5730 I jxcore-log: 
,09-29 06:32:20.631  5684  5730 I jxcore-log: # setup
09-29 06:32:20.631  5684  5730 I jxcore-log: 
,09-29 06:32:20.680  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-29 06:32:20.680  5684  5730 I jxcore-log: 
,09-29 06:32:20.786  5684  5730 I jxcore-log: 2016-09-29 10:32:20 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-29 06:32:20.786  5684  5730 I jxcore-log: 
,09-29 06:32:20.788  5684  5730 I jxcore-log: ok 46 Got socket hang up
09-29 06:32:20.788  5684  5730 I jxcore-log: 
,09-29 06:32:20.795  5684  5730 I jxcore-log: # teardown
09-29 06:32:20.795  5684  5730 I jxcore-log: 
,09-29 06:32:20.833  5684  5730 I jxcore-log: # setup
09-29 06:32:20.833  5684  5730 I jxcore-log: 
,09-29 06:32:20.895  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-29 06:32:20.895  5684  5730 I jxcore-log: 
,09-29 06:32:21.104  5684  5730 I jxcore-log: 2016-09-29 10:32:21 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-29 06:32:21.104  5684  5730 I jxcore-log: 
,09-29 06:32:21.105  5684  5730 I jxcore-log: ok 47 Got 500 as expected
09-29 06:32:21.105  5684  5730 I jxcore-log: 
,09-29 06:32:21.107  5684  5730 I jxcore-log: # teardown
09-29 06:32:21.107  5684  5730 I jxcore-log: 
,09-29 06:32:21.157   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 06:32:21.197  5684  5730 I jxcore-log: # setup
09-29 06:32:21.197  5684  5730 I jxcore-log: 
,09-29 06:32:21.224  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-29 06:32:21.224  5684  5730 I jxcore-log: 
,09-29 06:32:21.725   928  3027 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 06:32:22.637  5684  5730 I jxcore-log: ok 48 should be equal
09-29 06:32:22.637  5684  5730 I jxcore-log: 
,09-29 06:32:22.637  5684  5730 I jxcore-log: ok 49 revs are equal
09-29 06:32:22.637  5684  5730 I jxcore-log: 
,09-29 06:32:22.642  5684  5730 I jxcore-log: # teardown
09-29 06:32:22.642  5684  5730 I jxcore-log: 
,09-29 06:32:22.673  5684  5730 I jxcore-log: # setup
09-29 06:32:22.673  5684  5730 I jxcore-log: 
,09-29 06:32:23.609  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-29 06:32:23.609  5684  5730 I jxcore-log: 
,09-29 06:32:24.307  5684  5730 I jxcore-log: ok 50 should be equal
09-29 06:32:24.307  5684  5730 I jxcore-log: 
,09-29 06:32:24.307  5684  5730 I jxcore-log: ok 51 revs are equal
09-29 06:32:24.307  5684  5730 I jxcore-log: 
,09-29 06:32:24.311  5684  5730 I jxcore-log: # teardown
09-29 06:32:24.311  5684  5730 I jxcore-log: 
,09-29 06:32:24.417  5684  5730 I jxcore-log: # setup
09-29 06:32:24.417  5684  5730 I jxcore-log: 
,09-29 06:32:24.443  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-29 06:32:24.443  5684  5730 I jxcore-log: 
,09-29 06:32:24.968  5684  5730 I jxcore-log: ok 52 should be equal
09-29 06:32:24.968  5684  5730 I jxcore-log: 
09-29 06:32:24.968  5684  5730 I jxcore-log: ok 53 revs are equal
09-29 06:32:24.968  5684  5730 I jxcore-log: 
,09-29 06:32:25.094  5684  5730 I jxcore-log: ok 54 should be equal
09-29 06:32:25.094  5684  5730 I jxcore-log: 
,09-29 06:32:25.095  5684  5730 I jxcore-log: ok 55 revs are equal
09-29 06:32:25.095  5684  5730 I jxcore-log: 
,09-29 06:32:25.225  5684  5730 I jxcore-log: ok 56 should be equal
09-29 06:32:25.225  5684  5730 I jxcore-log: 
,09-29 06:32:25.225  5684  5730 I jxcore-log: ok 57 revs are equal
09-29 06:32:25.225  5684  5730 I jxcore-log: 
,09-29 06:32:25.230  5684  5730 I jxcore-log: # teardown
09-29 06:32:25.230  5684  5730 I jxcore-log: 
,09-29 06:32:25.318  5684  5730 I jxcore-log: # setup
09-29 06:32:25.318  5684  5730 I jxcore-log: 
,09-29 06:32:25.339  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-29 06:32:25.339  5684  5730 I jxcore-log: 
,09-29 06:32:25.918  5684  5730 I jxcore-log: 2016-09-29 10:32:25 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-29 06:32:25.918  5684  5730 I jxcore-log: 
,09-29 06:32:25.919  5684  5730 I jxcore-log: ok 58 Our rev is old so we should fail
09-29 06:32:25.919  5684  5730 I jxcore-log: 
,09-29 06:32:25.923  5684  5730 I jxcore-log: # teardown
09-29 06:32:25.923  5684  5730 I jxcore-log: 
,09-29 06:32:26.011  5684  5730 I jxcore-log: # setup
09-29 06:32:26.011  5684  5730 I jxcore-log: 
,09-29 06:32:26.034  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-29 06:32:26.034  5684  5730 I jxcore-log: 
,09-29 06:32:26.149  5684  5730 I jxcore-log: ok 59 confirm stop caused failure
09-29 06:32:26.149  5684  5730 I jxcore-log: 
,09-29 06:32:26.158   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:26.161  5684  5730 I jxcore-log: # teardown
09-29 06:32:26.161  5684  5730 I jxcore-log: 
,09-29 06:32:26.195  5684  5730 I jxcore-log: # setup
09-29 06:32:26.195  5684  5730 I jxcore-log: 
,09-29 06:32:26.268  5684  5730 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-29 06:32:26.268  5684  5730 I jxcore-log: 
,09-29 06:32:26.672  5684  5730 I jxcore-log: 2016-09-29 10:32:26 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-29 06:32:26.672  5684  5730 I jxcore-log: 
,09-29 06:32:26.674  5684  5730 I jxcore-log: ok 60 stop caused us to fail
09-29 06:32:26.674  5684  5730 I jxcore-log: 
09-29 06:32:26.675  5684  5730 I jxcore-log: ok 61 We specifically failed on a stop before put
09-29 06:32:26.675  5684  5730 I jxcore-log: 
,09-29 06:32:26.685  5684  5730 I jxcore-log: # teardown
09-29 06:32:26.685  5684  5730 I jxcore-log: 
,09-29 06:32:26.756  5684  5730 I jxcore-log: # setup
09-29 06:32:26.756  5684  5730 I jxcore-log: 
,09-29 06:32:26.810  5684  5730 I jxcore-log: # #update - fail if stop is called
09-29 06:32:26.810  5684  5730 I jxcore-log: 
,09-29 06:32:26.921  5684  5730 I jxcore-log: ok 62 failed due to stop
09-29 06:32:26.921  5684  5730 I jxcore-log: 
,09-29 06:32:26.923  5684  5730 I jxcore-log: ok 63 failed due to stop
09-29 06:32:26.923  5684  5730 I jxcore-log: 
,09-29 06:32:26.935  5684  5730 I jxcore-log: # teardown
09-29 06:32:26.935  5684  5730 I jxcore-log: 
,09-29 06:32:26.969  5684  5730 I jxcore-log: # setup
09-29 06:32:26.969  5684  5730 I jxcore-log: 
,09-29 06:32:27.041  5684  5730 I jxcore-log: # #update - set seq for first time
09-29 06:32:27.041  5684  5730 I jxcore-log: 
,09-29 06:32:27.158   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:27.551  5684  5730 I jxcore-log: ok 64 should be equal
09-29 06:32:27.551  5684  5730 I jxcore-log: 
,09-29 06:32:27.557  5684  5730 I jxcore-log: # teardown
09-29 06:32:27.557  5684  5730 I jxcore-log: 
,09-29 06:32:27.700  5684  5730 I jxcore-log: # setup
09-29 06:32:27.700  5684  5730 I jxcore-log: 
,09-29 06:32:27.989  5684  5730 I jxcore-log: # #update - Fail on bad seq value
09-29 06:32:27.989  5684  5730 I jxcore-log: 
,09-29 06:32:28.160   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:29.161   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:29.765  5684  5730 I jxcore-log: 2016-09-29 10:32:29 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-29 06:32:29.765  5684  5730 I jxcore-log: 
,09-29 06:32:29.769  5684  5730 I jxcore-log: ok 65 Expected bad seq error
09-29 06:32:29.769  5684  5730 I jxcore-log: 
,09-29 06:32:29.776  5684  5730 I jxcore-log: # teardown
09-29 06:32:29.776  5684  5730 I jxcore-log: 
,09-29 06:32:29.850  5684  5730 I jxcore-log: # setup
09-29 06:32:29.850  5684  5730 I jxcore-log: 
,09-29 06:32:30.163   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:30.553  5684  5730 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-29 06:32:30.553  5684  5730 I jxcore-log: 
,09-29 06:32:31.164   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 06:32:31.622  5684  5730 I jxcore-log: ok 66 Different promises
09-29 06:32:31.622  5684  5730 I jxcore-log: 
,09-29 06:32:31.624  5684  5730 I jxcore-log: ok 67 Timer was cancelled
09-29 06:32:31.624  5684  5730 I jxcore-log: 
,09-29 06:32:31.787  5684  5730 I jxcore-log: ok 68 should be equal
09-29 06:32:31.787  5684  5730 I jxcore-log: 
,09-29 06:32:31.796  5684  5730 I jxcore-log: # teardown
09-29 06:32:31.796  5684  5730 I jxcore-log: 
,09-29 06:32:33.046  5684  5730 I jxcore-log: # setup
09-29 06:32:33.046  5684  5730 I jxcore-log: 
,09-29 06:32:33.425  5684  5730 I jxcore-log: # #update - do we wait for blocked update
09-29 06:32:33.425  5684  5730 I jxcore-log: 
,09-29 06:32:33.540  5684  5730 I jxcore-log: ok 69 One go and one blocked
09-29 06:32:33.540  5684  5730 I jxcore-log: 
,09-29 06:32:33.540  5684  5730 I jxcore-log: ok 70 All blocked
09-29 06:32:33.540  5684  5730 I jxcore-log: 
09-29 06:32:33.541  5684  5730 I jxcore-log: ok 71 Still blocked
09-29 06:32:33.541  5684  5730 I jxcore-log: 
,09-29 06:32:34.057  5684  5730 I jxcore-log: ok 72 should be equal
09-29 06:32:34.057  5684  5730 I jxcore-log: 
,09-29 06:32:34.062  5684  5730 I jxcore-log: # teardown
09-29 06:32:34.062  5684  5730 I jxcore-log: 
,09-29 06:32:34.110  5684  5730 I jxcore-log: # setup
09-29 06:32:34.110  5684  5730 I jxcore-log: 
,09-29 06:32:34.748  5684  5730 I jxcore-log: # #update - test that we wait long enough
09-29 06:32:34.748  5684  5730 I jxcore-log: 
,09-29 06:32:37.190  5684  5730 I jxcore-log: ok 73 We waited long enough
09-29 06:32:37.190  5684  5730 I jxcore-log: 
,09-29 06:32:37.283  5684  5730 I jxcore-log: ok 74 should be equal
09-29 06:32:37.283  5684  5730 I jxcore-log: 
,09-29 06:32:37.290  5684  5730 I jxcore-log: # teardown
09-29 06:32:37.290  5684  5730 I jxcore-log: 
,09-29 06:32:37.533  5684  5730 I jxcore-log: # setup
09-29 06:32:37.533  5684  5730 I jxcore-log: 
,09-29 06:32:37.557  5684  5730 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-29 06:32:37.557  5684  5730 I jxcore-log: 
,09-29 06:32:38.065  5684  5730 I jxcore-log: ok 75 Should have gotten same timer promise
09-29 06:32:38.065  5684  5730 I jxcore-log: 
09-29 06:32:38.066  5684  5730 I jxcore-log: ok 76 Still same timer promise
09-29 06:32:38.066  5684  5730 I jxcore-log: 
,09-29 06:32:38.791  5684  5730 I jxcore-log: ok 77 We waited long enough
09-29 06:32:38.791  5684  5730 I jxcore-log: 
,09-29 06:32:38.885  5684  5730 I jxcore-log: ok 78 should be equal
09-29 06:32:38.885  5684  5730 I jxcore-log: 
,09-29 06:32:38.896  5684  5730 I jxcore-log: # teardown
09-29 06:32:38.896  5684  5730 I jxcore-log: 
,09-29 06:32:38.942  5684  5730 I jxcore-log: # setup
09-29 06:32:38.942  5684  5730 I jxcore-log: 
,09-29 06:32:39.014  5684  5730 I jxcore-log: # Coordinated seq test
09-29 06:32:39.014  5684  5730 I jxcore-log: 
,09-29 06:32:39.018  5684  5730 I jxcore-log: 2016-09-29 10:32:39 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-29 06:32:39.018  5684  5730 I jxcore-log: 
,09-29 06:32:39.101  5684  5730 I jxcore-log: # teardown
09-29 06:32:39.101  5684  5730 I jxcore-log: 
,09-29 06:32:39.150  5684  5730 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
09-29 06:32:39.150  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 06:32:39.150  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 06:32:39.150  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 06:32:39.168  5684  5730 I jxcore-log: # setup
09-29 06:32:39.168  5684  5730 I jxcore-log: 
,09-29 06:32:39.203  5684  5730 I jxcore-log: # closeAll can close even when connections open
09-29 06:32:39.203  5684  5730 I jxcore-log: 
,09-29 06:32:39.362  5684  5730 I jxcore-log: ok 79 not possible to connect to the server anymore
09-29 06:32:39.362  5684  5730 I jxcore-log: 
,09-29 06:32:39.375  5684  5730 I jxcore-log: # teardown
09-29 06:32:39.375  5684  5730 I jxcore-log: 
,09-29 06:32:39.404  5684  5730 I jxcore-log: # setup
09-29 06:32:39.404  5684  5730 I jxcore-log: 
,09-29 06:32:39.464  5684  5730 I jxcore-log: # closeAll with promise
09-29 06:32:39.464  5684  5730 I jxcore-log: 
,09-29 06:32:39.629  5684  5730 I jxcore-log: ok 80 not possible to connect to the server anymore
09-29 06:32:39.629  5684  5730 I jxcore-log: 
,09-29 06:32:39.642  5684  5730 I jxcore-log: # teardown
09-29 06:32:39.642  5684  5730 I jxcore-log: 
,09-29 06:32:39.676  5684  5730 I jxcore-log: # setup
09-29 06:32:39.676  5684  5730 I jxcore-log: 
,09-29 06:32:39.757  5684  5730 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-29 06:32:39.757  5684  5730 I jxcore-log: 
,09-29 06:32:39.900  5684  5730 I jxcore-log: ok 81 Got the right error
09-29 06:32:39.900  5684  5730 I jxcore-log: 
,09-29 06:32:39.917  5684  5730 I jxcore-log: # teardown
09-29 06:32:39.917  5684  5730 I jxcore-log: 
,09-29 06:32:39.975  5684  5730 I jxcore-log: # setup
09-29 06:32:39.975  5684  5730 I jxcore-log: 
,09-29 06:32:40.017  5684  5730 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-29 06:32:40.017  5684  5730 I jxcore-log: 
,09-29 06:32:40.173  5684  5730 I jxcore-log: # teardown
09-29 06:32:40.173  5684  5730 I jxcore-log: 
,09-29 06:32:40.225  5684  5730 I jxcore-log: # setup
09-29 06:32:40.225  5684  5730 I jxcore-log: 
,09-29 06:32:40.265  5684  5730 I jxcore-log: # onPeerLost calls jxcore
09-29 06:32:40.265  5684  5730 I jxcore-log: 
,09-29 06:32:40.311  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 06:32:40.312  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5aad969 added. We now have 3 listener(s)
,09-29 06:32:40.314  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 06:32:40.314  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:32:40.314  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:32:40.315  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:32:40.315  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@832bfee added. We now have 4 listener(s)
09-29 06:32:40.315  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 06:32:40.316  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:32:40.323  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:32:40.330  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:32:40.331  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:32:40.332  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:32:40.332  5684  5730 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-29 06:32:40.332  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-29 06:32:40.336  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:32:40.340  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:32:41.166   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:41.730   928  3027 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 06:32:42.167   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:42.337  5684  5730 I jxcore-log: onPeerLost
09-29 06:32:42.337  5684  5730 I jxcore-log: 
,09-29 06:32:42.341  5684  5730 I jxcore-log: 2016-09-29 10:32:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:42.341  5684  5730 I jxcore-log: 
,09-29 06:32:42.361  5684  5730 I jxcore-log: # teardown
09-29 06:32:42.361  5684  5730 I jxcore-log: 
,09-29 06:32:42.369  5684  5730 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-29 06:32:42.369  5684  5730 I jxcore-log: 
,09-29 06:32:42.370  5684  5730 I jxcore-log: ok 83 check if peerAvailable is false
09-29 06:32:42.370  5684  5730 I jxcore-log: 
,09-29 06:32:42.411  5684  5730 I jxcore-log: 2016-09-29 10:32:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 06:32:42.411  5684  5730 I jxcore-log: 
,09-29 06:32:42.415  5684  5730 I jxcore-log: 2016-09-29 10:32:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 06:32:42.415  5684  5730 I jxcore-log: 
,09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:32:42.426  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:32:42.430  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:32:42.434  5684  5730 I jxcore-log: 2016-09-29 10:32:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 06:32:42.434  5684  5730 I jxcore-log: 
,09-29 06:32:42.437  5684  5730 I jxcore-log: 2016-09-29 10:32:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 06:32:42.437  5684  5730 I jxcore-log: 
,09-29 06:32:42.443  5684  5730 I jxcore-log: 2016-09-29 10:32:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:42.443  5684  5730 I jxcore-log: 
,09-29 06:32:42.448  5684  5730 I jxcore-log: # setup
09-29 06:32:42.448  5684  5730 I jxcore-log: 
,09-29 06:32:43.169   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:44.170   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:44.479  5684  5730 I jxcore-log: # onPeerDiscovered calls jxcore
09-29 06:32:44.479  5684  5730 I jxcore-log: 
,09-29 06:32:44.556  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 06:32:44.557  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bdfb1c added. We now have 4 listener(s)
,09-29 06:32:44.558  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 06:32:44.559  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 06:32:44.559  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 06:32:44.559  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 06:32:44.559  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0ea325 added. We now have 5 listener(s)
09-29 06:32:44.559  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 06:32:44.560  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 06:32:44.564  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:32:44.571  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 06:32:44.574  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 06:32:44.574  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 06:32:44.574  5684  5730 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-29 06:32:44.580  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:32:44.584  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 06:32:45.175   542   542 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 06:32:46.176   542   542 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 06:32:46.580  5684  5730 I jxcore-log: onPeerDiscovered
09-29 06:32:46.580  5684  5730 I jxcore-log: 
,09-29 06:32:46.585  5684  5730 I jxcore-log: 2016-09-29 10:32:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:46.585  5684  5730 I jxcore-log: 
,09-29 06:32:46.598  5684  5730 I jxcore-log: # teardown
09-29 06:32:46.598  5684  5730 I jxcore-log: 
,09-29 06:32:46.605  5684  5730 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-29 06:32:46.605  5684  5730 I jxcore-log: 
,09-29 06:32:46.607  5684  5730 I jxcore-log: ok 85 check if peerAvailable is true
09-29 06:32:46.607  5684  5730 I jxcore-log: 
,09-29 06:32:47.533  5684  5730 I jxcore-log: 2016-09-29 10:32:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 06:32:47.533  5684  5730 I jxcore-log: 
,09-29 06:32:47.538  5684  5730 I jxcore-log: 2016-09-29 10:32:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 06:32:47.538  5684  5730 I jxcore-log: 
,09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 06:32:47.552  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 06:32:47.555  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 06:32:47.558  5684  5730 I jxcore-log: 2016-09-29 10:32:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 06:32:47.558  5684  5730 I jxcore-log: 
09-29 06:32:47.562  5684  5730 I jxcore-log: 2016-09-29 10:32:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 06:32:47.562  5684  5730 I jxcore-log: 
,09-29 06:32:47.571  5684  5730 I jxcore-log: 2016-09-29 10:32:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 06:32:47.571  5684  5730 I jxcore-log: 
,09-29 06:32:47.577  5684  5730 I jxcore-log: # setup
09-29 06:32:47.577  5684  5730 I jxcore-log: 
,09-29 06:32:47.966  5684  5730 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-29 06:32:47.966  5684  5730 I jxcore-log: 
,09-29 06:32:48.312  5684  5730 I jxcore-log: # teardown
09-29 06:32:48.312  5684  5730 I jxcore-log: 
,09-29 06:32:48.425  5684  5730 I jxcore-log: # setup
09-29 06:32:48.425  5684  5730 I jxcore-log: 
,09-29 06:32:48.476  5684  5730 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-29 06:32:48.476  5684  5730 I jxcore-log: 
,09-29 06:32:48.797  5684  5730 I jxcore-log: # teardown
09-29 06:32:48.797  5684  5730 I jxcore-log: 
,09-29 06:32:48.931  5684  5730 I jxcore-log: # setup
09-29 06:32:48.931  5684  5730 I jxcore-log: 
,09-29 06:32:49.015  5684  5730 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-29 06:32:49.015  5684  5730 I jxcore-log: 
,09-29 06:32:50.345  5684  5730 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-29 06:32:50.345  5684  5730 I jxcore-log: 
,09-29 06:32:50.362  5684  5730 I jxcore-log: # teardown
09-29 06:32:50.362  5684  5730 I jxcore-log: 
,09-29 06:32:50.433  5684  5730 I jxcore-log: # setup
09-29 06:32:50.433  5684  5730 I jxcore-log: 
,09-29 06:32:50.488  5684  5730 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-29 06:32:50.488  5684  5730 I jxcore-log: 
,09-29 06:32:51.092  5684  5730 I jxcore-log: # teardown
09-29 06:32:51.092  5684  5730 I jxcore-log: 
,09-29 06:32:51.174  5684  5730 I jxcore-log: # setup
09-29 06:32:51.174  5684  5730 I jxcore-log: 
,09-29 06:32:51.212  5684  5730 I jxcore-log: # test defaultDirectory
09-29 06:32:51.212  5684  5730 I jxcore-log: 
,09-29 06:32:51.252  5684  5730 I jxcore-log: ok 87 should be equal
09-29 06:32:51.252  5684  5730 I jxcore-log: 
,09-29 06:32:51.255  5684  5730 I jxcore-log: ok 88 should be equal
09-29 06:32:51.255  5684  5730 I jxcore-log: 
,09-29 06:32:51.258  5684  5730 I jxcore-log: ok 89 should be equal
09-29 06:32:51.258  5684  5730 I jxcore-log: 
,09-29 06:32:51.269  5684  5730 I jxcore-log: # teardown
09-29 06:32:51.269  5684  5730 I jxcore-log: 
,09-29 06:32:51.319  5684  5730 I jxcore-log: # setup
09-29 06:32:51.319  5684  5730 I jxcore-log: 
,09-29 06:32:51.347  5684  5730 I jxcore-log: # test defaultAdapter
09-29 06:32:51.347  5684  5730 I jxcore-log: 
,09-29 06:32:51.374  5684  5730 I jxcore-log: ok 90 should be equal
09-29 06:32:51.374  5684  5730 I jxcore-log: 
,09-29 06:32:51.375  5684  5730 I jxcore-log: ok 91 should be equal
09-29 06:32:51.375  5684  5730 I jxcore-log: 
,09-29 06:32:51.378  5684  5730 I jxcore-log: ok 92 should be equal
09-29 06:32:51.378  5684  5730 I jxcore-log: 
09-29 06:32:51.378  5684  5730 I jxcore-log: ok 93 should be equal
09-29 06:32:51.378  5684  5730 I jxcore-log: 
,09-29 06:32:51.383  5684  5730 I jxcore-log: ok 94 should be equal
09-29 06:32:51.383  5684  5730 I jxcore-log: 
,09-29 06:32:51.384  5684  5730 I jxcore-log: ok 95 should be equal
09-29 06:32:51.384  5684  5730 I jxcore-log: 
,09-29 06:32:51.509  5684  5730 I jxcore-log: ok 96 should be equal
09-29 06:32:51.509  5684  5730 I jxcore-log: 
09-29 06:32:51.510  5684  5730 I jxcore-log: ok 97 should be equal
09-29 06:32:51.510  5684  5730 I jxcore-log: 
,09-29 06:32:51.517  5684  5730 I jxcore-log: # teardown
09-29 06:32:51.517  5684  5730 I jxcore-log: 
,09-29 06:32:51.663  5684  5730 I jxcore-log: # setup
09-29 06:32:51.663  5684  5730 I jxcore-log: 
,09-29 06:32:51.704  5684  5730 I jxcore-log: # enqueue and run in order
09-29 06:32:51.704  5684  5730 I jxcore-log: 
,09-29 06:32:51.841  5684  5730 I jxcore-log: ok 98 firstPromise setTimeout
09-29 06:32:51.841  5684  5730 I jxcore-log: 
,09-29 06:32:51.845  5684  5730 I jxcore-log: ok 99 firstPromise result
09-29 06:32:51.845  5684  5730 I jxcore-log: 
09-29 06:32:51.846  5684  5730 I jxcore-log: ok 100 firstPromise testValue
09-29 06:32:51.846  5684  5730 I jxcore-log: 
,09-29 06:32:51.953  5684  5730 I jxcore-log: ok 101 secondPromise setTimeout
09-29 06:32:51.953  5684  5730 I jxcore-log: 
,09-29 06:32:51.961  5684  5730 I jxcore-log: ok 102 secondPromise result
09-29 06:32:51.961  5684  5730 I jxcore-log: 
,09-29 06:32:51.967  5684  5730 I jxcore-log: ok 103 secondPromise testValue
09-29 06:32:51.967  5684  5730 I jxcore-log: 
,09-29 06:32:51.969  5684  5730 I jxcore-log: ok 104 thirdPromise in promise
09-29 06:32:51.969  5684  5730 I jxcore-log: 
,09-29 06:32:51.974  5684  5730 I jxcore-log: ok 105 thirdPromise result
09-29 06:32:51.974  5684  5730 I jxcore-log: 
,09-29 06:32:51.976  5684  5730 I jxcore-log: ok 106 thirdPromise testValue
09-29 06:32:51.976  5684  5730 I jxcore-log: 
,09-29 06:32:51.989  5684  5730 I jxcore-log: # teardown
09-29 06:32:51.989  5684  5730 I jxcore-log: 
,09-29 06:32:52.032  5684  5730 I jxcore-log: # setup
09-29 06:32:52.032  5684  5730 I jxcore-log: 
,09-29 06:32:52.296  5684  5730 I jxcore-log: # enqueueAtTop and run backwards
09-29 06:32:52.296  5684  5730 I jxcore-log: 
,09-29 06:32:53.290  5684  5730 I jxcore-log: ok 107 thirdPromise - first to run
09-29 06:32:53.290  5684  5730 I jxcore-log: 
,09-29 06:32:53.293  5684  5730 I jxcore-log: ok 108 thirdPromise - in resolve
09-29 06:32:53.293  5684  5730 I jxcore-log: 
,09-29 06:32:53.295  5684  5730 I jxcore-log: ok 109 secondPromise - second to run
09-29 06:32:53.295  5684  5730 I jxcore-log: 
,09-29 06:32:53.298  5684  5730 I jxcore-log: ok 110 secondPromise - in catch
09-29 06:32:53.298  5684  5730 I jxcore-log: 
,09-29 06:32:53.300  5684  5730 I jxcore-log: ok 111 firstPromise - third to run
09-29 06:32:53.300  5684  5730 I jxcore-log: 
,09-29 06:32:53.303  5684  5730 I jxcore-log: ok 112 firstPromise - in then
09-29 06:32:53.303  5684  5730 I jxcore-log: 
,09-29 06:32:53.304  5684  5730 I jxcore-log: ok 113 testing promises
09-29 06:32:53.304  5684  5730 I jxcore-log: 
,09-29 06:32:53.315  5684  5730 I jxcore-log: # teardown
09-29 06:32:53.315  5684  5730 I jxcore-log: 
,09-29 06:32:54.003  5684  5730 I jxcore-log: # setup
09-29 06:32:54.003  5684  5730 I jxcore-log: 
,09-29 06:32:54.528  5684  5730 I jxcore-log: # mix enqueue and enqueueAtTop
09-29 06:32:54.528  5684  5730 I jxcore-log: 
,09-29 06:32:55.120  5684  5730 I jxcore-log: ok 114 fourth
09-29 06:32:55.120  5684  5730 I jxcore-log: 
,09-29 06:32:55.137  5684  5730 I jxcore-log: ok 115 fourth
09-29 06:32:55.137  5684  5730 I jxcore-log: 
,09-29 06:32:55.140  5684  5730 I jxcore-log: ok 116 second
09-29 06:32:55.140  5684  5730 I jxcore-log: 
,09-29 06:32:55.143  5684  5730 I jxcore-log: ok 117 secondPromise - in then
09-29 06:32:55.143  5684  5730 I jxcore-log: 
,09-29 06:32:55.249  5684  5730 I jxcore-log: ok 118 first
09-29 06:32:55.249  5684  5730 I jxcore-log: 
,09-29 06:32:55.252  5684  5730 I jxcore-log: ok 119 firstPromise - in catch
09-29 06:32:55.252  5684  5730 I jxcore-log: 
,09-29 06:32:55.257  5684  5730 I jxcore-log: ok 120 third
09-29 06:32:55.257  5684  5730 I jxcore-log: 
,09-29 06:32:55.260  5684  5730 I jxcore-log: ok 121 thirdPromise - in then
09-29 06:32:55.260  5684  5730 I jxcore-log: 
,09-29 06:32:55.262  5684  5730 I jxcore-log: ok 122 testingPromises
09-29 06:32:55.262  5684  5730 I jxcore-log: 
,09-29 06:32:55.274  5684  5730 I jxcore-log: # teardown
09-29 06:32:55.274  5684  5730 I jxcore-log: 
,09-29 06:32:55.944  5684  5730 I jxcore-log: # setup
09-29 06:32:55.944  5684  5730 I jxcore-log: 
,09-29 06:32:56.658  5684  5730 I jxcore-log: # queues handled independently
09-29 06:32:56.658  5684  5730 I jxcore-log: 
,09-29 06:32:56.731  5684  5730 I jxcore-log: ok 123 all short operations completed before the long resolves
09-29 06:32:56.731  5684  5730 I jxcore-log: 
,09-29 06:32:56.746  5684  5730 I jxcore-log: # teardown
09-29 06:32:56.746  5684  5730 I jxcore-log: 
,09-29 06:32:56.804  5684  5730 I jxcore-log: # setup
09-29 06:32:56.804  5684  5730 I jxcore-log: 
,09-29 06:32:56.859  5684  5730 I jxcore-log: # basic
09-29 06:32:56.859  5684  5730 I jxcore-log: 
,09-29 06:32:56.898  5684  5730 I jxcore-log: ok 124 sane
09-29 06:32:56.898  5684  5730 I jxcore-log: 
,09-29 06:32:56.912  5684  5730 I jxcore-log: # teardown
09-29 06:32:56.912  5684  5730 I jxcore-log: 
,09-29 06:32:56.956  5684  5730 I jxcore-log: # setup
09-29 06:32:56.956  5684  5730 I jxcore-log: 
,09-29 06:32:56.988  5684  5730 I jxcore-log: # another
09-29 06:32:56.988  5684  5730 I jxcore-log: 
,09-29 06:32:57.027  5684  5730 I jxcore-log: ok 125 sane
09-29 06:32:57.027  5684  5730 I jxcore-log: 
,09-29 06:32:57.037  5684  5730 I jxcore-log: # teardown
09-29 06:32:57.037  5684  5730 I jxcore-log: 
,09-29 06:32:57.069  5684  5730 I jxcore-log: # setup
09-29 06:32:57.069  5684  5730 I jxcore-log: 
,09-29 06:32:57.103  5684  5730 I jxcore-log: # can pass data in setup
09-29 06:32:57.103  5684  5730 I jxcore-log: 
,09-29 06:32:57.134  5684  5730 I jxcore-log: ok 126 test participant has uuid
09-29 06:32:57.134  5684  5730 I jxcore-log: 
,09-29 06:32:57.134  5684  5730 I jxcore-log: ok 127 participant data matches
09-29 06:32:57.134  5684  5730 I jxcore-log: 
09-29 06:32:57.135  5684  5730 I jxcore-log: ok 128 test participant has uuid
09-29 06:32:57.135  5684  5730 I jxcore-log: 
09-29 06:32:57.135  5684  5730 I jxcore-log: ok 129 participant data matches
09-29 06:32:57.135  5684  5730 I jxcore-log: 
,09-29 06:32:57.136  5684  5730 I jxcore-log: ok 130 test participant has uuid
09-29 06:32:57.136  5684  5730 I jxcore-log: 
09-29 06:32:57.137  5684  5730 I jxcore-log: ok 131 participant data matches
09-29 06:32:57.137  5684  5730 I jxcore-log: 
09-29 06:32:57.137  5684  5730 I jxcore-log: ok 132 own UUID is found from the participants list
09-29 06:32:57.137  5684  5730 I jxcore-log: 
,09-29 06:32:57.146  5684  5730 I jxcore-log: # teardown
09-29 06:32:57.146  5684  5730 I jxcore-log: 
,09-29 06:32:57.190  5684  5730 I jxcore-log: # setup
09-29 06:32:57.190  5684  5730 I jxcore-log: 
,09-29 06:32:57.230  5684  5730 I jxcore-log: # test thali manager spies
09-29 06:32:57.230  5684  5730 I jxcore-log: 
,09-29 06:32:57.370  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 06:32:57.370  5684  5730 I jxcore-log: 
,09-29 06:32:57.375  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 06:32:57.375  5684  5730 I jxcore-log: 
,09-29 06:32:57.376  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 06:32:57.376  5684  5730 I jxcore-log: 
,09-29 06:32:57.392  5684  5730 I jxcore-log: ok 133 expressPouchDB was called once
09-29 06:32:57.392  5684  5730 I jxcore-log: 
,09-29 06:32:57.393  5684  5730 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-29 06:32:57.393  5684  5730 I jxcore-log: 
09-29 06:32:57.393  5684  5730 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-29 06:32:57.393  5684  5730 I jxcore-log: 
09-29 06:32:57.394  5684  5730 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-29 06:32:57.394  5684  5730 I jxcore-log: 
09-29 06:32:57.394  5684  5730 I jxcore-log: ok 137 PouchDB was called once
09-29 06:32:57.394  5684  5730 I jxcore-log: 
,09-29 06:32:57.394  5684  5730 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-29 06:32:57.394  5684  5730 I jxcore-log: 
09-29 06:32:57.394  5684  5730 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-29 06:32:57.394  5684  5730 I jxcore-log: 
09-29 06:32:57.395  5684  5730 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-29 06:32:57.395  5684  5730 I jxcore-log: 
09-29 06:32:57.395  5684  5730 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-29 06:32:57.395  5684  5730 I jxcore-log: 
09-29 06:32:57.395  5684  5730 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-29 06:32:57.395  5684  5730 I jxcore-log: 
09-29 06:32:57.396  5684  5730 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-29 06:32:57.396  5684  5730 I jxcore-log: 
09-29 06:32:57.396  5684  5730 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-29 06:32:57.396  5684  5730 I jxcore-log: 
09-29 06:32:57.396  5684  5730 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-29 06:32:57.396  5684  5730 I jxcore-log: 
09-29 06:32:57.396  5684  5730 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-29 06:32:57.396  5684  5730 I jxcore-log: 
,09-29 06:32:57.397  5684  5730 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-29 06:32:57.397  5684  5730 I jxcore-log: 
09-29 06:32:57.397  5684  5730 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-29 06:32:57.397  5684  5730 I jxcore-log: 
09-29 06:32:57.397  5684  5730 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-29 06:32:57.397  5684  5730 I jxcore-log: 
09-29 06:32:57.397  5684  5730 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-29 06:32:57.397  5684  5730 I jxcore-log: 
09-29 06:32:57.398  5684  5730 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-29 06:32:57.398  5684  5730 I jxcore-log: 
09-29 06:32:57.398  5684  5730 I jxcore-log: ok 152 Salti was called once
09-29 06:32:57.398  5684  5730 I jxcore-log: 
09-29 06:32:57.398  5684  5730 I jxcore-log: ok 153 Salti was called with 4 arguments
09-29 06:32:57.398  5684  5730 I jxcore-log: 
09-29 06:32:57.398  5684  5730 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-29 06:32:57.398  5684  5730 I jxcore-log: 
09-29 06:32:57.398  5684  5730 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-29 06:32:57.398  5684  5730 I jxcore-log: 
,09-29 06:32:57.399  5684  5730 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-29 06:32:57.399  5684  5730 I jxcore-log: 
09-29 06:32:57.400  5684  5730 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-29 06:32:57.400  5684  5730 I jxcore-log: 
,09-29 06:32:57.401  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 06:32:57.401  5684  5730 I jxcore-log: 
,09-29 06:32:57.402  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 06:32:57.402  5684  5730 I jxcore-log: 
,09-29 06:32:57.403  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting ThaliMobile',
09-29 06:32:57.403  5684  5730 I jxcore-log: 
09-29 06:32:57.406  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start listening for advertisements'
09-29 06:32:57.406  5684  5730 I jxcore-log: 
,09-29 06:32:57.410  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start update advertising and listening'
09-29 06:32:57.410  5684  5730 I jxcore-log: 
,09-29 06:32:57.435  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliWifiInfrastructure: 'listening 37104'
09-29 06:32:57.435  5684  5730 I jxcore-log: 
,09-29 06:32:57.438  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 06:32:57.438  5684  5730 I jxcore-log: 
,09-29 06:32:57.457  5684  5730 I jxcore-log: ok 158 ThaliMobile.start was called once
09-29 06:32:57.457  5684  5730 I jxcore-log: 
,09-29 06:32:57.457  5684  5730 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-29 06:32:57.457  5684  5730 I jxcore-log: 
09-29 06:32:57.458  5684  5730 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 06:32:57.458  5684  5730 I jxcore-log: 
09-29 06:32:57.458  5684  5730 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 06:32:57.458  5684  5730 I jxcore-log: 
09-29 06:32:57.458  5684  5730 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-29 06:32:57.458  5684  5730 I jxcore-log: 
09-29 06:32:57.458  5684  5730 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 06:32:57.458  5684  5730 I jxcore-log: 
,09-29 06:32:57.458  5684  5730 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 06:32:57.458  5684  5730 I jxcore-log: 
09-29 06:32:57.459  5684  5730 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 06:32:57.459  5684  5730 I jxcore-log: 
09-29 06:32:57.459  5684  5730 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 06:32:57.459  5684  5730 I jxcore-log: 
09-29 06:32:57.459  5684  5730 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 06:32:57.459  5684  5730 I jxcore-log: 
09-29 06:32:57.459  5684  5730 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 06:32:57.459  5684  5730 I jxcore-log: 
09-29 06:32:57.460  5684  5730 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 06:32:57.460  5684  5730 I jxcore-log: 
09-29 06:32:57.460  5684  5730 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 06:32:57.460  5684  5730 I jxcore-log: 
,09-29 06:32:57.460  5684  5730 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 06:32:57.460  5684  5730 I jxcore-log: 
09-29 06:32:57.460  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 06:32:57.460  5684  5730 I jxcore-log: 
09-29 06:32:57.461  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 06:32:57.461  5684  5730 I jxcore-log: 
,09-29 06:32:57.463  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 06:32:57.463  5684  5730 I jxcore-log: 
,09-29 06:32:57.464  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 06:32:57.464  5684  5730 I jxcore-log: 
,09-29 06:32:57.468  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 06:32:57.468  5684  5730 I jxcore-log: 
,09-29 06:32:57.470  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 06:32:57.470  5684  5730 I jxcore-log: 
,09-29 06:32:57.473  5684  5730 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-29 06:32:57.473  5684  5730 I jxcore-log: 
09-29 06:32:57.473  5684  5730 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-29 06:32:57.473  5684  5730 I jxcore-log: 
09-29 06:32:57.474  5684  5730 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-29 06:32:57.474  5684  5730 I jxcore-log: 
09-29 06:32:57.474  5684  5730 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-29 06:32:57.474  5684  5730 I jxcore-log: 
09-29 06:32:57.474  5684  5730 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-29 06:32:57.474  5684  5730 I jxcore-log: 
09-29 06:32:57.474  5684  5730 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-29 06:32:57.474  5684  5730 I jxcore-log: 
,09-29 06:32:57.474  5684  5730 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-29 06:32:57.474  5684  5730 I jxcore-log: 
09-29 06:32:57.475  5684  5730 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-29 06:32:57.475  5684  5730 I jxcore-log: 
09-29 06:32:57.475  5684  5730 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-29 06:32:57.475  5684  5730 I jxcore-log: 
09-29 06:32:57.475  5684  5730 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-29 06:32:57.475  5684  5730 I jxcore-log: 
,09-29 06:32:57.483  5684  5730 I jxcore-log: # teardown
09-29 06:32:57.483  5684  5730 I jxcore-log: 
,09-29 06:32:57.542  5684  5730 I jxcore-log: # setup
09-29 06:32:57.542  5684  5730 I jxcore-log: 
,09-29 06:32:57.582  5684  5730 I jxcore-log: # test thali manager multiple starts and stops
09-29 06:32:57.582  5684  5730 I jxcore-log: 
,09-29 06:32:57.774  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 06:32:57.774  5684  5730 I jxcore-log: 
,09-29 06:32:57.780  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 06:32:57.780  5684  5730 I jxcore-log: 
,09-29 06:32:57.782  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 06:32:57.782  5684  5730 I jxcore-log: 
,09-29 06:32:57.803  5684  5730 I jxcore-log: ok 182 expressPouchDB was called once
09-29 06:32:57.803  5684  5730 I jxcore-log: 
09-29 06:32:57.804  5684  5730 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-29 06:32:57.804  5684  5730 I jxcore-log: 
,09-29 06:32:57.804  5684  5730 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-29 06:32:57.804  5684  5730 I jxcore-log: 
09-29 06:32:57.804  5684  5730 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-29 06:32:57.804  5684  5730 I jxcore-log: 
09-29 06:32:57.804  5684  5730 I jxcore-log: ok 186 PouchDB was called once
09-29 06:32:57.804  5684  5730 I jxcore-log: 
09-29 06:32:57.805  5684  5730 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-29 06:32:57.805  5684  5730 I jxcore-log: 
09-29 06:32:57.805  5684  5730 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-29 06:32:57.805  5684  5730 I jxcore-log: 
09-29 06:32:57.805  5684  5730 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-29 06:32:57.805  5684  5730 I jxcore-log: 
,09-29 06:32:57.805  5684  5730 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-29 06:32:57.805  5684  5730 I jxcore-log: 
09-29 06:32:57.806  5684  5730 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-29 06:32:57.806  5684  5730 I jxcore-log: 
09-29 06:32:57.806  5684  5730 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-29 06:32:57.806  5684  5730 I jxcore-log: 
09-29 06:32:57.806  5684  5730 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-29 06:32:57.806  5684  5730 I jxcore-log: 
09-29 06:32:57.806  5684  5730 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-29 06:32:57.806  5684  5730 I jxcore-log: 
,09-29 06:32:57.807  5684  5730 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-29 06:32:57.807  5684  5730 I jxcore-log: 
,09-29 06:32:57.807  5684  5730 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-29 06:32:57.807  5684  5730 I jxcore-log: 
09-29 06:32:57.807  5684  5730 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-29 06:32:57.807  5684  5730 I jxcore-log: 
09-29 06:32:57.807  5684  5730 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-29 06:32:57.807  5684  5730 I jxcore-log: 
09-29 06:32:57.807  5684  5730 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-29 06:32:57.807  5684  5730 I jxcore-log: 
09-29 06:32:57.808  5684  5730 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-29 06:32:57.808  5684  5730 I jxcore-log: 
09-29 06:32:57.808  5684  5730 I jxcore-log: ok 201 Salti was called once
09-29 06:32:57.808  5684  5730 I jxcore-log: 
,09-29 06:32:57.808  5684  5730 I jxcore-log: ok 202 Salti was called with 4 arguments
09-29 06:32:57.808  5684  5730 I jxcore-log: 
09-29 06:32:57.808  5684  5730 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-29 06:32:57.808  5684  5730 I jxcore-log: 
09-29 06:32:57.808  5684  5730 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-29 06:32:57.808  5684  5730 I jxcore-log: 
09-29 06:32:57.808  5684  5730 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-29 06:32:57.808  5684  5730 I jxcore-log: 
09-29 06:32:57.809  5684  5730 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-29 06:32:57.809  5684  5730 I jxcore-log: 
09-29 06:32:57.810  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 06:32:57.810  5684  5730 I jxcore-log: 
,09-29 06:32:57.810  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 06:32:57.810  5684  5730 I jxcore-log: 
,09-29 06:32:57.811  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 06:32:57.811  5684  5730 I jxcore-log: 
,09-29 06:32:57.815  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start listening for advertisements'
09-29 06:32:57.815  5684  5730 I jxcore-log: 
,09-29 06:32:57.819  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start update advertising and listening'
09-29 06:32:57.819  5684  5730 I jxcore-log: 
,09-29 06:32:57.825  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliWifiInfrastructure: 'listening 43139'
09-29 06:32:57.825  5684  5730 I jxcore-log: 
,09-29 06:32:57.826  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 06:32:57.826  5684  5730 I jxcore-log: 
,09-29 06:32:57.893  5684  5730 I jxcore-log: ok 207 ThaliMobile.start was called once
09-29 06:32:57.893  5684  5730 I jxcore-log: 
09-29 06:32:57.893  5684  5730 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-29 06:32:57.893  5684  5730 I jxcore-log: 
09-29 06:32:57.893  5684  5730 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 06:32:57.893  5684  5730 I jxcore-log: 
,09-29 06:32:57.893  5684  5730 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 06:32:57.893  5684  5730 I jxcore-log: 
09-29 06:32:57.894  5684  5730 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-29 06:32:57.894  5684  5730 I jxcore-log: 
09-29 06:32:57.894  5684  5730 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 06:32:57.894  5684  5730 I jxcore-log: 
09-29 06:32:57.894  5684  5730 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 06:32:57.894  5684  5730 I jxcore-log: 
09-29 06:32:57.894  5684  5730 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 06:32:57.894  5684  5730 I jxcore-log: 
09-29 06:32:57.894  5684  5730 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 06:32:57.894  5684  5730 I jxcore-log: 
09-29 06:32:57.895  5684  5730 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 06:32:57.895  5684  5730 I jxcore-log: 
,09-29 06:32:57.895  5684  5730 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 06:32:57.895  5684  5730 I jxcore-log: 
09-29 06:32:57.895  5684  5730 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 06:32:57.895  5684  5730 I jxcore-log: 
09-29 06:32:57.895  5684  5730 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 06:32:57.895  5684  5730 I jxcore-log: 
09-29 06:32:57.895  5684  5730 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 06:32:57.895  5684  5730 I jxcore-log: 
,09-29 06:32:57.896  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 06:32:57.896  5684  5730 I jxcore-log: 
,09-29 06:32:57.897  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 06:32:57.897  5684  5730 I jxcore-log: 
,09-29 06:32:57.899  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 06:32:57.899  5684  5730 I jxcore-log: 
,09-29 06:32:57.900  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 06:32:57.900  5684  5730 I jxcore-log: 
,09-29 06:32:57.904  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 06:32:57.904  5684  5730 I jxcore-log: 
,09-29 06:32:57.906  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 06:32:57.906  5684  5730 I jxcore-log: 
,09-29 06:32:57.911  5684  5730 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-29 06:32:57.911  5684  5730 I jxcore-log: 
09-29 06:32:57.912  5684  5730 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-29 06:32:57.912  5684  5730 I jxcore-log: 
09-29 06:32:57.912  5684  5730 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-29 06:32:57.912  5684  5730 I jxcore-log: 
,09-29 06:32:57.912  5684  5730 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-29 06:32:57.912  5684  5730 I jxcore-log: 
09-29 06:32:57.913  5684  5730 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-29 06:32:57.913  5684  5730 I jxcore-log: 
09-29 06:32:57.913  5684  5730 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-29 06:32:57.913  5684  5730 I jxcore-log: 
09-29 06:32:57.913  5684  5730 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-29 06:32:57.913  5684  5730 I jxcore-log: 
09-29 06:32:57.913  5684  5730 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-29 06:32:57.913  5684  5730 I jxcore-log: 
09-29 06:32:57.913  5684  5730 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-29 06:32:57.913  5684  5730 I jxcore-log: 
09-29 06:32:57.913  5684  5730 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-29 06:32:57.913  5684  5730 I jxcore-log: 
,09-29 06:32:57.914  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 06:32:57.914  5684  5730 I jxcore-log: 
09-29 06:32:57.914  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 06:32:57.914  5684  5730 I jxcore-log: 
,09-29 06:32:57.915  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 06:32:57.915  5684  5730 I jxcore-log: 
,09-29 06:32:57.917  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start listening for advertisements'
09-29 06:32:57.917  5684  5730 I jxcore-log: 
,09-29 06:32:57.919  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start update advertising and listening'
09-29 06:32:57.919  5684  5730 I jxcore-log: 
,09-29 06:32:57.924  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliWifiInfrastructure: 'listening 47720'
09-29 06:32:57.924  5684  5730 I jxcore-log: 
,09-29 06:32:57.926  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 06:32:57.926  5684  5730 I jxcore-log: 
,09-29 06:32:57.928  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 06:32:57.928  5684  5730 I jxcore-log: 
,09-29 06:32:57.929  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 06:32:57.929  5684  5730 I jxcore-log: 
,09-29 06:32:57.931  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 06:32:57.931  5684  5730 I jxcore-log: 
,09-29 06:32:57.932  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 06:32:57.932  5684  5730 I jxcore-log: 
,09-29 06:32:57.936  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 06:32:57.936  5684  5730 I jxcore-log: 
,09-29 06:32:57.938  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 06:32:57.938  5684  5730 I jxcore-log: 
,09-29 06:32:57.941  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 06:32:57.941  5684  5730 I jxcore-log: 
,09-29 06:32:57.941  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 06:32:57.941  5684  5730 I jxcore-log: 
,09-29 06:32:57.942  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 06:32:57.942  5684  5730 I jxcore-log: 
,09-29 06:32:57.944  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start listening for advertisements'
09-29 06:32:57.944  5684  5730 I jxcore-log: 
,09-29 06:32:57.946  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start update advertising and listening'
09-29 06:32:57.946  5684  5730 I jxcore-log: 
,09-29 06:32:57.951  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliWifiInfrastructure: 'listening 44929'
09-29 06:32:57.951  5684  5730 I jxcore-log: 
,09-29 06:32:57.952  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 06:32:57.952  5684  5730 I jxcore-log: 
,09-29 06:32:57.955  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 06:32:57.955  5684  5730 I jxcore-log: 
,09-29 06:32:57.956  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 06:32:57.956  5684  5730 I jxcore-log: 
,09-29 06:32:57.958  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 06:32:57.958  5684  5730 I jxcore-log: 
,09-29 06:32:57.959  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 06:32:57.959  5684  5730 I jxcore-log: 
,09-29 06:32:57.968  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 06:32:57.968  5684  5730 I jxcore-log: 
,09-29 06:32:57.970  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 06:32:57.970  5684  5730 I jxcore-log: 
,09-29 06:32:57.973  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 06:32:57.973  5684  5730 I jxcore-log: 
,09-29 06:32:57.973  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 06:32:57.973  5684  5730 I jxcore-log: 
09-29 06:32:57.974  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 06:32:57.974  5684  5730 I jxcore-log: 
,09-29 06:32:57.976  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start listening for advertisements'
09-29 06:32:57.976  5684  5730 I jxcore-log: 
,09-29 06:32:57.977  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'start update advertising and listening'
09-29 06:32:57.977  5684  5730 I jxcore-log: 
,09-29 06:32:57.982  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliWifiInfrastructure: 'listening 48699'
09-29 06:32:57.982  5684  5730 I jxcore-log: 
,09-29 06:32:57.983  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 06:32:57.983  5684  5730 I jxcore-log: 
,09-29 06:32:57.987  5684  5730 I jxcore-log: ok 231 ThaliMobile.start was called once
09-29 06:32:57.987  5684  5730 I jxcore-log: 
,09-29 06:32:57.987  5684  5730 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-29 06:32:57.987  5684  5730 I jxcore-log: 
09-29 06:32:57.987  5684  5730 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 06:32:57.987  5684  5730 I jxcore-log: 
09-29 06:32:57.988  5684  5730 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 06:32:57.988  5684  5730 I jxcore-log: 
09-29 06:32:57.988  5684  5730 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-29 06:32:57.988  5684  5730 I jxcore-log: 
09-29 06:32:57.988  5684  5730 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 06:32:57.988  5684  5730 I jxcore-log: 
09-29 06:32:57.988  5684  5730 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 06:32:57.988  5684  5730 I jxcore-log: 
09-29 06:32:57.988  5684  5730 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 06:32:57.988  5684  5730 I jxcore-log: 
,09-29 06:32:57.989  5684  5730 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 06:32:57.989  5684  5730 I jxcore-log: 
09-29 06:32:57.989  5684  5730 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 06:32:57.989  5684  5730 I jxcore-log: 
,09-29 06:32:57.989  5684  5730 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 06:32:57.989  5684  5730 I jxcore-log: 
,09-29 06:32:57.989  5684  5730 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 06:32:57.989  5684  5730 I jxcore-log: 
09-29 06:32:57.989  5684  5730 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 06:32:57.989  5684  5730 I jxcore-log: 
,09-29 06:32:57.990  5684  5730 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 06:32:57.990  5684  5730 I jxcore-log: 
09-29 06:32:57.990  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 06:32:57.990  5684  5730 I jxcore-log: 
09-29 06:32:57.991  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 06:32:57.991  5684  5730 I jxcore-log: 
09-29 06:32:57.992  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 06:32:57.992  5684  5730 I jxcore-log: 
,09-29 06:32:57.993  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 06:32:57.993  5684  5730 I jxcore-log: 
,09-29 06:32:57.997  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 06:32:57.997  5684  5730 I jxcore-log: 
,09-29 06:32:57.999  5684  5730 I jxcore-log: 2016-09-29 10:32:57 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 06:32:57.999  5684  5730 I jxcore-log: 
,09-29 06:32:58.004  5684  5730 I jxcore-log: # teardown
09-29 06:32:58.004  5684  5730 I jxcore-log: 
,09-29 06:32:58.036  5684  5730 I jxcore-log: # setup
09-29 06:32:58.036  5684  5730 I jxcore-log: 
,09-29 06:32:58.120  5684  5730 I jxcore-log: # test write
09-29 06:32:58.120  5684  5730 I jxcore-log: 
,09-29 06:32:58.333  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 06:32:58.333  5684  5730 I jxcore-log: 
,09-29 06:32:58.336  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 06:32:58.336  5684  5730 I jxcore-log: 
,09-29 06:32:58.338  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 06:32:58.338  5684  5730 I jxcore-log: 
,09-29 06:32:58.362  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 06:32:58.362  5684  5730 I jxcore-log: 
,09-29 06:32:58.363  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 06:32:58.363  5684  5730 I jxcore-log: 
09-29 06:32:58.364  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 06:32:58.364  5684  5730 I jxcore-log: 
,09-29 06:32:58.366  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'start listening for advertisements'
09-29 06:32:58.366  5684  5730 I jxcore-log: 
,09-29 06:32:58.370  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'start update advertising and listening'
09-29 06:32:58.370  5684  5730 I jxcore-log: 
,09-29 06:32:58.374  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliWifiInfrastructure: 'listening 48189'
09-29 06:32:58.374  5684  5730 I jxcore-log: 
,09-29 06:32:58.378  5684  5730 I jxcore-log: 2016-09-29 10:32:58 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 06:32:58.378  5684  5730 I jxcore-log: 
,09-29 06:32:59.073  5684  5730 I jxcore-log: 2016-09-29 10:32:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-29 06:32:59.073  5684  5730 I jxcore-log: 
,09-29 06:32:59.283  5684  5730 I jxcore-log: 2016-09-29 10:32:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-29 06:32:59.283  5684  5730 I jxcore-log: 
,09-29 06:32:59.624  5684  5730 I jxcore-log: 2016-09-29 10:32:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-29 06:32:59.624  5684  5730 I jxcore-log: 
,09-29 06:32:59.631  5684  5730 I jxcore-log: 2016-09-29 10:32:59 - ERROR thaliSendNotificationBasedOnReplication: 'Got an error on the replication change listener - {"name":"AssertionError","actual":null,"expected":true,"operator":"==","message":"If beacons werepreviously updated then there has to be a refresh timer for them.","stack":"ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9\nPouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9"}'
09-29 06:32:59.631  5684  5730 I jxcore-log: 
,09-29 06:32:59.634  5684  5730 I jxcore-log: 2016-09-29 10:32:59 - ERROR TestsProcess: 'uncaught promise rejection, error: 'AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.', stack: 'ok@assert.js:126:1
09-29 06:32:59.634  5684  5730 I jxcore-log: ThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9
09-29 06:32:59.634  5684  5730 I jxcore-log: PouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9''
09-29 06:32:59.634  5684  5730 I jxcore-log: 
,09-29 06:32:59.634  5684  5730 I jxcore-log: 2016-09-29 10:32:59 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-29 06:32:59.634  5684  5730 I jxcore-log: 
,09-29 06:33:00.195  6063  6063 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-29 06:33:00.218  6063  6063 D AndroidRuntime: CheckJNI is OFF
,09-29 06:33:00.242  6063  6063 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-29 06:33:00.275  6063  6063 I Radio-JNI: register_android_hardware_Radio DONE
,09-29 06:33:00.291  6063  6063 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-29 06:33:00.300   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-29 06:33:00.301   928   941 I ActivityManager: Killing 5684:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-29 06:33:00.410   928   938 D GraphicsStats: Buffer count: 2
,09-29 06:33:00.410   928  3932 I WindowState: WIN DEATH: Window{72ef7b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-29 06:33:00.412   928  3028 D WifiService: Client connection lost with reason: 4
,09-29 06:33:00.450   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-29 06:33:00.450   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-29 06:33:00.451   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-29 06:33:00.451   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-29 06:33:00.451   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:00.451   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:00.451   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 06:33:00.451   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-29 06:33:00.452   928   941 I ActivityManager:   Force finishing activity ActivityRecord{976e8a4 u0 com.test.thalitest/.MainActivity t2}
,09-29 06:33:00.454   928   951 I art     : Starting a blocking GC Explicit
,09-29 06:33:00.459   928  3900 W ActivityManager: Spurious death for ProcessRecord{fb510af 0:com.test.thalitest/u0a77}, curProc for 5684: null
,09-29 06:33:00.464   928   946 W WindowManager: Attempted to add application window with unknown token Token{55b360d ActivityRecord{976e8a4 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-29 06:33:00.464   928   946 W WindowManager: Token{55b360d ActivityRecord{976e8a4 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{55b360d ActivityRecord{976e8a4 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-29 06:33:00.464   928   946 W WindowManager: view not successfully added to wm, removing view
09-29 06:33:00.465   928   946 W WindowManager: Exception when adding starting window
09-29 06:33:00.465   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{ada7366 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-29 06:33:00.465   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-29 06:33:00.465   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-29 06:33:00.465   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-29 06:33:00.465   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-29 06:33:00.465   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-29 06:33:00.465   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:00.465   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:00.465   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 06:33:00.465   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-29 06:33:00.539   928   951 I art     : Explicit concurrent mark sweep GC freed 69957(4MB) AllocSpace objects, 29(1108KB) LOS objects, 33% free, 29MB/43MB, paused 1.552ms total 85.167ms
,09-29 06:33:00.561   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-29 06:33:00.564  6063  6063 I art     : System.exit called, status: 0
,09-29 06:33:00.564  6063  6063 I AndroidRuntime: VM exiting with result code 0.
,09-29 06:33:00.579   928   951 I ActivityManager: Start proc 6073:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-29 06:33:00.579   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-29 06:33:00.584   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-29 06:33:00.590  5953  5953 D BluetoothMapAppObserver: onReceive
09-29 06:33:00.590  5953  5953 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-29 06:33:00.596  4097  4214 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-29 06:33:00.598  3708  3708 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-29 06:33:00.605   928  2991 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-29 06:33:00.628  3708  6085 I Keyboard.Facilitator.DecoderInitializer: run()
,09-29 06:33:00.643  3708  6085 I Decoder : createOrResetDecoder
09-29 06:33:00.644  3863  3863 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-29 06:33:00.662  3447  6088 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-29 06:33:00.667   391   391 W kworker/3:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 06:33:00.678  3630  3630 I ConfigService: onCreate
,09-29 06:33:00.677   391   391 W kworker/3:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 06:33:00.694   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-29 06:33:00.690   391   391 W kworker/3:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 06:33:00.700  3630  3630 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-29 06:33:00.701  3630  3630 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-29 06:33:00.702  3630  3630 E AndroidRuntime: FATAL EXCEPTION: main
09-29 06:33:00.702  3630  3630 E AndroidRuntime: Process: com.google.process.gapps, PID: 3630
09-29 06:33:00.702  3630  3630 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-29 06:33:00.702  3630  3630 E AndroidRuntime: 	... 8 more
,09-29 06:33:00.708  3901  4000 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-29 06:33:00.710   928  6093 E DropBoxManagerService: Can't write: system_app_crash
09-29 06:33:00.710   928  6093 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 06:33:00.710   928  6093 E DropBoxManagerService: 	... 5 more
,09-29 06:33:00.710  3630  3630 I Process : Sending signal. PID: 3630 SIG: 9
,09-29 06:33:00.714  3708  6085 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-29 06:33:00.721   928  3204 I ActivityManager: Start proc 6094:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-29 06:33:00.722  3901  4000 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-29 06:33:00.722  3901  4000 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3901
09-29 06:33:00.722  3901  4000 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:00.722  3901  4000 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 06:33:00.725   928  3900 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-29 06:33:00.726   928  6101 E DropBoxManagerService: Can't write: system_app_crash
09-29 06:33:00.726   928  6101 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 06:33:00.726   928  6101 E DropBoxManagerService: 	... 5 more
,09-29 06:33:00.732  3901  4000 I Process : Sending signal. PID: 3901 SIG: 9
,09-29 06:33:00.754   928  3028 D WifiService: Client connection lost with reason: 4
,09-29 06:33:00.759   928  3643 I ActivityManager: Process com.google.process.gapps (pid 3630) has died
,09-29 06:33:00.760   928  3643 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-29 06:33:00.760   928  3643 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-29 06:33:00.760   928  3643 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 21000ms
09-29 06:33:00.761   928  3643 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,09-29 06:33:00.783   928   939 I ActivityManager: Start proc 6109:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-29 06:33:00.853   928  3914 D GraphicsStats: Buffer count: 1
,09-29 06:33:00.853   928  3624 I WindowState: WIN DEATH: Window{d4f7659 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-29 06:33:00.859   928   939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3901) has died
,09-29 06:33:00.859   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-29 06:33:00.861   928   939 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-29 06:33:00.876   928   941 I ActivityManager: Start proc 6122:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-29 06:33:00.918  6122  6122 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:33:00.918  6122  6122 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-29 06:33:00.918  6122  6122 D AndroidRuntime: Shutting down VM
,09-29 06:33:00.925  6122  6122 E AndroidRuntime: FATAL EXCEPTION: main
09-29 06:33:00.925  6122  6122 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6122
09-29 06:33:00.925  6122  6122 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-29 06:33:00.925  6122  6122 E AndroidRuntime: 	... 10 more
,09-29 06:33:00.928   928  3208 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-29 06:33:00.929  6122  6122 I Process : Sending signal. PID: 6122 SIG: 9
,09-29 06:33:00.944   928  3643 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6122) has died
,09-29 06:33:00.946   928  3643 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-29 06:33:00.960   928   941 I ActivityManager: Start proc 6136:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-29 06:33:01.010  6136  6136 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:33:01.010  6136  6136 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-29 06:33:01.011  6136  6136 D AndroidRuntime: Shutting down VM
09-29 06:33:01.017  6136  6136 E AndroidRuntime: FATAL EXCEPTION: main
09-29 06:33:01.017  6136  6136 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6136
09-29 06:33:01.017  6136  6136 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-29 06:33:01.017  6136  6136 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-29 06:33:01.017  6136  6136 E AndroidRuntime: 	... 10 more
09-29 06:33:01.021   928  3204 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-29 06:33:01.022  6136  6136 I Process : Sending signal. PID: 6136 SIG: 9
,09-29 06:33:01.039   928  3624 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6136) has died
,09-29 06:33:01.040   928  3624 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-29 06:33:01.056   928   941 I ActivityManager: Start proc 6149:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-29 06:33:01.073   385   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
