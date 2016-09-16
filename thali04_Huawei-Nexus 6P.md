#### Test 85202518dd4c7ab_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-16 06:39:36.178   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-16 06:39:36.178   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:39:36.681  5347  5347 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 06:39:36.687  5347  5347 D AndroidRuntime: CheckJNI is OFF
09-16 06:39:36.711  5347  5347 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 06:39:36.742  5347  5347 I Radio-JNI: register_android_hardware_Radio DONE
09-16 06:39:36.757  5347  5347 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-16 06:39:36.761   927  3581 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 06:39:36.802   927  3581 I ActivityManager: Start proc 5356:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 06:39:36.820  5347  5347 D AndroidRuntime: Shutting down VM
,09-16 06:39:37.136   927  3438 I WindowManager: Screenshot max retries 4 of Token{5960a98 ActivityRecord{43b5c7b u0 com.test.thalitest/.MainActivity t4}} appWin=Window{982dff3 u0 Starting com.test.thalitest} drawState=2
,09-16 06:39:37.209  5356  5356 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-16 06:39:37.241  5356  5356 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-16 06:39:37.268  5356  5356 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 415-434)
09-16 06:39:37.268  5356  5356 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 06:39:37.288  5356  5356 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8d38e49}
09-16 06:39:37.289  5356  5356 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-16 06:39:37.289  5356  5356 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-16 06:39:37.294  5356  5356 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-16 06:39:37.296  5356  5356 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-16 06:39:37.322  5356  5371 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,09-16 06:39:37.331  5356  5356 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-16 06:39:37.344  5356  5356 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-16 06:39:37.344  5356  5356 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 06:39:37.344  5356  5356 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 06:39:37.344  5356  5356 I Adreno  : Build Date                       : 12/06/15
09-16 06:39:37.344  5356  5356 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 06:39:37.344  5356  5356 I Adreno  : Local Branch                     : mybranch17112971
09-16 06:39:37.344  5356  5356 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 06:39:37.344  5356  5356 I Adreno  : Remote Branch                    : NONE
09-16 06:39:37.344  5356  5356 I Adreno  : Reconstruct Branch               : NOTHING
,09-16 06:39:37.398   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a1a986:true
,09-16 06:39:37.432   734   734 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24547]" dev="sockfs" ino=24547 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 06:39:37.432   734   734 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[24547]" dev="sockfs" ino=24547 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 06:39:37.449  5356  5356 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-16 06:39:37.457  5356  5356 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-16 06:39:37.479  3496  3496 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30043]" dev="sockfs" ino=30043 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 06:39:37.479  3496  3496 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30043]" dev="sockfs" ino=30043 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 06:39:37.483  5356  5393 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-16 06:39:37.485  3605  3605 W Binder_C: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24559]" dev="sockfs" ino=24559 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 06:39:37.485  3605  3605 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24559]" dev="sockfs" ino=24559 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 06:39:37.489  5356  5380 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-16 06:39:37.519  5356  5393 I OpenGLRenderer: Initialized EGL, version 1.4
,09-16 06:39:37.597   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +459ms (total +822ms)
,09-16 06:39:37.621  5356  5356 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5356
,09-16 06:39:37.759  5356  5356 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 06:39:37.945  5356  5396 D jxcore_app_log: JniHelper::setJavaVM(0xf503c000), pthread_self() = -587986640
,09-16 06:39:37.950  5356  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 06:39:37.950  5356  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 06:39:37.950  5356  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 06:39:37.950  5356  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 06:39:37.950  5356  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-16 06:39:37.951  5356  5396 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dc70e6 added. We now have 1 listener(s)
,09-16 06:39:37.954  5356  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-16 06:39:37.954  5356  5396 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 06:39:37.955  5356  5396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:39:37.955  5356  5396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-16 06:39:37.958  5356  5396 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16e27d added. We now have 1 listener(s)
09-16 06:39:37.959  5356  5396 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:39:37.964   927  2982 D WifiService: New client listening to asynchronous messages
09-16 06:39:37.965  5356  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 06:39:37.965  5356  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 06:39:37.966  5356  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 06:39:37.966  5356  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 06:39:37.966  5356  5396 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-16 06:39:37.968  5356  5396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:39:37.968  5356  5396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-16 06:39:37.973  5356  5396 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:37.974  5356  5396 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:39:37.974  5356  5396 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 06:39:37.974  5356  5396 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:39:37.974  5356  5396 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 06:39:38.003  5356  5356 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 06:39:38.626  5356  5365 I art     : Background sticky concurrent mark sweep GC freed 76681(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.363ms total 207.371ms
,09-16 06:39:39.201  5356  5402 W jxcore-log: Initializing JXcore engine
09-16 06:39:39.201  5356  5402 W jxcore-log: JXcore engine is ready
,09-16 06:39:39.249  5402  5402 W Thread-53: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12020 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-16 06:39:39.249  5402  5402 W Thread-53: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16410]" dev="sockfs" ino=16410 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-16 06:39:39.249  5402  5402 W Thread-53: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 06:39:39.249  5402  5402 W Thread-53: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30020]" dev="sockfs" ino=30020 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 06:39:39.259  5356  5402 W jxcore-log: Starting JXcore engine
,09-16 06:39:39.314  5356  5402 W jxcore-log: Platform android
09-16 06:39:39.314  5356  5402 W jxcore-log: 
,09-16 06:39:39.314  5356  5402 W jxcore-log: Process ARCH arm
09-16 06:39:39.314  5356  5402 W jxcore-log: 
,09-16 06:39:39.411  5356  5402 I jxcore-log: JXcore Cordova bridge is ready!
09-16 06:39:39.411  5356  5402 I jxcore-log: 
,09-16 06:39:39.411  5356  5402 W jxcore-log: JXcore engine is started
,09-16 06:39:39.419  5356  5396 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 06:39:39.426  5356  5356 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 06:39:49.451  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 06:39:49.451  5356  5402 I jxcore-log: 
,09-16 06:39:49.454  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 06:39:49.454  5356  5402 I jxcore-log: 
,09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:49.457  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:39:49.458  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:39:49.460  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 06:39:49.460  5356  5402 I jxcore-log: 
,09-16 06:39:49.461  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 06:39:49.461  5356  5402 I jxcore-log: 
,09-16 06:39:49.718  5356  5402 I jxcore-log: Running unit tests
09-16 06:39:49.718  5356  5402 I jxcore-log: 
,09-16 06:39:49.718  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 06:39:49.719  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1919c1 added. We now have 2 listener(s)
,09-16 06:39:49.719  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 06:39:49.719  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:39:49.719  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:39:49.720  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:39:49.720  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cef566 added. We now have 2 listener(s)
,09-16 06:39:49.720  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:39:49.720  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 06:39:49.722  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:49.724  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:39:49.725  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:39:49.725  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 06:39:49.725  5356  5402 D executeNativeTests: Running unit tests
,09-16 06:39:49.763  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 06:39:49.763  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 added. We now have 3 listener(s)
09-16 06:39:49.763  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 06:39:49.763  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:39:49.763  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 06:39:49.764  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:39:49.764  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d added. We now have 3 listener(s)
09-16 06:39:49.764  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:39:49.764  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 06:39:49.765  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:49.771  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:39:49.777  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:39:49.777  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:39:49.779  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 06:39:49.779  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-16 06:39:49.779  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 06:39:49.779  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 06:39:49.779  5356  5402 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-16 06:39:49.780  5356  5402 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 06:39:49.780  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 06:39:49.780  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:39:49.780  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:39:49.780  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:39:49.780  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:39:49.780  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:39:49.780  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:39:49.780  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:39:49.780  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.780  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:39:49.781  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 06:39:49.781  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 removed from the list
,09-16 06:39:49.781  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:49.781  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d removed from the list
09-16 06:39:49.781  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:39:49.781  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:49.782  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.782  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:49.782  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 06:39:49.782  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:39:49.782  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:49.782  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:49.783  5356  5402 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 06:39:49.784  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:39:49.784  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:39:49.784  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:39:49.784  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:39:49.784  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.784  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:39:49.784  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:39:49.784  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:49.784  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:49.784  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 06:39:49.784  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.784  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:49.784  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.784  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:39:49.785  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:39:49.785  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:39:49.785  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:49.785  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-16 06:39:49.787  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 06:39:49.788  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:39:49.788  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:39:49.788  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:39:49.788  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:39:49.788  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.788  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:49.788  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
,09-16 06:39:49.788  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:49.788  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:49.788  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:39:49.788  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.788  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:49.788  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:49.788  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:49.789  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:39:49.789  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:39:49.789  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:49.789  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:49.789  5356  5402 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 06:39:49.790  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:49.791  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:39:49.792  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:39:49.792  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:39:49.792  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:39:49.792  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 06:39:49.793  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 06:39:49.793  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:39:49.793  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 06:39:49.794  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 06:39:49.794  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 06:39:49.797  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 06:39:49.797  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 06:39:49.798  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 06:39:49.799  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-16 06:39:49.800  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-16 06:39:49.800  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 06:39:49.800  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 06:39:49.800  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 06:39:49.801  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:39:49.803  4476  4720 D BtGatt.GattService: registerClient() - UUID=f4fcfe57-af86-407e-97e4-c5bfcc1806da
09-16 06:39:49.804  4476  4537 D BtGatt.GattService: onClientRegistered() - UUID=f4fcfe57-af86-407e-97e4-c5bfcc1806da, clientIf=5
09-16 06:39:49.805  5356  5366 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 06:39:49.807  4476  4491 D BtGatt.GattService: start scan with filters
09-16 06:39:49.812  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 06:39:49.812  4476  4542 D BtGatt.ScanManager: handling starting scan
09-16 06:39:49.812  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 06:39:49.812  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 06:39:49.812  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 06:39:49.813  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:39:49.813  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 06:39:49.814  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:39:49.814  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 06:39:49.815  4476  4542 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:39:49.816  5356  5402 I io.jxcore.node.ConnectionHelper: start: OK
09-16 06:39:49.823  4476  4537 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 06:39:49.823  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:49.824  4476  4542 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 06:39:49.831  4476  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 06:39:49.831  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:49.831  4476  4542 D BtGatt.ScanManager: Starting BLE batch scan
09-16 06:39:49.831  4476  4542 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 06:39:49.844  4476  4537 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 06:39:49.844  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:49.851  4476  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 06:39:49.851  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:39:50.316  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-16 06:39:50.316  5356  5356 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 06:39:50.317  5356  5356 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 06:39:51.179   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:39:52.180   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:39:53.181   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:39:54.182   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:39:54.820  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:39:54.820  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 06:39:54.820  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 06:39:54.821  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:54.821  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 06:39:54.821  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:39:54.821  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:39:54.821  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 06:39:54.821  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-16 06:39:54.822  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 06:39:54.822  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 06:39:54.823  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:39:54.824  4476  4720 D BtGatt.GattService: stopScan() - queue size =1
,09-16 06:39:54.825  4476  4491 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 06:39:54.825  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 06:39:54.825  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 06:39:54.825  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-16 06:39:54.826  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 06:39:54.826  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 06:39:54.827  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:39:54.827  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 06:39:54.828  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 06:39:54.828  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 06:39:54.828  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 06:39:54.835  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:39:54.835  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:54.835  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:39:54.836  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:39:54.836  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:54.836  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:54.836  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 06:39:54.836  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:39:54.836  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:39:54.836  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:54.836  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:39:54.836  4476  4476 D BtGatt.ScanManager: awakened up at time 348003
,09-16 06:39:54.844  4476  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 06:39:54.844  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:54.844  4476  4542 D BtGatt.ScanManager: stopping BLe Batch
,09-16 06:39:54.855  4476  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 06:39:54.856  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:54.856  4476  4542 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 06:39:54.877  4476  4537 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-16 06:39:54.877  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:54.878  4476  4537 D BtGatt.GattService: current time is 348044223035
09-16 06:39:54.878  4476  4537 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -77, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -87, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 06:39:54.880  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 06:39:54.882  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 06:39:54.883  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-16 06:39:54.883  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 06:39:54.883  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 06:39:55.183   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:39:55.338  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 06:39:56.184   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:39:59.839  5356  5402 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 06:39:59.844  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:59.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:39:59.856  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:39:59.856  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:39:59.856  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:39:59.857  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-16 06:39:59.857  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 06:39:59.857  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:39:59.857  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 06:39:59.863  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 06:39:59.863  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 06:39:59.869  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 06:39:59.870  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 06:39:59.871  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 06:39:59.876  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 06:39:59.877  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 06:39:59.877  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 06:39:59.878  5356  5402 D BluetoothAdapter: STATE_ON
,09-16 06:39:59.882  4476  4719 D BtGatt.GattService: registerClient() - UUID=72e0dc84-0bf5-49bc-a711-3fa0689cdc7c
,09-16 06:39:59.882  4476  4537 D BtGatt.GattService: onClientRegistered() - UUID=72e0dc84-0bf5-49bc-a711-3fa0689cdc7c, clientIf=5
09-16 06:39:59.883  5356  5367 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 06:39:59.884  4476  4490 D BtGatt.GattService: start scan with filters
,09-16 06:39:59.888  4476  4542 D BtGatt.ScanManager: handling starting scan
09-16 06:39:59.889  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 06:39:59.890  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 06:39:59.890  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 06:39:59.890  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 06:39:59.896  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 06:39:59.896  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 06:39:59.896  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:39:59.898  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 06:39:59.899  4476  4537 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 06:39:59.899  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.900  4476  4542 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 06:39:59.902  5356  5402 I io.jxcore.node.ConnectionHelper: start: OK
09-16 06:39:59.906  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:39:59.906  5356  5402 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-16 06:39:59.906  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 06:39:59.906  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 06:39:59.906  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:59.906  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 06:39:59.906  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:39:59.906  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:39:59.906  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 06:39:59.906  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 06:39:59.906  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 06:39:59.907  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 06:39:59.907  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:39:59.908  4476  4719 D BtGatt.GattService: stopScan() - queue size =1
09-16 06:39:59.908  4476  4490 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 06:39:59.909  4476  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 06:39:59.909  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 06:39:59.909  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.909  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 06:39:59.909  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 06:39:59.909  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 06:39:59.909  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 06:39:59.909  4476  4542 D BtGatt.ScanManager: Starting BLE batch scan
09-16 06:39:59.909  4476  4542 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 06:39:59.910  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:39:59.910  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 06:39:59.911  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 06:39:59.911  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 06:39:59.911  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 06:39:59.912  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:39:59.912  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 06:39:59.913  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:59.913  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:39:59.913  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:39:59.913  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:39:59.913  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:39:59.913  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:59.913  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:39:59.913  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:39:59.913  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:39:59.914  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:39:59.914  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:39:59.915  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:39:59.915  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:39:59.915  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:39:59.915  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
,09-16 06:39:59.916  5356  5402 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 06:39:59.918  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:39:59.922  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:39:59.922  4476  4537 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 06:39:59.923  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:39:59.925  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:39:59.926  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:39:59.926  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-16 06:39:59.926  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 06:39:59.926  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 06:39:59.926  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:39:59.926  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 06:39:59.929  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 06:39:59.929  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 06:39:59.929  4476  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 06:39:59.929  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:39:59.932  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 06:39:59.933  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 06:39:59.933  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 06:39:59.936  4476  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 06:39:59.936  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.936  4476  4542 D BtGatt.ScanManager: stopping BLe Batch
09-16 06:39:59.936  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 06:39:59.936  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 06:39:59.936  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 06:39:59.939  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:39:59.941  4476  4491 D BtGatt.GattService: registerClient() - UUID=2a0f5c6e-521e-403d-80ee-0f0bbb70a107
09-16 06:39:59.942  4476  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 06:39:59.942  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.942  4476  4537 D BtGatt.GattService: onClientRegistered() - UUID=2a0f5c6e-521e-403d-80ee-0f0bbb70a107, clientIf=5
09-16 06:39:59.942  4476  4542 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 06:39:59.942  5356  5366 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 06:39:59.943  4476  4719 D BtGatt.GattService: start scan with filters
,09-16 06:39:59.946  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 06:39:59.946  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 06:39:59.946  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 06:39:59.946  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 06:39:59.949  4476  4537 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 06:39:59.949  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:39:59.949  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.949  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 06:39:59.949  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:39:59.950  4476  4542 D BtGatt.ScanManager: handling starting scan
09-16 06:39:59.950  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 06:39:59.952  5356  5402 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 06:39:59.956  4476  4537 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 06:39:59.956  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.956  4476  4542 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 06:39:59.961  4476  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 06:39:59.962  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:39:59.962  4476  4542 D BtGatt.ScanManager: Starting BLE batch scan
09-16 06:39:59.962  4476  4542 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 06:39:59.972  4476  4537 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 06:39:59.972  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:39:59.977  4476  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 06:39:59.977  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:40:00.450  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 06:40:00.451  5356  5356 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:40:00.451  5356  5356 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 06:40:01.185   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:02.186   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:03.187   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:04.188   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:04.953  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:40:04.953  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:40:04.954  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 06:40:04.954  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:04.954  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-16 06:40:04.954  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:40:04.954  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:40:04.954  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 06:40:04.955  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 06:40:04.955  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 06:40:04.955  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 06:40:04.957  5356  5402 D BluetoothAdapter: STATE_ON
,09-16 06:40:04.959  4476  4719 D BtGatt.GattService: stopScan() - queue size =1
09-16 06:40:04.962  4476  4720 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 06:40:04.964  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 06:40:04.964  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 06:40:04.965  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 06:40:04.965  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 06:40:04.965  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 06:40:04.969  4476  4476 D BtGatt.ScanManager: awakened up at time 358135
09-16 06:40:04.969  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:40:04.970  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 06:40:04.970  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 06:40:04.970  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 06:40:04.972  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:40:04.974  4476  4537 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 06:40:04.974  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:40:04.974  4476  4542 D BtGatt.ScanManager: stopping BLe Batch
09-16 06:40:04.975  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:40:04.975  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 06:40:04.976  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 06:40:04.983  4476  4537 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 06:40:04.983  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:40:04.983  4476  4542 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 06:40:05.006  4476  4537 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-16 06:40:05.006  4476  4537 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:40:05.006  4476  4537 D BtGatt.GattService: current time is 358172552767
09-16 06:40:05.006  4476  4537 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 107, 58, 19, -9, 93, -60, 1, 0, -101, 87, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 37, -47, 14, -113, 116, -46, 1, -128, -81, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -92, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-16 06:40:05.007  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-16 06:40:05.007  4476  4537 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-16 06:40:05.007  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-16 06:40:05.008  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 06:40:05.008  4476  4537 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-16 06:40:05.189   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:05.477  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 06:40:05.477  5356  5356 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:05.477  5356  5356 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 06:40:06.190   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:40:09.977  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:40:09.977  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:09.977  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 06:40:09.977  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 06:40:09.978  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:09.978  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 06:40:09.978  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:09.978  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:40:09.978  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:09.978  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:09.979  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:40:09.980  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:09.980  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:09.985  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:09.986  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:40:09.986  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:09.986  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:09.989  5356  5402 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-16 06:40:09.992  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:09.992  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:40:09.992  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:09.993  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:09.993  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:09.993  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:09.994  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:09.994  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:09.995  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:09.995  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 06:40:09.995  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:09.995  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:09.995  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:09.995  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:09.996  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:09.996  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:09.997  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:09.997  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
,09-16 06:40:09.998  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 06:40:09.998  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:09.998  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:09.998  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 06:40:09.999  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:09.999  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:09.999  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:09.999  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:09.999  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:09.999  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:09.999  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:09.999  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:09.999  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:09.999  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.000  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.001  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.001  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.001  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:40:10.002  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.003  5356  5402 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 06:40:10.003  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:40:10.003  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:10.003  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 06:40:10.003  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.003  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.003  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.004  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.004  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.004  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.004  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.004  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.004  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.004  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:10.004  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.006  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.006  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.006  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.006  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.007  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 06:40:10.007  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:10.007  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:10.007  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:10.007  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 06:40:10.007  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.007  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.007  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.007  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.008  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.008  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.008  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.008  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.008  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.008  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.009  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.009  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.016  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.016  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
,09-16 06:40:10.017  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-16 06:40:10.017  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 06:40:10.017  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 06:40:10.017  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 06:40:10.018  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:40:10.018  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:40:10.018  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 06:40:10.018  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 06:40:10.018  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-16 06:40:10.018  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:10.018  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:10.018  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:10.018  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.018  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.018  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.018  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.018  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.018  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.019  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.019  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:10.019  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.019  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.019  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.021  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.021  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.021  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.021  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.022  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 06:40:10.022  5356  5402 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 06:40:10.022  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-16 06:40:10.025  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 06:40:10.025  5356  5402 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 06:40:10.025  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 06:40:10.026  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 06:40:10.027  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 06:40:10.027  5356  5402 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 06:40:10.027  5356  5402 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 06:40:10.027  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-16 06:40:10.027  5356  5402 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 06:40:10.027  5356  5402 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 06:40:10.027  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 06:40:10.027  5356  5402 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 06:40:10.027  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-16 06:40:10.031  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-16 06:40:10.032  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 06:40:10.032  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 06:40:10.032  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-16 06:40:10.033  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 06:40:10.033  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-16 06:40:10.033  5356  5402 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-16 06:40:10.033  5356  5402 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-16 06:40:10.033  5356  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 117)
09-16 06:40:10.034  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:10.034  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:10.034  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:10.034  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.034  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.034  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.034  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-16 06:40:10.035  4491  4491 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28579]" dev="sockfs" ino=28579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 06:40:10.035  4491  4491 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28579]" dev="sockfs" ino=28579 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 06:40:10.036  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
,09-16 06:40:10.036  5356  5404 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:10.036  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.036  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.036  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.036  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.036  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.036  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.036  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.036  5356  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 117
09-16 06:40:10.036  5356  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 117)
09-16 06:40:10.036  5356  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 117)
,09-16 06:40:10.037  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.037  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.037  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.037  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.038  5356  5402 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 06:40:10.038  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:10.038  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:40:10.038  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:10.038  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.038  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.038  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.039  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.039  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.039  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.039  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.039  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.039  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.039  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.039  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.039  5356  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 117)
09-16 06:40:10.041  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.041  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.041  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.041  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.042  5356  5402 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 06:40:10.042  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:10.042  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:10.042  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:10.042  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.042  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.042  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.042  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.042  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.042  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.04,3  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.043  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.043  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.043  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.043  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.044  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.044  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.044  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.044  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.045  5356  5402 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 06:40:10.046  5356  5402 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 06:40:10.046  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 06:40:10.046  5356  5402 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 06:40:10.046  5356  5402 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 06:40:10.046  5356  5402 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 06:40:10.046  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 06:40:10.046  5356  5402 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 06:40:10.046  5356  5402 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 06:40:10.046  5356  5402 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 06:40:10.046  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 06:40:10.046  5356  5402 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 06:40:10.047  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:10.047  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:10.047  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:10.047  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.047  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.047  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s,) left
09-16 06:40:10.047  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.047  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.047  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.047  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.047  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.047  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.047  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.047  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.048  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:10.048  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:10.048  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.048  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.049  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:10.049  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.049  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:10.049  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:10.049  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:10.049  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:10.049  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:10.049  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:10.049  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:40:15.050  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:40:15.050  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.051  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.051  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.051  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.051  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
,09-16 06:40:15.051  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:15.051  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:15.053  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:15.053  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.053  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.053  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.054  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
,09-16 06:40:15.054  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.054  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.054  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:15.054  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.054  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:40:15.054  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.055  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:40:15.058  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:15.058  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:15.058  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.059  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
,09-16 06:40:15.062  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 06:40:15.063  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:40:15.065  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-16 06:40:15.067  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-16 06:40:15.067  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-16 06:40:15.068  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 06:40:15.068  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:40:15.068  5356  5356 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 06:40:15.068  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.069  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 06:40:15.069  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 06:40:15.069  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 06:40:15.069  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.069  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 06:40:15.069  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
,09-16 06:40:15.069  5356  5356 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 06:40:15.069  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.070  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:40:15.070  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 06:40:15.070  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 06:40:15.070  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.070  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.071  5356  5406 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:15.072  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 06:40:15.072  4490  4490 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31020]" dev="sockfs" ino=31020 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 06:40:15.072  4490  4490 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31020]" dev="sockfs" ino=31020 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-16 06:40:15.072  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.073  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:40:15.073  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:15.073  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:15.073  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:40:15.073  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:15.073  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:40:15.073  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.073  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.073  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.073  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:15.074  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.074  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.074  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:15.074  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.074  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.074  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:15.074  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.076  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:15.076  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:15.076  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.076  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.076  5356  5406 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 06:40:15.076  5356  5406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 06:40:15.077  5356  5406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-16 06:40:15.077  5356  5356 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 06:40:15.078  5356  5402 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-16 06:40:15.079  5356  5402 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 06:40:15.079  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 06:40:15.079  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:40:15.079  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 06:40:15.079  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:15.079  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:15.079  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:15.080  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.080  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.080  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:40:15.080  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:15.080  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.080  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.080  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:15.080  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.080  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.081  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.081  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.082  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 06:40:15.082  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:40:15.083  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.083  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.090  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:15.090  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:40:15.090  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:15.090  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.090  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:15.090  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.090  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:15.091  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.091  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.091  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:15.091  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.092  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.092  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:40:15.092  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.093  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:15.093  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:15.093  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.093  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.094  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:40:15.094  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:40:15.094  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:40:15.095  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:40:15.095  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.095  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.095  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7707f84 not in the list
09-16 06:40:15.095  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.095  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
09-16 06:40:15.095  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 06:40:15.095  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.095  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.095  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:15.095  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:15.097  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:40:15.097  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:40:15.097  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:15.097  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d8b36d not in the list
,09-16 06:40:15.099  5356  5402 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 06:40:15.099  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 06:40:15.099  5356  5402 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 06:40:15.099  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 06:40:15.099  5356  5402 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 06:40:15.099  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-16 06:40:15.102  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 06:40:15.102  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-16 06:40:15.102  5356  5402 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 06:40:15.103  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 06:40:15.103  5356  5402 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 06:40:15.103  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 06:40:15.103  5356  5402 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-16 06:40:15.103  5356  5402 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 06:40:15.104  5356  5402 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-16 06:40:15.104  5356  5402 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-16 06:40:15.104  5356  5402 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 06:40:15.104  5356  5402 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-16 06:40:15.105  5356  5402 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-16 06:40:15.105  5356  5402 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-16 06:40:15.106  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:40:15.106  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e29e87 added. We now have 3 listener(s)
09-16 06:40:15.107  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:40:15.108  5356  5402 D BluetoothAdapter: enable(): BT is already enabled..!
09-16 06:40:15.109   927  3439 D WifiService: setWifiEnabled: true pid=5356, uid=10077
09-16 06:40:15.109   927  3439 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 06:40:15.115   507   922 D SoftapController: Softap fwReload - Ok
,09-16 06:40:15.118   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:15.118   507   922 D CommandListener: Trying to bring down wlan0
,09-16 06:40:15.119   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-16 06:40:15.122   927  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 06:40:15.165  4476  4703 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-16 06:40:15.166  4476  4710 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-16 06:40:15.573  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 06:40:15.817   927  2981 D wifi    : set interface wlan0 flags (UP)
09-16 06:40:15.817   927  2981 I WifiHAL : Initializing wifi
09-16 06:40:15.817   927  2981 I WifiHAL : Creating socket
,09-16 06:40:15.826   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 06:40:15.832   927  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-16 06:40:15.832   927  2981 D wifi    : Did set static halHandle = 0x7f6be18ea0
09-16 06:40:15.833   927  2981 D wifi    : halHandle = 0x7f6be18ea0, mVM = 0x7f81b4d140, mCls = 0x200f86
09-16 06:40:15.833   927  2981 D wifi    : array field set
09-16 06:40:15.833   927  2981 I WifiNative-HAL: interface[0] = wlan0
09-16 06:40:15.834   927  5409 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547270790816
09-16 06:40:15.835   927  5409 D wifi    : waitForHalEvents called, vm = 0x7f81b4d140, obj = 0x200f86, env = 0x7f663db480
,09-16 06:40:15.939   927  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 06:40:15.945  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:15.946  5410  5410 I wpa_supplicant: Successfully initialized wpa_supplicant
09-16 06:40:15.947  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:15.956   927   940 I ActivityManager: Start proc 5411:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-16 06:40:15.963  5410  5410 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 06:40:15.985  5411  5411 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-16 06:40:15.994   927  3437 I ActivityManager: Killing 5113:org.codeaurora.ims/1001 (adj 15): empty #17
,09-16 06:40:16.008  5410  5410 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 06:40:16.008  5410  5410 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 06:40:16.024   927  2981 D WifiConfigStore: Loading config and enabling all networks 
,09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:16.030  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:40:16.032  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:16.036  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:40:16.037   927  2981 D WifiConfigStore: loaded 0 passpoint configs
,09-16 06:40:16.038   927  2981 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 06:40:16.038  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:16.039   927  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 06:40:16.040   927  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-16 06:40:16.041   927  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 06:40:16.041   927  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 06:40:16.041   927  2981 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 06:40:16.042   927  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 06:40:16.046   927  2981 D WifiNative-HAL: Setting external_sim to 1
,09-16 06:40:16.046  4288  4288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 06:40:16.047   927  2981 D wifi    : setting dfs flag to true, 0x7f770484c0
09-16 06:40:16.047   927  2981 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 06:40:16.047   927  2981 D wifi    : setting scan oui 0x7f770484c0
09-16 06:40:16.048   927  2981 D WifiHAL : Sending mac address OUI
,09-16 06:40:16.059   927  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 06:40:16.059   927   927 D RttService: SCAN_AVAILABLE : 3
,09-16 06:40:16.059   927  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 06:40:16.059   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 06:40:16.060   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:16.062   927  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '30 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 30 Failed to set address (No such device)'
09-16 06:40:16.062   927  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 06:40:16.065   927  2980 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 06:40:16.066   927  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 06:40:16.085   927  2981 E native  : do suspend false
,09-16 06:40:16.092   927  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 06:40:16.190   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:17.191   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:17.821  5410  5410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:17.825  5410  5410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:17.832  5410  5410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:17.836  5410  5410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:17.925   927  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 06:40:17.927   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-16 06:40:17.928   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:40:17.940   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 06:40:17.974   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 06:40:17.976  5410  5410 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 06:40:18.192   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:18.425  5410  5410 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 06:40:18.464  5410  5410 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 06:40:18.465  5410  5410 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 06:40:18.481   927  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 06:40:18.481   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 06:40:18.481   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 06:40:18.499   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:40:18.510   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:18.518   927  2981 D WifiStateMachine: Start Dhcp Watchdog 1
,09-16 06:40:18.526   927  5431 D DhcpClient: Receive thread started
,09-16 06:40:18.529   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-16 06:40:18.530   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 06:40:18.531   927  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-16 06:40:18.610   927  2981 E native  : do suspend false
,09-16 06:40:18.623   927  5430 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 06:40:18.831   927  5431 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 168722, domain null
,09-16 06:40:18.833   927  5430 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 168722 seconds,
09-16 06:40:18.836   927  5430 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 06:40:18.852   927  5431 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 06:40:18.853   927  5430 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 06:40:18.856   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:18.861   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 06:40:18.865   927  5430 D DhcpClient: Scheduling renewal in 86399s
,09-16 06:40:18.878   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-16 06:40:18.881   927  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 06:40:18.882   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-16 06:40:18.885   927  2983 D ConnectivityService: Adding iface wlan0 to network 100
09-16 06:40:18.896   927  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 06:40:18.929   927  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-16 06:40:18.929   927  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,09-16 06:40:18.936   927  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,09-16 06:40:18.938   927  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,09-16 06:40:18.941   927  2983 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,09-16 06:40:18.949   927  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 06:40:18.954   927  2983 D ConnectivityService: scheduleUnvalidatedPrompt 100
,09-16 06:40:18.954   927  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,09-16 06:40:18.955   927  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
09-16 06:40:18.955   927  2983 D ConnectivityService:    accepting network in place of null
09-16 06:40:18.956   927  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 06:40:18.957   927  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 06:40:18.957   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 06:40:18.978   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:40:18.999   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:40:19.002   927  2983 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,09-16 06:40:19.006   927  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-16 06:40:19.007   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:40:19.007  3501  3698 W QCNEJ   : |CORE| network available: 100
,09-16 06:40:19.008   927  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
09-16 06:40:19.011  4228  4228 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@12b7fc5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-16 06:40:19.012  3501  3698 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 06:40:19.013   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 06:40:19.017  3501  3698 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-16 06:40:19.018  3501  3698 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-16 06:40:19.018   927  5429 D NetlinkSocketObserver: NeighborEvent{elapsedMs=372181, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:19.018  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:19.021  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:19.028  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:19.029  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 06:40:19.029  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 06:40:19.030  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 06:40:19.030  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:19.030  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:40:19.030  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-16 06:40:19.030  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:40:19.031  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 06:40:19.033  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:19.033  4938  4938 D QcrilMsgTunnelSocket: [1000] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 06:40:19.035  4825  4825 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-16 06:40:19.043  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000e803000000000000ffffffff]
,09-16 06:40:19.044  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:19.044  4938  4952 D QcrilMsgTunnelSocket: [1000] < OEM_HOOK_RAW [null]
09-16 06:40:19.045  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:19.045  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 06:40:19.049  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-16 06:40:19.050  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:40:19.050  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:40:19.050  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:19.051  4938  4938 D QcrilMsgTunnelSocket: [1001] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-16 06:40:19.055  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000e903000000000000ffffffff]
,09-16 06:40:19.055  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:19.055  4938  4952 D QcrilMsgTunnelSocket: [1001] < OEM_HOOK_RAW [null]
09-16 06:40:19.056  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:19.056  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 06:40:19.027  4228  4228 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-16 06:40:19.094   927  5439 D GpsLocationProvider: NTP server returned: 1474022419720 (Fri Sep 16 06:40:19 EDT 2016) reference: 372260 certainty: 20 system time offset: 626
,09-16 06:40:19.097   927  3488 D AlarmManagerService: Setting time of day to sec=1474022419
09-16 06:40:19.719   927  3488 W AlarmManagerService: Unable to set rtc to 1474022419: Invalid argument
,09-16 06:40:19.733  3889  3889 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,09-16 06:40:19.741   927  5428 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-16 06:40:19.756  3889  5455 I iu.SyncManager: SYNC; picasa accounts
,09-16 06:40:19.769  3889  3889 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-16 06:40:19.774  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 06:40:19.780  3889  5455 I iu.UploadsManager: num queued entries: 0
,09-16 06:40:19.781  3889  5455 I iu.UploadsManager: num updated entries: 0
09-16 06:40:19.782  3889  5455 I iu.SyncManager: NEXT; no task
,09-16 06:40:19.784   927  3439 I ActivityManager: Start proc 5458:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-16 06:40:19.799   927  5428 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 10:40:19 GMT], X-Android-Received-Millis=[1474022419797], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474022419772]}
,09-16 06:40:19.800   927  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 06:40:19.800   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
09-16 06:40:19.801   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-16 06:40:19.802   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 06:40:19.814   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:19.815  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 06:40:19.819  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 06:40:19.830  5458  5458 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,09-16 06:40:19.834   927  3605 I ActivityManager: Start proc 5472:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-16 06:40:19.849  3652  5484 I VacuumService: Vacuum at: now=1474022419849 tag=VacuumService
,09-16 06:40:19.881  5472  5472 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-16 06:40:19.887  5458  5485 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64,
,09-16 06:40:19.892  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:40:19.901  5472  5472 D SprintDMHelper: simOperator: 
09-16 06:40:19.901  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 06:40:19.913   927  3437 I ActivityManager: Start proc 5496:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-16 06:40:19.914   927  3437 I ActivityManager: Killing 5126:com.android.settings/1000 (adj 15): empty #17
,09-16 06:40:19.920  5458  5485 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,09-16 06:40:19.935  5458  5485 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-16 06:40:20.000  5458  5458 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-16 06:40:20.026  5512  5512 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1493551532.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1493551532.dex
,09-16 06:40:20.041  3652  5531 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-16 06:40:20.080  5512  5512 I dex2oat : dex2oat took 58.004ms (threads: 2) arena alloc=200KB java alloc=37KB native alloc=1258KB free=1045KB
,09-16 06:40:20.108  3652  5513 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-16 06:40:20.111  3652  5513 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-16 06:40:20.113  5458  5458 W InstanceID/Rpc: Found 10012
,09-16 06:40:20.138  3652  5531 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-16 06:40:20.177   927  3440 I ActivityManager: Start proc 5568:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-16 06:40:20.228  5568  5568 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-16 06:40:20.298  4288  5567 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-16 06:40:20.483  3652  5513 W Uploader:  no longer exists, so no auth token.
,09-16 06:40:20.489  3652  5543 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-16 06:40:20.566  3652  5531 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-16 06:40:20.605   927  3437 I ActivityManager: Killing 4924:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,09-16 06:40:20.630   387   387 I MSM-irqbalance: Discovered a new IRQ: 304
,09-16 06:40:20.654  3652  5543 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-16 06:40:20.677   927  3595 I ActivityManager: Start proc 5595:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,09-16 06:40:20.710  5595  5595 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,09-16 06:40:20.735  5595  5595 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-16 06:40:20.735  5595  5595 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-16 06:40:20.735  5595  5595 I GAv4    :   adb logcat -s GAv4
,09-16 06:40:20.737  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:40:20.737  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@946152 added. We now have 4 listener(s)
09-16 06:40:20.737  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 06:40:20.743  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:40:20.743  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@946152 removed from the list
09-16 06:40:20.743  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:20.743  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:20.743  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:20.743  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:40:20.744  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c409c23 added. We now have 4 listener(s)
09-16 06:40:20.744  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:40:20.745  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:20.745  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c409c23 removed from the list
09-16 06:40:20.745  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:20.745  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:20.745  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:20.746  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:40:20.746  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d275520 added. We now have 4 listener(s)
09-16 06:40:20.746  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 06:40:20.748   927  3439 D WifiService: setWifiEnabled: false pid=5356, uid=10077
,09-16 06:40:20.748   927  3439 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-16 06:40:20.750   927  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 06:40:20.750   927  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-16 06:40:20.750   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 06:40:20.750   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 06:40:20.753  4476  4533 D BluetoothAdapterState: Current state: ON, message: 23
09-16 06:40:20.753  4476  4533 D BluetoothAdapterProperties: Setting state to 13
09-16 06:40:20.753  4476  4533 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 06:40:20.754  4476  4533 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 06:40:20.754  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:40:20.754  4476  4533 I BluetoothAdapterState: Entering PendingCommandState
,09-16 06:40:20.757  4476  4537 D BluetoothAdapterProperties: Scan Mode:20
,09-16 06:40:20.758  5595  5595 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-16 06:40:20.758  4476  4533 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 06:40:20.759  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:20.759  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:40:20.759   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 06:40:20.759   927  5430 D DhcpClient: Clearing IP address
09-16 06:40:20.759  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.759  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:20.759  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:40:20.761  4476  4476 D HeadsetService: Received stop request...Stopping profile...
09-16 06:40:20.761   507   922 D CommandListener: Setting iface cfg
09-16 06:40:20.763   927  5431 D DhcpClient: Receive thread stopped
09-16 06:40:20.763  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.765  5458  5556 V NativeCrypto: Read error: ssl=0x7f77c8b680: I/O error during system call, Connection timed out
09-16 06:40:20.766  5595  5595 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-16 06:40:20.766  3135  3149 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:20.767  4476  4476 D BluetoothMapService: onReceive
09-16 06:40:20.767  4476  4476 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 06:40:20.767  4476  4476 D BluetoothMapService: STATE_TURNING_OFF
09-16 06:40:20.767  3535  3558 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:20.767  3135  3135 D HeadsetProfile: Bluetooth service disconnected
,09-16 06:40:20.767   927   927 D BluetoothHeadset: Proxy object disconnected
,09-16 06:40:20.767   927   927 D BluetoothHeadset: Proxy object disconnected
,09-16 06:40:20.767   927   927 D BluetoothHeadset: Proxy object disconnected
,09-16 06:40:20.767  4476  4476 D A2dpService: Received stop request...Stopping profile...
09-16 06:40:20.768  4476  4714 D A2dpStateMachine: Exit Disconnected: -1
09-16 06:40:20.768  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.768  5458  5556 V NativeCrypto: SSL shutdown failed: ssl=0x7f77c8b680: I/O error during system call, Broken pipe
09-16 06:40:20.769   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 06:40:20.769  3652  5495 V NativeCrypto: Read error: ssl=0x7f77c8bd80: I/O error during system call, Connection timed out
09-16 06:40:20.770  3652  5495 V NativeCrypto: SSL shutdown failed: ssl=0x7f77c8bd80: I/O error during system call, Broken pipe
09-16 06:40:20.770  3652  5531 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
09-16 06:40:20.770  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:20.770  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:20.771  4476  4476 D HidService: Received stop request...Stopping profile...
09-16 06:40:20.773  4476  4476 D HidService: Stopping Bluetooth HidService
09-16 06:40:20.771   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 06:40:20.773   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-16 06:40:20.774  4476  4476 D HealthService: Received stop request...Stopping profile...
,09-16 06:40:20.771  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.774  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:20.774   533   533 E Parcel  : Reading a NULL string not supported here.
09-16 06:40:20.776  4476  4476 D PanService: Received stop request...Stopping profile...
09-16 06:40:20.778  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.778  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:20.778  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.779  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:20.780   927   927 D RttService: SCAN_AVAILABLE : 1
09-16 06:40:20.781  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.781  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.781  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.781  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.781  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.781  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:20.781   927  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-16 06:40:20.781  4476  4476 D BluetoothMapService: Received stop request...Stopping profile...
09-16 06:40:20.782  4476  4476 D BluetoothMapService: stop()
09-16 06:40:20.782   927  3088 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 06:40:20.782  4476  4476 D BluetoothMapAppObserver: deinitObservers()
09-16 06:40:20.78,2  4476  4476 D BluetoothMapAppObserver: removeReceiver()
09-16 06:40:20.783  3501  3698 W QCNEJ   : |CORE| network lost: 100
09-16 06:40:20.783  3652  5513 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.20.234 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
09-16 06:40:20.783  3501  3698 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 06:40:20.783  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.784  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:20.784   927  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 06:40:20.785  4476  4476 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 06:40:20.786  4476  4476 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 06:40:20.786  4476  4703 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:20.786  4476  4703 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:20.786  4476  4703 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:20.786  4476  4537 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 06:40:20.786  4476  4476 I BtOppRfcommListener: stopping Accept Thread
09-16 06:40:20.786  4476  4537 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 06:40:20.786  4476  5160 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 06:40:20.786  4476  5160 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 06:40:20.789  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.789  5595  5612 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.789  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:20.789  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.789  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.789  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.789  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.790  4476  4476 D SapService: Received stop request...Stopping profile...
09-16 06:40:20.790  4476  4476 V SapService: stop()
09-16 06:40:20.790  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.790  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:20.791   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 06:40:20.791  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.791  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:20.793  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.793  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:20.793  4476  4537 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 06:40:20.793  4476  4703 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:20.794  4476  4703 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:20.794  4476  4703 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 06:40:20.794  4476  4703 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 06:40:20.794  4476  4703 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 06:40:20.794  4476  4703 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 06:40:20.794  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.794  5458  5545 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
09-16 06:40:20.794  3135  3135 D BluetoothA2dp: Proxy object disconnected
09-16 06:40:20.794  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.794  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.795  3135  3135 D BluetoothInputDevice: Proxy object disconnected
09-16 06:40:20.795  3135  3135 D HidProfile: Bluetooth service disconnected
09-16 06:40:20.794  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.795  3135  3135 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 06:40:20.795  3135  3135 D PanProfile: Bluetooth service disconnected
09-16 06:40:20.795  3135  3135 D BluetoothMap: Proxy object disconnected
09-16 06:40:20.795  4476  4476 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 06:40:20.795  3135  3135 D MapProfile: Bluetooth service disconnected
09-16 06:40:20.795  4476  4476 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 06:40:20.795  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.795  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.795  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.795  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.795  4476  4537 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 06:40:20.796  4476  4476 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 06:40:20.796  4476  4537 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 06:40:20.796  4476  4476 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 06:40:20.796  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.796  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.796  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.796  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.796  4476  4476 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 06:40:20.796  4476  4476 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 06:40:20.797  4476  4476 D BluetoothMapService: MAP Service closeService in
09-16 06:40:20.797  4476  4476 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 06:40:20.797  4476  4476 D ObexServerSockets0: shutdown(block = true)
09-16 06:40:20.798  4476  4476 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 06:40:20.798  4476  4723 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-16 06:40:20.798  4476  4476 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 06:40:20.798  4476  4724 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 06:40:20.798  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.798  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.798  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.798  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.798  4476  4710 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 06:40:20.798  4476  4476 D BluetoothMapService: cleanup()
09-16 06:40:20.798  4476  4476 D BluetoothMapService: MAP Service closeService in
09-16 06:40:20.800  4476  4476 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:20.800  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:20.800  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:20.800  4476  4476 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:20.800  4476  4533 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 06:40:20.800  4476  4533 D BluetoothAdapterProperties: Setting state to 15
09-16 06:40:20.800  4476  4533 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 06:40:20.800  4476  4533 I BluetoothAdapterState: Entering BleOnState
09-16 06:40:20.801  3135  3149 D BluetoothPan: onBluetoothStateChange on: false
09-16 06:40:20.801   927  3440 I ActivityManager: Killing 4547:com.android.providers.calendar/u0a1 (adj 15): empty #17
09-16 06:40:20.810   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 06:40:20.815   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:20.833   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 06:40:20.833   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 06:40:20.834   927  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-16 06:40:20.834   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 06:40:20.838   927  3440 I ActivityManager: Killing 4228:com.google.android.music:main/u0a59 (adj 15): empty #18
09-16 06:40:20.864   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:20.865   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-16 06:40:20.867   927   940 W BroadcastQueue: Failure sending broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-16 06:40:20.867   927   940 W BroadcastQueue: android.os.DeadObjectException
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1128)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:453)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:594)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:667)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 06:40:20.867   927   940 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-16 06:40:20.869  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.870  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.870   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 06:40:20.870  3535  3844 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 06:40:20.870   927  2981 D DhcpClient: doQuit
09-16 06:40:20.870   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 06:40:20.871   927  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 06:40:20.871  3135  3759 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 06:40:20.871  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.872  5410  5410 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-16 06:40:20.872   927  5430 D DhcpClient: onQuitting
09-16 06:40:20.873  3135  3147 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 06:40:20.873  4825  4825 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-16 06:40:20.873  3135  3759 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:20.874  3135  3149 D BluetoothMap: onBluetoothStateChange: up=false
09-16 06:40:20.875  3135  3149 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 06:40:20.875  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid,
09-16 06:40:20.876  4476  4533 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-16 06:40:20.876  4476  4533 D BluetoothAdapterProperties: Setting state to 16
,09-16 06:40:20.876  4476  4533 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-16 06:40:20.876   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 06:40:20.875  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-16 06:40:20.877  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 06:40:20.877  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:40:20.877  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 06:40:20.877  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:40:20.877  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.877  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.877  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:20.878  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:20.878  4938  4938 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 06:40:20.878  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 06:40:20.879  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:40:20.879  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:40:20.879  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.879  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:20.880  4476  4533 D BluetoothAdapterProperties: onBleDisable
,09-16 06:40:20.880  4476  4533 I BluetoothAdapterState: Entering PendingCommandState
09-16 06:40:20.880  4476  4534 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 06:40:20.881  4476  4537 D BluetoothAdapterProperties: Scan Mode:20
09-16 06:40:20.882  4476  4703 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 06:40:20.882  4476  4703 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:20.882  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.882  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:40:20.882  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.882  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:20.884  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:20.884  4938  4938 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 06:40:20.885  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:20.886  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:20.886  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:20.886  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:20.888  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.889  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.890  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.892  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.894  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.896  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:20.896  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000ea03000000000000ffffffff]
,09-16 06:40:20.896  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:20.896  4938  4952 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-16 06:40:20.897  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:20.897  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 06:40:20.899   927   938 I ActivityManager: Start proc 5622:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
09-16 06:40:20.899   927   938 I ActivityManager: Killing 5236:com.android.defcontainer/u0a7 (adj 15): empty #17
09-16 06:40:20.901  5410  5410 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-16 06:40:20.905  5410  5410 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-16 06:40:20.907  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000eb03000000000000ffffffff]
09-16 06:40:20.907  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:20.907  4938  4952 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-16 06:40:20.908  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:20.908  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 06:40:20.918   507   922 E Netd    : netlink response contains error (No such file or directory)
09-16 06:40:20.920   927  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-16 06:40:20.943  5622  5622 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm64
,09-16 06:40:20.947  5410  5410 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 06:40:20.952  5410  5410 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 06:40:20.966  5622  5622 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1474022420966
,09-16 06:40:20.966  5622  5622 D         : TimeServiceNative: User Time to be set is 1474022420966
09-16 06:40:20.966  5622  5622 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-16 06:40:20.966  5622  5622 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-16 06:40:20.966  5622  5622 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1474022420966
09-16 06:40:20.967   529   549 D QC-time-services: Daemon: Connection accepted:time_genoff
09-16 06:40:20.967  5622  5622 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1474022420966
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1474022420966, operation = 0
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/25/70 17:6:35
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:Value read from RTC seconds = 9911195000
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:new time 1474022420966 
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon: delta 1464111225966 genoff 1464111225966 
,09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1464111225966 to memory
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-16 06:40:20.967   529  5635 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-16 06:40:20.972   529  5635 D QC-time-services: Updating the TOD offset
,09-16 06:40:20.972   529  5635 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1464111225966 to memory
09-16 06:40:20.972   529  5635 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-16 06:40:20.972   529  5635 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-16 06:40:20.974   529  5635 E QC-time-services: Daemon:Update to modem bit set
,09-16 06:40:20.974   529  5635 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-16 06:40:20.974   529  5635 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1148146425966
09-16 06:40:20.975  5622  5622 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
09-16 06:40:20.977   927  3195 I ActivityManager: Killing 3422:android.process.acore/u0a2 (adj 15): empty #17
,09-16 06:40:20.979   529   570 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,09-16 06:40:20.979   529   549 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-16 06:40:21.018   927  3195 I ActivityManager: Start proc 5638:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-16 06:40:21.054  4288  4288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 06:40:21.054   927  2981 D wifi    : In wifi stop Hal
09-16 06:40:21.054   927  2981 D wifi    : halHandle = 0x7f6be18ea0, mVM = 0x7f81b4d140, mCls = 0x200f86
09-16 06:40:21.054   927  5409 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 06:40:21.054   927  5409 D WifiHAL : Got a signal to exit!!!
09-16 06:40:21.054   927  5409 I WifiHAL : Exit wifi_event_loop
09-16 06:40:21.055   927  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 06:40:21.055   927  2981 E WifiHAL : Event processing terminated
,09-16 06:40:21.055   927  2981 D wifi    : In wifi cleaned up handler
09-16 06:40:21.055   927  2981 I WifiHAL : Internal cleanup completed
09-16 06:40:21.056  3476  4044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 06:40:21.057  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:21.058  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:21.058  5638  5638 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-16 06:40:21.059  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:21.071  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 06:40:21.076   927  5409 D wifi    : set interface wlan0 flags (DOWN)
09-16 06:40:21.076   927  2981 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 06:40:21.078   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@793e743:true
,09-16 06:40:21.078  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:21.091   927  3195 I ActivityManager: Start proc 5652:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 06:40:21.104  5638  5638 D LocalBluetoothProfileManager: Adding local MAP profile
,09-16 06:40:21.107  5638  5638 D BluetoothMap: Create BluetoothMap proxy object
,09-16 06:40:21.116  5638  5638 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 06:40:21.129  5652  5652 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 06:40:21.133  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-16 06:40:21.133  4476  4537 I bt_hci  : shut_down
,09-16 06:40:21.138  4476  4543 D bt_hwcfg: hw_epilog_process
,09-16 06:40:21.138  4476  4543 I bt_vendor: low_power_mode_cb
,09-16 06:40:21.140  4476  4543 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-16 06:40:21.140  4476  4543 I bt_vendor: epilog_cb
09-16 06:40:21.140  4476  4543 I bt_hci  : epilog_finished_callback
09-16 06:40:21.142  4476  4537 I bt_hci_h4: hal_close
09-16 06:40:21.143  4476  4537 I bt_userial_vendor: device fd = 54 close
,09-16 06:40:21.143   927  3438 I ActivityManager: Killing 5253:com.google.android.partnersetup/u0a18 (adj 15): empty #17
,09-16 06:40:21.251  4476  4534 D bt_stack_manager: event_shut_down_stack finished.
,09-16 06:40:21.251  4476  4533 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 06:40:21.252  4476  4533 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-16 06:40:21.252  4476  4476 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 06:40:21.253  4476  4476 D BtGatt.GattService: Received stop request...Stopping profile...
,09-16 06:40:21.253  4476  4476 D BtGatt.GattService: stop()
09-16 06:40:21.253  4476  4476 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 06:40:21.254  4476  4476 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:21.254  4476  4476 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:21.254  4476  4476 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:21.254  4476  4476 V BluetoothAdapterState: isBleTurningOff()=true
,09-16 06:40:21.255  4476  4533 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 06:40:21.255  4476  4533 D BluetoothAdapterProperties: Setting state to 10
09-16 06:40:21.255  4476  4533 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 06:40:21.255  4476  4533 I BluetoothAdapterState: Entering OffState
,09-16 06:40:21.256   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-16 06:40:21.263  4476  4476 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 06:40:21.263  4476  4476 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-16 06:40:21.263  4476  4534 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-16 06:40:21.263  4476  4476 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-16 06:40:21.273  4476  4534 D bt_stack_manager: event_clean_up_stack finished.
,09-16 06:40:21.276  4476  4476 I art     : System.exit called, status: 0
09-16 06:40:21.276  4476  4476 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 06:40:21.278   927   944 D Tethering: InitialState.processMessage what=4
,09-16 06:40:21.280   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 06:40:21.341   927  3572 I ActivityManager: Process com.android.bluetooth (pid 4476) has died
,09-16 06:40:21.354  5652  5652 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.354  5652  5652 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.354  5652  5652 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.354  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.355  5652  5652 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.355  5652  5652 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.k.d(PG:583)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.355  5652  5652 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.355  5652  5652 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.355  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.366  5652  5652 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 06:40:21.366  5652  5652 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 06:40:21.372   927  3195 I ActivityManager: Killing 5270:com.android.musicfx/u0a21 (adj 15): empty #17
,09-16 06:40:21.414  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-16 06:40:21.419  3889  5455 I iu.UploadsManager: num queued entries: 0
09-16 06:40:21.419  3889  5455 I iu.UploadsManager: num updated entries: 0
09-16 06:40:21.420  3889  5455 I iu.SyncManager: NEXT; no task
09-16 06:40:21.422  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 06:40:21.424  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-16 06:40:21.426  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 06:40:21.429  5472  5472 D SprintDMHelper: simOperator: 
09-16 06:40:21.429  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 06:40:21.441  4288  5684 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 06:40:21.449  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 06:40:21.462   927  3572 I ActivityManager: Start proc 5686:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-16 06:40:21.465  5638  5638 D DockEventReceiver: finishStartingService: stopping service
,09-16 06:40:21.532  5686  5686 D AdapterServiceConfig: Adding HeadsetService
,09-16 06:40:21.532  5686  5686 D AdapterServiceConfig: Adding A2dpService
09-16 06:40:21.532  5686  5686 D AdapterServiceConfig: Adding HidService
09-16 06:40:21.532  5686  5686 D AdapterServiceConfig: Adding HealthService
09-16 06:40:21.532  5686  5686 D AdapterServiceConfig: Adding PanService
09-16 06:40:21.533  5686  5686 D AdapterServiceConfig: Adding GattService
09-16 06:40:21.533  5686  5686 D AdapterServiceConfig: Adding BluetoothMapService
,09-16 06:40:21.533  5686  5686 D AdapterServiceConfig: Adding SapService
09-16 06:40:21.535   927  5508 I ActivityManager: Killing 5174:com.google.android.gms.wearable/u0a12 (adj 15): empty #17
,09-16 06:40:21.568  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:21.706  5652  5676 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 06:40:21.715   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ffa808:true
,09-16 06:40:21.815   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:40:24.760   927   940 I ActivityManager: Start proc 5701:com.android.providers.calendar/u0a1 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,09-16 06:40:24.808  5701  5701 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm64
,09-16 06:40:24.857  5701  5701 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@ce4034e(com.android.providers.calendar.CalendarProvider2@26b5c6f)
,09-16 06:40:24.930   927  3438 I ActivityManager: Killing 4825:com.google.android.googlequicksearchbox:search/u0a29 (adj 15): empty #17
,09-16 06:40:24.993   927  2982 D WifiService: Client connection lost with reason: 4
,09-16 06:40:25.761   927  3581 D WifiService: setWifiEnabled: true pid=5356, uid=10077
,09-16 06:40:25.761   927  3581 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 06:40:25.764   507   922 D SoftapController: Softap fwReload - Ok
,09-16 06:40:25.768   507   922 D CommandListener: Setting iface cfg
09-16 06:40:25.768   507   922 D CommandListener: Trying to bring down wlan0
,09-16 06:40:25.769   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 06:40:25.771   927  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 06:40:26.008  5701  5701 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,09-16 06:40:26.009  5701  5701 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,09-16 06:40:26.314   927  2981 D wifi    : set interface wlan0 flags (UP)
,09-16 06:40:26.314   927  2981 I WifiHAL : Initializing wifi
09-16 06:40:26.314   927  2981 I WifiHAL : Creating socket
09-16 06:40:26.317   927  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 06:40:26.317   927  2981 D wifi    : Did set static halHandle = 0x7f6be18ea0
09-16 06:40:26.317   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-16 06:40:26.317   927  2981 D wifi    : halHandle = 0x7f6be18ea0, mVM = 0x7f81b4d140, mCls = 0x16ee
09-16 06:40:26.317   927  2981 D wifi    : array field set
09-16 06:40:26.317   927  2981 I WifiNative-HAL: interface[0] = wlan0
09-16 06:40:26.319   927  5718 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547270790816
09-16 06:40:26.319   927  5718 D wifi    : waitForHalEvents called, vm = 0x7f81b4d140, obj = 0x16ee, env = 0x7f663dc740
,09-16 06:40:26.327   927  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 06:40:26.330  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:26.331  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:26.332  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:26.373  5719  5719 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 06:40:26.392  5719  5719 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 06:40:26.401  5719  5719 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 06:40:26.401  5719  5719 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 06:40:26.416   927  2981 D WifiConfigStore: Loading config and enabling all networks 
,09-16 06:40:26.416  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:26.416  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:26.416  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 06:40:26.416  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:26.419  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:26.419  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:26.419  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:26.419  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:26.420  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:26.420  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:26.421  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:26.421  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:26.428   927  2981 D WifiConfigStore: loaded 0 passpoint configs
,09-16 06:40:26.428   927  2981 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 06:40:26.429   927  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 06:40:26.430   927  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 06:40:26.431   927  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 06:40:26.431   927  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 06:40:26.431   927  2981 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 06:40:26.432   927  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 06:40:26.435   927  2981 D WifiNative-HAL: Setting external_sim to 1
09-16 06:40:26.435  4288  4288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 06:40:26.436   927  2981 D wifi    : setting dfs flag to true, 0x7f6c6236a0
09-16 06:40:26.436   927  2981 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 06:40:26.437   927  2981 D wifi    : setting scan oui 0x7f6c6236a0
09-16 06:40:26.437   927  2981 D WifiHAL : Sending mac address OUI
,09-16 06:40:26.441   927  2981 E native  : do suspend false
,09-16 06:40:26.447   927  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 06:40:26.447   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 06:40:26.448   927  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 06:40:26.448   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-16 06:40:26.449   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:26.452   927  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-16 06:40:26.452   927  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 06:40:26.461   927  2980 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 06:40:26.461   927  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 06:40:26.466   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=379010 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-16 06:40:27.583   927  2983 D ConnectivityService: handlePromptUnvalidated 100
,09-16 06:40:29.630  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:29.635  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:29.640  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:29.644  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:40:29.722   927  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 06:40:29.723   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-16 06:40:29.723   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:40:29.736   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 06:40:29.770   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 06:40:29.772  5719  5719 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 06:40:29.822   927  2955 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-16 06:40:29.826   927   940 I ActivityManager: Start proc 5721:com.google.android.googlequicksearchbox:search/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,09-16 06:40:29.866  3476  3476 V GmsNetworkLocationProvi: DISABLE
,09-16 06:40:29.872  3476  3476 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-16 06:40:30.060   927  3438 I ActivityManager: Start proc 5740:com.google.android.partnersetup/u0a18 for content provider com.google.android.partnersetup/.RlzAppProvider
,09-16 06:40:30.096   927  3572 I ActivityManager: Start proc 5754:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-16 06:40:30.102  5740  5740 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,09-16 06:40:30.156  5754  5754 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,09-16 06:40:30.195  5754  5754 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,09-16 06:40:30.200  5719  5719 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 06:40:30.217  3889  5774 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-16 06:40:30.230   927  3438 I ActivityManager: Start proc 5775:com.google.android.gms.wearable/u0a12 for service com.google.android.gms/.wearable.service.WearableControlService
,09-16 06:40:30.230  3889  5774 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-16 06:40:30.238  5719  5719 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 06:40:30.238  5719  5719 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 06:40:30.243  5721  5781 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-16 06:40:30.244  3889  4816 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-16 06:40:30.245   927  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 06:40:30.247   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 06:40:30.247   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 06:40:30.260   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:40:30.269   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:30.273   927  2981 D WifiStateMachine: Start Dhcp Watchdog 2
,09-16 06:40:30.280   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 06:40:30.280   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-16 06:40:30.281   927  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-16 06:40:30.287  5775  5775 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,09-16 06:40:30.296   927  5791 D DhcpClient: Receive thread started
,09-16 06:40:30.304  5775  5775 I MultiDex: VM with version 2.1.0 has multidex support
,09-16 06:40:30.304  5775  5775 I MultiDex: install
09-16 06:40:30.304  5775  5775 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-16 06:40:30.357  5754  5772 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-16 06:40:30.364  5775  5775 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,09-16 06:40:30.370  5721  5781 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
,09-16 06:40:30.377   927  2981 E native  : do suspend false
,09-16 06:40:30.385   927  5790 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 06:40:30.389  5775  5775 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-16 06:40:30.394  3652  5795 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-16 06:40:30.397  3652  3652 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-16 06:40:30.401   927  5791 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172789, domain null
,09-16 06:40:30.401   927  5790 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172789 seconds
09-16 06:40:30.402   927  5790 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 06:40:30.407  3652  3652 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-16 06:40:30.409  3652  3652 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-16 06:40:30.411  3889  3889 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-16 06:40:30.412   927   938 I ActivityManager: Killing 5292:com.google.android.apps.docs/u0a43 (adj 15): empty #17
,09-16 06:40:30.439   927  5791 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 06:40:30.439   927  5790 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 06:40:30.440   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:30.442   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 06:40:30.444   927  5790 D DhcpClient: Scheduling renewal in 86399s
,09-16 06:40:30.449  5775  5796 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,09-16 06:40:30.452   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-16 06:40:30.452   927  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 06:40:30.452   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-16 06:40:30.453   927  2983 D ConnectivityService: Adding iface wlan0 to network 101
,09-16 06:40:30.457   927  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 06:40:30.459  5775  5775 D WearableService: callingUid 10012, callindPid: 5775
,09-16 06:40:30.475  3889  5802 D LocationInitializer: Restart initialization of location
,09-16 06:40:30.492   927  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-16 06:40:30.492   927  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-16 06:40:30.495  3476  5800 E MDM     : [90] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-16 06:40:30.496   927  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-16 06:40:30.496  3476  3898 W GCoreFlp: No location to return for getLastLocation()
,09-16 06:40:30.497  3652  5804 W FusedLocationProvider: location=null
09-16 06:40:30.498   927  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-16 06:40:30.500   927  2983 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-16 06:40:30.504   927  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 06:40:30.508   927  2983 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-16 06:40:30.508   927  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-16 06:40:30.508   927  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-16 06:40:30.508   927  2983 D ConnectivityService:    accepting network in place of null
09-16 06:40:30.508   927  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 06:40:30.509   927  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 06:40:30.509   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 06:40:30.529   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:40:30.542   927  5789 D NetlinkSocketObserver: NeighborEvent{elapsedMs=383087, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:40:30.548   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:40:30.551   927  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-16 06:40:30.551  3501  3698 W QCNEJ   : |CORE| network available: 101
09-16 06:40:30.551   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 06:40:30.552   927  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-16 06:40:30.553  3501  3698 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 06:40:30.554  3501  3698 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-16 06:40:30.554  3501  3698 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-16 06:40:30.554   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 06:40:30.556  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:30.556  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:30.556  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.556  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:30.559  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:30.559  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:30.559  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.559  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetwork,Changed: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:40:30.561  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:40:30.561  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:40:30.561  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.561  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:40:30.567  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-16 06:40:30.567  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 06:40:30.567  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 06:40:30.567  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:40:30.567  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 06:40:30.567  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:40:30.567  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 06:40:30.568  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:30.568  4938  4938 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 06:40:30.569  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 06:40:30.569  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:40:30.569  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:40:30.570  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:30.570  4938  4938 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-16 06:40:30.577  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000ec03000000000000ffffffff]
,09-16 06:40:30.577  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:30.577  4938  4952 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-16 06:40:30.577  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:30.577  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 06:40:30.578  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000ed03000000000000ffffffff]
09-16 06:40:30.578  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:30.578  4938  4952 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-16 06:40:30.579  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:30.579  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 06:40:30.579  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-16 06:40:30.580  3889  5455 I iu.UploadsManager: num queued entries: 0
09-16 06:40:30.581  3889  5455 I iu.UploadsManager: num updated entries: 0
09-16 06:40:30.581  3889  5455 I iu.SyncManager: NEXT; no task
09-16 06:40:30.585  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 06:40:30.586  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 06:40:30.588  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:40:30.593  5472  5472 D SprintDMHelper: simOperator: 
,09-16 06:40:30.593  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 06:40:30.623   927  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-16 06:40:30.643  5754  5772 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,09-16 06:40:30.643  5754  5772 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-16 06:40:30.657   927  3595 I ActivityManager: Start proc 5818:com.google.android.gm.exchange/u0a67 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-16 06:40:30.680   927  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 10:40:30 GMT], X-Android-Received-Millis=[1474022430680], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474022430646]}
,09-16 06:40:30.681   927  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-16 06:40:30.681   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-16 06:40:30.681   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-16 06:40:30.682   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 06:40:30.688  5818  5818 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm64
,09-16 06:40:30.693  4288  5814 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 06:40:30.729   927  5508 I ActivityManager: Start proc 5833:com.google.android.gm/u0a68 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-16 06:40:30.753   927  3437 I ActivityManager: Start proc 5845:com.google.process.gapps/u0a46 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-16 06:40:30.756   927   937 I ActivityManager: Killing 5458:com.google.android.youtube/u0a75 (adj 15): empty #17
,09-16 06:40:30.764   927  3121 D WifiService: setWifiEnabled: false pid=5356, uid=10077
,09-16 06:40:30.765   927  3121 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 06:40:30.767   927  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-16 06:40:30.767   927  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 06:40:30.767   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 06:40:30.767   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:40:30.776   927  5790 D DhcpClient: Clearing IP address
,09-16 06:40:30.776   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 06:40:30.778   507   922 D CommandListener: Setting iface cfg
,09-16 06:40:30.784  3652  5832 V NativeCrypto: Read error: ssl=0x7f66a39000: I/O error during system call, Connection timed out
,09-16 06:40:30.784  3652  5832 V NativeCrypto: SSL shutdown failed: ssl=0x7f66a39000: I/O error during system call, Broken pipe
,09-16 06:40:30.789   927  5791 D DhcpClient: Receive thread stopped
,09-16 06:40:30.806   927  3439 I ActivityManager: Killing 5595:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-16 06:40:30.826  5833  5833 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm64
,09-16 06:40:30.835   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-16 06:40:30.835   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-16 06:40:30.840   927   927 D RttService: SCAN_AVAILABLE : 1
,09-16 06:40:30.840   927  3088 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 06:40:30.841   927  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-16 06:40:30.841   533   533 E Parcel  : Reading a NULL string not supported here.
09-16 06:40:30.844  3501  3698 W QCNEJ   : |CORE| network lost: 101
09-16 06:40:30.844   927  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 06:40:30.844  3501  3698 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-16 06:40:30.847   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 06:40:30.855  5845  5845 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm64
,09-16 06:40:30.866   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:40:30.884   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:40:30.884   927  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-16 06:40:30.884   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 06:40:30.885   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:40:30.886   927  2981 D DhcpClient: doQuit
,09-16 06:40:30.886   927  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 06:40:30.886   927  5790 D DhcpClient: onQuitting
,09-16 06:40:30.887  5719  5719 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 06:40:30.887   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 06:40:30.889  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:30.889  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:30.890  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.890  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:30.890  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:30.891  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:30.891  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.891  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:30.892  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:30.892  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:30.892  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:30.892  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:30.893  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:30.894  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:30.896  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 06:40:30.896  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-16 06:40:30.896  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-16 06:40:30.896  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:40:30.896  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 06:40:30.896  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:30.896  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:40:30.897  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 06:40:30.897  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:30.897  4938  4938 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-16 06:40:30.899  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 06:40:30.899  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:40:30.899  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:40:30.899  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:40:30.900  4938  4938 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 06:40:30.901  5845  5845 I GoogleHttpClient: GMS http client unavailable, use old client
09-16 06:40:30.902  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-16 06:40:30.903  3889  5455 I iu.UploadsManager: num queued entries: 0
09-16 06:40:30.903  3889  5455 I iu.UploadsManager: num updated entries: 0
09-16 06:40:30.904  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000ee03000000000000ffffffff]
09-16 06:40:30.904  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:30.904  4938  4952 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-16 06:40:30.904  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:30.904  3889  5455 I iu.SyncManager: NEXT; no task
09-16 06:40:30.905  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 06:40:30.907  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000ef03000000000000ffffffff]
09-16 06:40:30.907  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:40:30.907  4938  4952 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-16 06:40:30.907  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 06:40:30.908  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:40:30.908  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 06:40:30.909  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-16 06:40:30.910  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 06:40:30.910  5719  5719 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-16 06:40:30.913  5719  5719 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 06:40:30.915  5472  5472 D SprintDMHelper: simOperator: 
09-16 06:40:30.915  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 06:40:30.935   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-16 06:40:30.941  4288  5869 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 06:40:30.946  5754  5772 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-16 06:40:30.947  5719  5719 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 06:40:30.966  5719  5719 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 06:40:30.983  5833  5876 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-16 06:40:30.985  5754  5772 I ContactDirectoryManager: Discovered 0 contact directories in 495ms
,09-16 06:40:31.055  5833  5833 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-16 06:40:31.068   927  2981 D wifi    : In wifi stop Hal
,09-16 06:40:31.068  4288  4288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 06:40:31.068   927  2981 D wifi    : halHandle = 0x7f6be18ea0, mVM = 0x7f81b4d140, mCls = 0x16ee
09-16 06:40:31.068   927  5718 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 06:40:31.068   927  5718 D WifiHAL : Got a signal to exit!!!
09-16 06:40:31.068   927  5718 I WifiHAL : Exit wifi_event_loop
09-16 06:40:31.068   927  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 06:40:31.068   927  2981 E WifiHAL : Event processing terminated
09-16 06:40:31.069  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:31.069   927  2981 D wifi    : In wifi cleaned up handler
,09-16 06:40:31.069   927  2981 I WifiHAL : Internal cleanup completed
09-16 06:40:31.070  3476  4044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 06:40:31.070  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:31.071  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:31.085  5833  5875 I Gmail   : getAccountsCursor
,09-16 06:40:31.090   927  5718 D wifi    : set interface wlan0 flags (DOWN)
,09-16 06:40:31.090   927  2981 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 06:40:31.105  5833  5885 E Gmail   : Error finding the version of the Email provider.....
09-16 06:40:31.105  5833  5885 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-16 06:40:31.105  5833  5885 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-16 06:40:31.105  5833  5885 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-16 06:40:31.105  5833  5885 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-16 06:40:31.105  5833  5885 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-16 06:40:31.105  5833  5885 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 06:40:31.105  5833  5885 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-16 06:40:31.105  5833  5885 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-16 06:40:31.105  5833  5885 W EmailMigration: We do not support migrating this version of the Email provider.
,09-16 06:40:31.152  3652  3652 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-16 06:40:31.197  3652  3652 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-16 06:40:31.215   927   937 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-16 06:40:31.245  5818  5818 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-16 06:40:31.262  5818  5818 I Exchange: EasService.onCreate
,09-16 06:40:31.264  5833  5892 I Gmail   : Observing account changes for notifications
,09-16 06:40:31.273  5818  5895 I Exchange: RestartPingTask
,09-16 06:40:31.286  5818  5818 I Exchange: RestartPingsTask did not start any pings.
,09-16 06:40:31.286  5818  5818 I Exchange: PSS stopIfIdle
09-16 06:40:31.286  5818  5818 I Exchange: PSS has no active accounts; stopping service.
,09-16 06:40:31.289  5818  5818 I Exchange: onDestroy
,09-16 06:40:31.292   927   944 D Tethering: InitialState.processMessage what=4
,09-16 06:40:31.294   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 06:40:31.552   927  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-16 06:40:35.506   927  3195 I ActivityManager: Killing 5622:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-16 06:40:35.792   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75eba06:true
,09-16 06:40:35.792  5686  5686 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 06:40:35.796  5686  5686 I bt_bluedroid: init
,09-16 06:40:35.796  5686  5898 I BluetoothAdapterState: Entering OffState
,09-16 06:40:35.798  5686  5899 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 06:40:35.799  5686  5899 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 06:40:35.799  5686  5899 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 06:40:35.799  5686  5899 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-16 06:40:35.799  5686  5686 I bt_bluedroid: get_profile_interface socket
09-16 06:40:35.801  5686  5902 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-16 06:40:35.801  5686  5686 I bt_bluedroid: get_profile_interface sdp
,09-16 06:40:35.803  5686  5902 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 06:40:35.807  5686  5697 I bt_bluedroid: config_hci_snoop_log
,09-16 06:40:35.809   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 06:40:35.814  5686  5898 D BluetoothAdapterState: Current state: OFF, message: 0
,09-16 06:40:35.814  5686  5898 D BluetoothAdapterProperties: Setting state to 14
09-16 06:40:35.814  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 06:40:35.816  5686  5898 D BluetoothBondStateMachine: make
,09-16 06:40:35.819  5686  5903 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 06:40:35.821  5686  5898 I BluetoothAdapterState: Entering PendingCommandState
,09-16 06:40:35.822  5686  5686 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 06:40:35.825  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:35.826  5686  5686 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 06:40:35.826  5686  5686 D BtGatt.GattService: Received start request. Starting profile...
09-16 06:40:35.826  5686  5686 D BtGatt.GattService: start()
09-16 06:40:35.826  5686  5686 I bt_bluedroid: get_profile_interface gatt
,09-16 06:40:35.827  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:40:35.827  5686  5686 D BtGatt.AdvertiseManager: advertise manager created
,09-16 06:40:35.832  5686  5686 V BluetoothAdapterState: isTurningOff()=false
,09-16 06:40:35.832  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:35.832  5686  5686 V BluetoothAdapterState: isBleTurningOn()=true
09-16 06:40:35.832  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:35.833  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 06:40:35.834  5686  5898 I bt_bluedroid: bt_bluedroid
09-16 06:40:35.834  5686  5899 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 06:40:35.835  5686  5899 I bt_hci  : start_up
,09-16 06:40:35.840  5686  5899 I bt_vendor: alloc value 0xf3cb8871
,09-16 06:40:35.840  5686  5899 I bt_vendor: init
09-16 06:40:35.840  5686  5899 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 06:40:35.840  5686  5899 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 06:40:35.952  5686  5899 D bt_hci  : start_up starting async portion
09-16 06:40:35.952  5686  5906 I bt_hci  : event_finish_startup
09-16 06:40:35.952  5686  5906 I bt_hci_h4: hal_open
,09-16 06:40:35.953  5686  5906 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 06:40:35.955  5686  5906 I bt_userial_vendor: device fd = 54 open
,09-16 06:40:35.949  5907  5907 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 06:40:35.968  5686  5906 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 06:40:35.970  5686  5906 D bt_hwcfg: Chipset BCM4358A3
,09-16 06:40:35.970  5686  5906 D bt_hwcfg: Target name = [BCM4358A3]
09-16 06:40:35.971  5686  5906 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 06:40:36.087  5833  5880 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-16 06:40:36.274  5818  5894 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-16 06:40:36.323  5686  5906 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 06:40:36.323  5686  5906 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 06:40:36.323  5686  5906 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 06:40:36.457  5686  5906 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 06:40:36.458  5686  5906 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 06:40:36.459  5686  5906 I bt_hwcfg: vendor lib fwcfg completed
09-16 06:40:36.459  5686  5906 I bt_vendor: firmware callback
,09-16 06:40:36.459  5686  5906 I bt_hci  : firmware_config_callback
09-16 06:40:36.468  5686  5913 I bt_btu  : btu_task pending for preload complete event
09-16 06:40:36.468  5686  5913 I bt_btu_task: Bluetooth chip preload is complete
09-16 06:40:36.468  5686  5913 I bt_btu  : btu_task received preload complete event
,09-16 06:40:36.474  5686  5913 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 06:40:36.474  5686  5913 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 06:40:36.474  5686  5913 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_BTM
,09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 06:40:36.475  5686  5913 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 06:40:36.476  5686  5913 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 06:40:36.476  5686  5913 I         : BTE_InitTraceLevels -- TRC_SMP
,09-16 06:40:36.476  5686  5913 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 06:40:36.476  5686  5913 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 06:40:36.556  5686  5913 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c36549
,09-16 06:40:36.556  5686  5913 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c36549 
,09-16 06:40:36.570  5686  5902 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 06:40:36.572  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 06:40:36.572  5686  5902 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 06:40:36.574  5686  5902 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 06:40:36.577  5686  5902 D BluetoothAdapterProperties: Scan Mode:20
,09-16 06:40:36.578  5686  5902 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 06:40:36.578  5686  5902 D bt_hci  : do_postload posting postload work item
09-16 06:40:36.578  5686  5906 I bt_hci  : event_postload
09-16 06:40:36.579  5686  5906 I bt_vendor: sco_config_cb
09-16 06:40:36.579  5686  5906 I bt_hci  : sco_config_callback postload finished.
09-16 06:40:36.584  5686  5902 D bt_bte_conf: Device ID record 1 : primary
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   vendorId            = 000f
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   vendorIdSource      = 0001
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   product             = 1200
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   version             = 1436
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   clientExecutableURL = 
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   serviceDescription  = 
09-16 06:40:36.584  5686  5902 D bt_bte_conf:   documentationURL    = 
,09-16 06:40:36.585  5686  5902 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 06:40:36.585  5686  5899 D bt_stack_manager: event_start_up_stack finished
09-16 06:40:36.585  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:36.586  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 06:40:36.587  5686  5898 D BluetoothAdapterProperties: Setting state to 15
09-16 06:40:36.587  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-16 06:40:36.590  5686  5898 I BluetoothAdapterState: Entering BleOnState
,09-16 06:40:36.591  5686  5906 I bt_vendor: low_power_mode_cb
09-16 06:40:36.593  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:36.593  5686  5898 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 06:40:36.593  5686  5898 D BluetoothAdapterProperties: Setting state to 11
09-16 06:40:36.593  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-16 06:40:36.595  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:36.603  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:36.605  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:36.607  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:40:36.608  5686  5686 D HeadsetService: Received start request. Starting profile...
09-16 06:40:36.611  5686  5686 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-16 06:40:36.612  5686  5686 D HeadsetStateMachine: make
09-16 06:40:36.613  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:36.623  5686  5898 I BluetoothAdapterState: Entering PendingCommandState
,09-16 06:40:36.623  5686  5686 D HeadsetStateMachine: max_hf_connections = 1
,09-16 06:40:36.624  5686  5686 I bt_bluedroid: get_profile_interface handsfree
09-16 06:40:36.624  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 06:40:36.624  5686  5902 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-16 06:40:36.628  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:36.628  5686  5686 D A2dpService: Received start request. Starting profile...
,09-16 06:40:36.629  5686  5686 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 06:40:36.629  5686  5686 I bt_bluedroid: get_profile_interface avrcp
,09-16 06:40:36.635  5686  5686 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 06:40:36.635  5686  5686 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 06:40:36.635  5686  5686 D A2dpStateMachine: make
,09-16 06:40:36.637  5686  5686 I bt_bluedroid: get_profile_interface a2dp
,09-16 06:40:36.638  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-16 06:40:36.639  5686  5921 D A2dpStateMachine: Enter Disconnected: -2
,09-16 06:40:36.640  5686  5686 I BluetoothHidServiceJni: classInitNative: succeeds
09-16 06:40:36.641  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:40:36.641  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:36.644  5686  5686 D HidService: Received start request. Starting profile...
,09-16 06:40:36.644  5686  5686 I bt_bluedroid: get_profile_interface hidhost
09-16 06:40:36.644  5638  5638 D BluetoothInputDevice: Proxy object connected
09-16 06:40:36.644  5686  5902 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c1756d
09-16 06:40:36.644  5686  5686 D HidService: setHidService(): set to: null
09-16 06:40:36.644  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 06:40:36.645  5686  5686 I BluetoothHealthServiceJni: classInitNative: succeeds
09-16 06:40:36.645  5638  5638 D HidProfile: Bluetooth service connected
,09-16 06:40:36.646  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:40:36.646  5686  5686 D HealthService: Received start request. Starting profile...
,09-16 06:40:36.648  5686  5686 I bt_bluedroid: get_profile_interface health
09-16 06:40:36.649  5686  5686 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-16 06:40:36.649  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:36.651  5686  5686 D PanService: Received start request. Starting profile...
,09-16 06:40:36.651  5686  5686 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 06:40:36.651  5686  5686 I bt_bluedroid: get_profile_interface pan
09-16 06:40:36.651  5638  5638 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 06:40:36.651  5686  5902 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-16 06:40:36.652  5638  5638 D PanProfile: Bluetooth service connected
,09-16 06:40:36.654  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:36.659  5686  5686 D BluetoothMapService: Received start request. Starting profile...
09-16 06:40:36.659  5686  5686 D BluetoothMapService: start()
09-16 06:40:36.660  5638  5638 D BluetoothMap: Proxy object connected
09-16 06:40:36.660  5638  5638 D MapProfile: Bluetooth service connected
09-16 06:40:36.660  5638  5638 D BluetoothMap: getConnectedDevices()
09-16 06:40:36.661  5638  5638 D BluetoothMap: Bluetooth is Not enabled
,09-16 06:40:36.662  5686  5686 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 06:40:36.663  5686  5686 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 06:40:36.663  5686  5686 D BluetoothMapAppObserver: createReceiver()
09-16 06:40:36.665  5686  5686 D BluetoothMapAppObserver: initObservers()
09-16 06:40:36.665  5686  5686 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 06:40:36.672  5686  5686 V SapService: SapBinder()
,09-16 06:40:36.672  5686  5686 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:36.673  5686  5686 D SapService: Received start request. Starting profile...
09-16 06:40:36.673  5686  5686 V SapService: start()
,09-16 06:40:36.675  5686  5686 V BluetoothAdapterState: isTurningOff()=false
,09-16 06:40:36.675  5686  5686 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:36.675  5686  5919 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 06:40:36.675  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.675  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isTurningOn()=true
,09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.676  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:36.677  5686  5686 V BluetoothAdapterState: isTurningOff()=false
,09-16 06:40:36.677  5686  5686 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:36.677  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.678  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:36.678  5686  5686 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:36.678  5686  5686 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:36.678  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.678  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 06:40:36.679  5686  5686 V BluetoothAdapterState: isTurningOff()=false
,09-16 06:40:36.679  5686  5686 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:36.679  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:36.679  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:36.680  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 06:40:36.680  5686  5898 D BluetoothAdapterProperties: ScanMode =  20
09-16 06:40:36.680  5686  5898 D BluetoothAdapterProperties: State =  11
09-16 06:40:36.680  5686  5898 D BluetoothAdapterProperties: Setting state to 12
09-16 06:40:36.680  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 06:40:36.680  5686  5898 I BluetoothAdapterState: Entering OnState
09-16 06:40:36.681  3135  3759 D BluetoothPan: onBluetoothStateChange on: true
09-16 06:40:36.682  5686  5902 D BluetoothAdapterProperties: Scan Mode:21
09-16 06:40:36.683  5686  5902 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 06:40:36.683  3135  3135 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 06:40:36.683  3135  3135 D PanProfile: Bluetooth service connected
09-16 06:40:36.683  5638  5648 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 06:40:36.685   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:36.685   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 06:40:36.685   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:36.685  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:36.686  3535  3844 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 06:40:36.686   927   927 D BluetoothA2dp: Proxy object connected
09-16 06:40:36.686   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:36.686  3135  3149 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 06:40:36.687  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:36.687  5638  5649 D BluetoothMap: onBluetoothStateChange: up=true
09-16 06:40:36.688  3135  3759 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 06:40:36.689  3135  3135 D BluetoothA2dp: Proxy object connected
09-16 06:40:36.689  3135  3149 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 06:40:36.690  5638  5648 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 06:40:36.690  3135  3759 D BluetoothMap: onBluetoothStateChange: up=true
,09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:36.690  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:36.691  3135  3135 D BluetoothMap: Proxy object connected
09-16 06:40:36.691  3135  3135 D MapProfile: Bluetooth service connected
09-16 06:40:36.691  3135  3149 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 06:40:36.691  3135  3135 D BluetoothMap: getConnectedDevices()
09-16 06:40:36.694  5686  5686 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 06:40:36.694  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:36.694  5686  5686 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 06:40:36.694  5638  5649 D BluetoothPan: onBluetoothStateChange on: true
09-16 06:40:36.696   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 06:40:36.698  5686  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:36.698  3135  3135 D BluetoothInputDevice: Proxy object connected
09-16 06:40:36.698  3135  3135 D HidProfile: Bluetooth service connected
,09-16 06:40:36.699  5638  5638 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-16 06:40:36.699  5686  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:36.699  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:36.700  5686  5686 D ObexServerSockets: Succeed to create listening sockets 
09-16 06:40:36.700  5686  5686 D ObexServerSockets0: startAccept()
09-16 06:40:36.700  5686  5686 D ObexServerSockets0: prepareForNewConnect()
09-16 06:40:36.701  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:36.702  5686  5686 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 06:40:36.702  5686  5686 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 06:40:36.702  5686  5928 D ObexServerSockets0: Accepting socket connection...
09-16 06:40:36.703  5686  5686 D BluetoothMapService: onReceive
,09-16 06:40:36.703  5686  5686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 06:40:36.703  5686  5686 D BluetoothMapService: STATE_ON
09-16 06:40:36.703  5686  5929 D ObexServerSockets0: Accepting socket connection...
09-16 06:40:36.703  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:36.704  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:36.705  5638  5638 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-16 06:40:36.706  5686  5930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:36.706  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:36.707  5686  5930 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 06:40:36.707  5686  5930 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 06:40:36.713  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 06:40:36.715  5638  5638 D BluetoothA2dp: Proxy object connected
,09-16 06:40:36.720  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:36.724  5638  5638 D DockEventReceiver: finishStartingService: stopping service
09-16 06:40:36.726  5638  5638 D BluetoothPbap: Proxy object connected
,09-16 06:40:36.726  3135  3135 D BluetoothPbap: Proxy object connected
09-16 06:40:36.726  3135  3135 D PbapServerProfile: Bluetooth service connected
09-16 06:40:36.727  5686  5686 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 06:40:36.727  5686  5686 D ObexServerSockets0: prepareForNewConnect()
09-16 06:40:36.727  5638  5638 D PbapServerProfile: Bluetooth service connected
,09-16 06:40:36.734  5686  5934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 06:40:36.747  5686  5938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 06:40:36.748  5686  5938 I BtOppRfcommListener: Accept thread started.
,09-16 06:40:36.786  3135  3149 D BluetoothHeadset: Proxy object connected
,09-16 06:40:36.786   927   944 D BluetoothHeadset: Proxy object connected
09-16 06:40:36.786  3135  3135 D HeadsetProfile: Bluetooth service connected
09-16 06:40:36.786  3535  3560 D BluetoothHeadset: Proxy object connected
09-16 06:40:36.786  3535  3558 D BluetoothHeadset: Proxy object connected
09-16 06:40:36.786   927   927 D BluetoothHeadset: Proxy object connected
09-16 06:40:36.786   927   927 D BluetoothHeadset: Proxy object connected
,09-16 06:40:36.786   927   927 D BluetoothHeadset: Proxy object connected
09-16 06:40:36.786   927   944 D BluetoothHeadset: Proxy object connected
,09-16 06:40:36.790  3135  3759 D BluetoothHeadset: Proxy object connected
,09-16 06:40:36.790  3135  3135 D HeadsetProfile: Bluetooth service connected
,09-16 06:40:36.807  5638  5649 D BluetoothHeadset: Proxy object connected
,09-16 06:40:36.809  5638  5638 D HeadsetProfile: Bluetooth service connected
,09-16 06:40:36.816   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:37.817   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:38.515   927  2983 D ConnectivityService: handlePromptUnvalidated 101
,09-16 06:40:38.818   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:39.819   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:40:40.778  5686  5898 D BluetoothAdapterState: Current state: ON, message: 23
,09-16 06:40:40.779  5686  5898 D BluetoothAdapterProperties: Setting state to 13
09-16 06:40:40.779  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 06:40:40.780  5686  5898 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 06:40:40.782  5686  5898 I BluetoothAdapterState: Entering PendingCommandState
,09-16 06:40:40.786  5686  5686 D BluetoothMapService: onReceive
,09-16 06:40:40.787  5686  5686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 06:40:40.787  5686  5686 D BluetoothMapService: STATE_TURNING_OFF
09-16 06:40:40.788  5686  5686 D BluetoothMapService: MAP Service closeService in
09-16 06:40:40.788  5686  5686 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 06:40:40.788  5686  5686 D ObexServerSockets0: shutdown(block = true)
09-16 06:40:40.789  5686  5928 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 06:40:40.790  5686  5686 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-16 06:40:40.790  5686  5902 D BluetoothAdapterProperties: Scan Mode:20
,09-16 06:40:40.790  5686  5686 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-16 06:40:40.790  5686  5929 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 06:40:40.792  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 06:40:40.795  5686  5915 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 06:40:40.795  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:40.795  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:40:40.796  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 06:40:40.797  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:40.797  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:40.801  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:40.801  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:40.803  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:40.803  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:40.803  5686  5686 I BtOppRfcommListener: stopping Accept Thread
09-16 06:40:40.803  5686  5938 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 06:40:40.807  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:40.808  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:40.809  5686  5938 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 06:40:40.810  5356  5356 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 06:40:40.810  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OF,F, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:40.812  5686  5686 D HeadsetService: Received stop request...Stopping profile...
09-16 06:40:40.814  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.816  5638  5638 D DockEventReceiver: finishStartingService: stopping service
09-16 06:40:40.816  3135  3147 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:40.816  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.817  3535  3844 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:40.817   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:40.817  3135  3135 D HeadsetProfile: Bluetooth service disconnected
,09-16 06:40:40.818  5638  5648 D BluetoothHeadset: Proxy object disconnected
,09-16 06:40:40.818  5686  5686 D A2dpService: Received stop request...Stopping profile...
09-16 06:40:40.818  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.818   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:40.819   927   927 D BluetoothHeadset: Proxy object disconnected
09-16 06:40:40.819  5686  5921 D A2dpStateMachine: Exit Disconnected: -1
,09-16 06:40:40.819   535   535 I ServiceManager: Waiting for service AtCmdFwd...
09-16 06:40:40.819  5638  5638 D HeadsetProfile: Bluetooth service disconnected
09-16 06:40:40.823   927   927 D BluetoothA2dp: Proxy object disconnected
09-16 06:40:40.823  5638  5638 D BluetoothA2dp: Proxy object disconnected
,09-16 06:40:40.823  3135  3135 D BluetoothA2dp: Proxy object disconnected
09-16 06:40:40.823  5686  5686 D HidService: Received stop request...Stopping profile...
,09-16 06:40:40.823  5686  5686 D HidService: Stopping Bluetooth HidService
09-16 06:40:40.824  3135  3135 D BluetoothInputDevice: Proxy object disconnected
09-16 06:40:40.824  3135  3135 D HidProfile: Bluetooth service disconnected
,09-16 06:40:40.825  5638  5638 D BluetoothInputDevice: Proxy object disconnected
09-16 06:40:40.825  5638  5638 D HidProfile: Bluetooth service disconnected
09-16 06:40:40.826  5686  5686 D HealthService: Received stop request...Stopping profile...
,09-16 06:40:40.828  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:40.830  5686  5686 D PanService: Received stop request...Stopping profile...
,09-16 06:40:40.831  3135  3135 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 06:40:40.831  5638  5638 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 06:40:40.831  3135  3135 D PanProfile: Bluetooth service disconnected
09-16 06:40:40.831  5638  5638 D PanProfile: Bluetooth service disconnected
09-16 06:40:40.832  5686  5686 D BluetoothMapService: Received stop request...Stopping profile...
09-16 06:40:40.832  5686  5686 D BluetoothMapService: stop()
,09-16 06:40:40.833  5686  5686 D BluetoothMapAppObserver: deinitObservers()
,09-16 06:40:40.833  5686  5686 D BluetoothMapAppObserver: removeReceiver()
09-16 06:40:40.834  3135  3135 D BluetoothMap: Proxy object disconnected
09-16 06:40:40.834  3135  3135 D MapProfile: Bluetooth service disconnected
09-16 06:40:40.835  5638  5638 D BluetoothMap: Proxy object disconnected
09-16 06:40:40.835  5638  5638 D MapProfile: Bluetooth service disconnected
,09-16 06:40:40.836  5686  5686 D SapService: Received stop request...Stopping profile...
09-16 06:40:40.836  5686  5686 V SapService: stop()
,09-16 06:40:40.837  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.837  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:40.838  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.838  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:40.839  5686  5686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 06:40:40.839  5686  5686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 06:40:40.839  5686  5913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:40.840  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.840  5686  5913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:40.840  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:40.840  5686  5913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:40.840  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.840  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:40.840  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 06:40:40.840  5686  5902 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-16 06:40:40.841  5686  5913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:40.841  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.841  5686  5913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:40.841  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:40.841  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.841  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 06:40:40.841  5686  5686 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 06:40:40.842  5686  5686 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 06:40:40.842  5686  5913 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 06:40:40.842  5686  5913 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 06:40:40.842  5686  5913 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 06:40:40.842  5686  5913 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 06:40:40.842  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 06:40:40.843  5686  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 06:40:40.844  5638  5638 D BluetoothPbap: Proxy object disconnected
09-16 06:40:40.844  5638  5638 D PbapServerProfile: Bluetooth service disconnected
09-16 06:40:40.844  3135  3135 D BluetoothPbap: Proxy object disconnected
09-16 06:40:40.844  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.844  3135  3135 D PbapServerProfile: Bluetooth service disconnected
09-16 06:40:40.844  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:40.844  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.844  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:40.844  5686  5686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 06:40:40.844  5686  5902 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 06:40:40.845  5686  5686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 06:40:40.845  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.845  5686  5686 V BluetoothAdapterState: isTurningOn()=false
,09-16 06:40:40.846  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.846  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:40.846  5686  5686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 06:40:40.846  5686  5686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 06:40:40.847  5686  5686 D BluetoothMapService: MAP Service closeService in
09-16 06:40:40.848  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.848  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:40.848  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.848  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:40.848  5686  5686 D BluetoothMapService: cleanup()
09-16 06:40:40.849  5686  5686 D BluetoothMapService: MAP Service closeService in
09-16 06:40:40.849  5686  5686 V BluetoothAdapterState: isTurningOff()=true
09-16 06:40:40.849  5686  5686 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:40.849  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:40.849  5686  5686 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:40.850  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 06:40:40.850  5686  5898 D BluetoothAdapterProperties: Setting state to 15
09-16 06:40:40.850  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 06:40:40.851  5686  5898 I BluetoothAdapterState: Entering BleOnState
09-16 06:40:40.853  3135  3147 D BluetoothPan: onBluetoothStateChange on: false
,09-16 06:40:40.854  5638  5648 D BluetoothPbap: onBluetoothStateChange: up=false
,09-16 06:40:40.856   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:40.856  5638  5942 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 06:40:40.856   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 06:40:40.856   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:40.857  5638  5649 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:40.857  3535  3558 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:40.857   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:40.857  3135  3149 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 06:40:40.858  5638  5648 D BluetoothMap: onBluetoothStateChange: up=false
09-16 06:40:40.858  3135  3759 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 06:40:40.859  3135  3147 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 06:40:40.859  5638  5942 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 06:40:40.860  3135  3149 D BluetoothMap: onBluetoothStateChange: up=false
09-16 06:40:40.860  3135  3759 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 06:40:40.861  5638  5649 D BluetoothPan: onBluetoothStateChange on: false
09-16 06:40:40.862  5686  5898 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 06:40:40.862  5686  5898 D BluetoothAdapterProperties: Setting state to 16
09-16 06:40:40.862  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 06:40:40.862  5686  5898 D BluetoothAdapterProperties: onBleDisable
09-16 06:40:40.863  5686  5898 I BluetoothAdapterState: Entering PendingCommandState
09-16 06:40:40.863  5686  5899 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 06:40:40.863  5686  5913 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 06:40:40.863  5686  5913 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 06:40:40.867  5686  5902 D BluetoothAdapterProperties: Scan Mode:20
09-16 06:40:40.867  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 06:40:40.868  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.869  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.871  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.873  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:40.875  5638  5638 D DockEventReceiver: finishStartingService: stopping service
09-16 06:40:40.876  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.879  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:40.880  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:41.078  5686  5902 I bt_hci  : shut_down
,09-16 06:40:41.088  5686  5906 D bt_hwcfg: hw_epilog_process
,09-16 06:40:41.088  5686  5906 I bt_vendor: low_power_mode_cb
,09-16 06:40:41.091  5686  5906 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-16 06:40:41.091  5686  5906 I bt_vendor: epilog_cb
09-16 06:40:41.091  5686  5906 I bt_hci  : epilog_finished_callback
,09-16 06:40:41.094  5686  5902 I bt_hci_h4: hal_close
,09-16 06:40:41.094  5686  5902 I bt_userial_vendor: device fd = 54 close
,09-16 06:40:41.209  5686  5899 D bt_stack_manager: event_shut_down_stack finished.
,09-16 06:40:41.210  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 06:40:41.215  5686  5898 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 06:40:41.215  5686  5686 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 06:40:41.216  5686  5686 D BtGatt.GattService: Received stop request...Stopping profile...
,09-16 06:40:41.217  5686  5686 D BtGatt.GattService: stop()
,09-16 06:40:41.217  5686  5686 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 06:40:41.220  5686  5686 V BluetoothAdapterState: isTurningOff()=false
,09-16 06:40:41.220  5686  5686 V BluetoothAdapterState: isTurningOn()=false
,09-16 06:40:41.220  5686  5686 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:41.220  5686  5686 V BluetoothAdapterState: isBleTurningOff()=true
,09-16 06:40:41.221  5686  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 06:40:41.221  5686  5898 D BluetoothAdapterProperties: Setting state to 10
,09-16 06:40:41.221  5686  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 06:40:41.222  5686  5898 I BluetoothAdapterState: Entering OffState
,09-16 06:40:41.223   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 06:40:41.237  5686  5686 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 06:40:41.237  5686  5686 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 06:40:41.237  5686  5686 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 06:40:41.239  5686  5899 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 06:40:41.246  5686  5686 I art     : System.exit called, status: 0
,09-16 06:40:41.246  5686  5686 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 06:40:41.275   927  3581 I ActivityManager: Process com.android.bluetooth (pid 5686) has died
,09-16 06:40:41.820   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:40:45.776  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 06:40:45.777  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:40:45.781  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:40:45.782  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d275520 removed from the list
09-16 06:40:45.782  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 06:40:45.782  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:45.782  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:45.784  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 06:40:45.785  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73409e added. We now have 4 listener(s)
,09-16 06:40:45.785  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 06:40:45.787  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:45.787  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73409e removed from the list
09-16 06:40:45.787  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:45.787  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:45.787  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:45.789  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:40:45.789  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f6d77f added. We now have 4 listener(s)
09-16 06:40:45.789  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 06:40:50.799  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:50.828   927   944 I ActivityManager: Start proc 5947:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 06:40:50.910  5947  5947 D AdapterServiceConfig: Adding HeadsetService
,09-16 06:40:50.910  5947  5947 D AdapterServiceConfig: Adding A2dpService
09-16 06:40:50.910  5947  5947 D AdapterServiceConfig: Adding HidService
,09-16 06:40:50.911  5947  5947 D AdapterServiceConfig: Adding HealthService
09-16 06:40:50.911  5947  5947 D AdapterServiceConfig: Adding PanService
09-16 06:40:50.911  5947  5947 D AdapterServiceConfig: Adding GattService
09-16 06:40:50.911  5947  5947 D AdapterServiceConfig: Adding BluetoothMapService
09-16 06:40:50.911  5947  5947 D AdapterServiceConfig: Adding SapService
,09-16 06:40:50.922   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2052320:true
,09-16 06:40:50.922  5947  5947 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 06:40:50.924  5947  5947 I bt_bluedroid: init
,09-16 06:40:50.925  5947  5959 I BluetoothAdapterState: Entering OffState
,09-16 06:40:50.927  5947  5960 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 06:40:50.927  5947  5960 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 06:40:50.927  5947  5960 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 06:40:50.927  5947  5960 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-16 06:40:50.928  5947  5947 I bt_bluedroid: get_profile_interface socket
,09-16 06:40:50.929  5947  5963 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-16 06:40:50.929  5947  5947 I bt_bluedroid: get_profile_interface sdp
,09-16 06:40:50.931  5947  5963 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 06:40:50.936  5947  5957 I bt_bluedroid: config_hci_snoop_log
09-16 06:40:50.938   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 06:40:50.942  5947  5959 D BluetoothAdapterState: Current state: OFF, message: 0
09-16 06:40:50.942  5947  5959 D BluetoothAdapterProperties: Setting state to 14
09-16 06:40:50.942  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 06:40:50.944  5947  5959 D BluetoothBondStateMachine: make
,09-16 06:40:50.946  5947  5964 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 06:40:50.948  5947  5959 I BluetoothAdapterState: Entering PendingCommandState
,09-16 06:40:50.949  5947  5947 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 06:40:50.951  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:40:50.952  5947  5947 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 06:40:50.952  5947  5947 D BtGatt.GattService: Received start request. Starting profile...
09-16 06:40:50.952  5947  5947 D BtGatt.GattService: start()
09-16 06:40:50.953  5947  5947 I bt_bluedroid: get_profile_interface gatt
09-16 06:40:50.953  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
09-16 06:40:50.953  5947  5947 D BtGatt.AdvertiseManager: advertise manager created
,09-16 06:40:50.959  5947  5947 V BluetoothAdapterState: isTurningOff()=false
,09-16 06:40:50.959  5947  5947 V BluetoothAdapterState: isTurningOn()=false
09-16 06:40:50.959  5947  5947 V BluetoothAdapterState: isBleTurningOn()=true
09-16 06:40:50.959  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:50.959  5947  5959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 06:40:50.960  5947  5959 I bt_bluedroid: bt_bluedroid
09-16 06:40:50.961  5947  5960 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 06:40:50.961  5947  5960 I bt_hci  : start_up
,09-16 06:40:50.966  5947  5960 I bt_vendor: alloc value 0xf3d19871
,09-16 06:40:50.966  5947  5960 I bt_vendor: init
09-16 06:40:50.966  5947  5960 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 06:40:50.967  5947  5960 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 06:40:51.079  5947  5960 D bt_hci  : start_up starting async portion
,09-16 06:40:51.080  5947  5967 I bt_hci  : event_finish_startup
09-16 06:40:51.080  5947  5967 I bt_hci_h4: hal_open
09-16 06:40:51.080  5947  5967 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 06:40:51.083  5947  5967 I bt_userial_vendor: device fd = 54 open
,09-16 06:40:51.075  5968  5968 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 06:40:51.099  5947  5967 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 06:40:51.103  5947  5967 D bt_hwcfg: Chipset BCM4358A3
,09-16 06:40:51.103  5947  5967 D bt_hwcfg: Target name = [BCM4358A3]
09-16 06:40:51.103  5947  5967 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 06:40:51.604  5947  5967 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 06:40:51.604  5947  5967 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 06:40:51.604  5947  5967 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 06:40:51.737  5947  5967 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 06:40:51.737  5947  5967 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-16 06:40:51.739  5947  5967 I bt_hwcfg: vendor lib fwcfg completed
,09-16 06:40:51.739  5947  5967 I bt_vendor: firmware callback
,09-16 06:40:51.739  5947  5967 I bt_hci  : firmware_config_callback
,09-16 06:40:51.749  5947  5970 I bt_btu  : btu_task pending for preload complete event
,09-16 06:40:51.749  5947  5970 I bt_btu_task: Bluetooth chip preload is complete
09-16 06:40:51.749  5947  5970 I bt_btu  : btu_task received preload complete event
,09-16 06:40:51.755  5947  5970 I         : BTE_InitTraceLevels -- TRC_HCI
,09-16 06:40:51.755  5947  5970 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 06:40:51.755  5947  5970 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 06:40:51.755  5947  5970 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_A2D
,09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 06:40:51.756  5947  5970 I         : BTE_InitTraceLevels -- TRC_SDP
,09-16 06:40:51.757  5947  5970 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 06:40:51.757  5947  5970 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 06:40:51.757  5947  5970 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 06:40:51.757  5947  5970 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 06:40:51.841  5947  5970 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c97549
09-16 06:40:51.841  5947  5970 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c97549 
,09-16 06:40:51.865  5947  5963 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 06:40:51.866  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 06:40:51.867  5947  5963 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 06:40:51.869  5947  5963 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 06:40:51.873  5947  5963 D BluetoothAdapterProperties: Scan Mode:20
,09-16 06:40:51.873  5947  5963 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 06:40:51.874  5947  5963 D bt_hci  : do_postload posting postload work item
09-16 06:40:51.874  5947  5967 I bt_hci  : event_postload
09-16 06:40:51.874  5947  5967 I bt_vendor: sco_config_cb
09-16 06:40:51.874  5947  5967 I bt_hci  : sco_config_callback postload finished.
,09-16 06:40:51.877  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:51.881  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:51.881  5947  5967 I bt_vendor: low_power_mode_cb
,09-16 06:40:51.882  5947  5963 D bt_bte_conf: Device ID record 1 : primary
09-16 06:40:51.882  5947  5963 D bt_bte_conf:   vendorId            = 000f
09-16 06:40:51.882  5947  5963 D bt_bte_conf:   vendorIdSource      = 0001
,09-16 06:40:51.882  5947  5963 D bt_bte_conf:   product             = 1200
09-16 06:40:51.882  5947  5963 D bt_bte_conf:   version             = 1436
09-16 06:40:51.882  5947  5963 D bt_bte_conf:   clientExecutableURL = 
09-16 06:40:51.882  5947  5963 D bt_bte_conf:   serviceDescription  = 
09-16 06:40:51.883  5947  5963 D bt_bte_conf:   documentationURL    = 
09-16 06:40:51.883  5947  5963 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 06:40:51.883  5947  5960 D bt_stack_manager: event_start_up_stack finished
09-16 06:40:51.884  5947  5959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-16 06:40:51.884  5947  5959 D BluetoothAdapterProperties: Setting state to 15
09-16 06:40:51.884  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 06:40:51.886  5947  5959 I BluetoothAdapterState: Entering BleOnState
,09-16 06:40:51.890  5947  5959 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 06:40:51.890  5947  5959 D BluetoothAdapterProperties: Setting state to 11
09-16 06:40:51.890  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 06:40:51.894   927   940 I ActivityManager: Killing 5701:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-16 06:40:51.895  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:51.897  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:51.913  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.914  5947  5947 D HeadsetService: Received start request. Starting profile...
,09-16 06:40:51.914   927  3581 I ActivityManager: Killing 4864:com.google.android.calendar/u0a36 (adj 15): empty #17
09-16 06:40:51.917  5947  5947 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-16 06:40:51.917  5947  5947 D HeadsetStateMachine: make
,09-16 06:40:51.942  5947  5947 D HeadsetStateMachine: max_hf_connections = 1
,09-16 06:40:51.942  5947  5947 I bt_bluedroid: get_profile_interface handsfree
09-16 06:40:51.942  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 06:40:51.942  5947  5963 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-16 06:40:51.947  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.948  5947  5947 D A2dpService: Received start request. Starting profile...
09-16 06:40:51.949  5947  5947 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 06:40:51.949  5947  5947 I bt_bluedroid: get_profile_interface avrcp
,09-16 06:40:51.951  5947  5959 I BluetoothAdapterState: Entering PendingCommandState
,09-16 06:40:51.954  5947  5947 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 06:40:51.954  5947  5947 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 06:40:51.954  5947  5947 D A2dpStateMachine: make
09-16 06:40:51.955  5947  5947 I bt_bluedroid: get_profile_interface a2dp
09-16 06:40:51.956  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-16 06:40:51.957  5947  5979 D A2dpStateMachine: Enter Disconnected: -2
,09-16 06:40:51.960  5947  5947 I BluetoothHidServiceJni: classInitNative: succeeds
,09-16 06:40:51.961  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 06:40:51.961  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.962  5947  5947 D HidService: Received start request. Starting profile...
,09-16 06:40:51.962  5947  5947 I bt_bluedroid: get_profile_interface hidhost
09-16 06:40:51.963  5947  5963 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c7856d
09-16 06:40:51.963  5947  5947 D HidService: setHidService(): set to: null
09-16 06:40:51.963  5947  5963 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 06:40:51.963  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.963  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.963  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.963  5947  5977 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 06:40:51.963  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:51.964  5947  5947 I BluetoothHealthServiceJni: classInitNative: succeeds
09-16 06:40:51.964  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.965  5947  5947 D HealthService: Received start request. Starting profile...
,09-16 06:40:51.966  5947  5947 I bt_bluedroid: get_profile_interface health
,09-16 06:40:51.967  5947  5947 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-16 06:40:51.968  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.968  5947  5947 D PanService: Received start request. Starting profile...
09-16 06:40:51.969  5947  5947 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 06:40:51.969  5947  5947 I bt_bluedroid: get_profile_interface pan
,09-16 06:40:51.969  5947  5963 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-16 06:40:51.971  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.972  5947  5947 D BluetoothMapService: Received start request. Starting profile...
,09-16 06:40:51.972  5947  5947 D BluetoothMapService: start()
09-16 06:40:51.975  5947  5947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 06:40:51.976  5947  5947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 06:40:51.976  5947  5947 D BluetoothMapAppObserver: createReceiver()
,09-16 06:40:51.978  5947  5947 D BluetoothMapAppObserver: initObservers()
,09-16 06:40:51.978  5947  5947 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 06:40:51.985  5947  5947 V SapService: SapBinder()
,09-16 06:40:51.985  5947  5947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:40:51.985  5947  5947 D SapService: Received start request. Starting profile...
09-16 06:40:51.985  5947  5947 V SapService: start()
,09-16 06:40:51.986  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.987  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.988  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 06:40:51.989  5947  5947 V BluetoothAdapterState: isTurningOff()=false
09-16 06:40:51.989  5947  5947 V BluetoothAdapterState: isTurningOn()=true
09-16 06:40:51.989  5947  5947 V BluetoothAdapterState: isBleTurningOn()=false
09-16 06:40:51.989  5947  5947 V BluetoothAdapterState: isBleTurningOff()=false
09-16 06:40:51.989  5947  5959 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-16 06:40:51.989  5947  5959 D BluetoothAdapterProperties: ScanMode =  20
,09-16 06:40:51.989  5947  5959 D BluetoothAdapterProperties: State =  11
09-16 06:40:51.990  5947  5959 D BluetoothAdapterProperties: Setting state to 12
09-16 06:40:51.990  5947  5959 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 06:40:51.990  5947  5959 I BluetoothAdapterState: Entering OnState
09-16 06:40:51.990  3135  3149 D BluetoothPan: onBluetoothStateChange on: true
09-16 06:40:51.991  5947  5963 D BluetoothAdapterProperties: Scan Mode:21
09-16 06:40:51.991  5947  5963 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:51.994  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:40:51.995  5638  5942 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 06:40:51.995  3135  3135 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 06:40:51.995  3135  3135 D PanProfile: Bluetooth service connected
09-16 06:40:51.996  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:51.997   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:51.997  5638  5649 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 06:40:51.999   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 06:40:51.999   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:51.999  5638  5648 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:51.999   927   927 D BluetoothA2dp: Proxy object connected
09-16 06:40:52.000  3535  3560 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:52.000  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:40:52.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 06:40:52.001  3135  3759 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 06:40:52.002  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:40:52.002  5638  5649 D BluetoothMap: onBluetoothStateChange: up=true
09-16 06:40:52.004  3135  3149 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 06:40:52.004  5947  5947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 06:40:52.005  5947  5947 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 06:40:52.005  3135  3135 D BluetoothA2dp: Proxy object connected
09-16 06:40:52.006  3135  3759 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 06:40:52.007  5947  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:52.007  5638  5942 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 06:40:52.009  5947  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:52.009  5638  5638 D BluetoothA2dp: Proxy object connected
09-16 06:40:52.009  3135  3147 D BluetoothMap: onBluetoothStateChange: up=true
,09-16 06:40:52.010  5947  5947 D ObexServerSockets: Succeed to create listening sockets 
09-16 06:40:52.010  5947  5947 D ObexServerSockets0: startAccept()
09-16 06:40:52.010  5947  5947 D ObexServerSockets0: prepareForNewConnect()
09-16 06:40:52.011  3135  3149 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 06:40:52.012  5947  5947 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 06:40:52.012  5947  5947 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 06:40:52.012  5947  5984 D ObexServerSockets0: Accepting socket connection...
09-16 06:40:52.013  5947  5985 D ObexServerSockets0: Accepting socket connection...
09-16 06:40:52.013  5638  5648 D BluetoothPan: onBluetoothStateChange on: true
09-16 06:40:52.013  3135  3135 D BluetoothMap: Proxy object connected
09-16 06:40:52.013  3135  3135 D MapProfile: Bluetooth service connected
09-16 06:40:52.013  3135  3135 D BluetoothMap: getConnectedDevices()
09-16 06:40:52.013  5638  5638 D BluetoothMap: Proxy object connected
09-16 06:40:52.013  5638  5638 D MapProfile: Bluetooth service connected
09-16 06:40:52.014  5638  5638 D BluetoothMap: getConnectedDevices()
09-16 06:40:52.017  5947  5947 D BluetoothMapService: onReceive
09-16 06:40:52.017  5947  5947 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 06:40:52.017  5947  5947 D BluetoothMapService: STATE_ON
09-16 06:40:52.017   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 06:40:52.015  3135  3135 D BluetoothInputDevice: Proxy object connected
09-16 06:40:52.018  3135  3135 D HidProfile: Bluetooth service connected
09-16 06:40:52.019  5638  5638 D BluetoothInputDevice: Proxy object connected
09-16 06:40:52.019  5638  5638 D HidProfile: Bluetooth service connected
09-16 06:40:52.019  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:40:52.020  5947  5987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:40:52.021  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:40:52.021  5638  5638 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 06:40:52.021  5638  5638 D PanProfile: Bluetooth service connected
09-16 06:40:52.022  5947  5987 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 06:40:52.022  5947  5987 D BluetoothSdpJni: SDP Create record success - handle: 1
09-16 06:40:52.025  5638  5638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 06:40:52.032  5638  5638 D DockEventReceiver: finishStartingService: stopping service
09-16 06:40:52.032  3652  3652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 06:40:52.038  3135  3135 D BluetoothPbap: Proxy object connected
,09-16 06:40:52.038  3135  3135 D PbapServerProfile: Bluetooth service connected
,09-16 06:40:52.041  5638  5638 D BluetoothPbap: Proxy object connected
09-16 06:40:52.041  5638  5638 D PbapServerProfile: Bluetooth service connected
,09-16 06:40:52.043  5947  5947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 06:40:52.043  5947  5947 D ObexServerSockets0: prepareForNewConnect()
09-16 06:40:52.045  5947  5991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 06:40:52.060  5947  5995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 06:40:52.062  5947  5995 I BtOppRfcommListener: Accept thread started.
,09-16 06:40:52.099  3135  3759 D BluetoothHeadset: Proxy object connected
,09-16 06:40:52.099  3135  3135 D HeadsetProfile: Bluetooth service connected
09-16 06:40:52.099  3535  3844 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.099   927   927 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.100   927   944 D BluetoothHeadset: Proxy object connected
,09-16 06:40:52.100  5638  5942 D BluetoothHeadset: Proxy object connected
,09-16 06:40:52.100  5638  5649 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.100   927   927 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.100   927   927 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.101  3535  3558 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.102   927   944 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.104  5638  5638 D HeadsetProfile: Bluetooth service connected
09-16 06:40:52.105  5638  5638 D HeadsetProfile: Bluetooth service connected
,09-16 06:40:52.107  3135  3147 D BluetoothHeadset: Proxy object connected
09-16 06:40:52.107  3135  3135 D HeadsetProfile: Bluetooth service connected
,09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:40:55.816  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:40:55.822  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:40:55.822  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:40:55.823  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f6d77f removed from the list
,09-16 06:40:55.823  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:40:55.823  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:40:55.823  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:40:55.825  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:40:55.826  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7fca34c added. We now have 4 listener(s)
09-16 06:40:55.826  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 06:40:55.829   927  3595 D WifiService: setWifiEnabled: false pid=5356, uid=10077
,09-16 06:40:55.829   927  3595 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 06:41:00.838  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:00.839   927  3121 D WifiService: setWifiEnabled: true pid=5356, uid=10077
09-16 06:41:00.839   927  3121 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 06:41:00.846   507   922 D SoftapController: Softap fwReload - Ok
,09-16 06:41:00.851   507   922 D CommandListener: Setting iface cfg
09-16 06:41:00.851   507   922 D CommandListener: Trying to bring down wlan0
,09-16 06:41:00.854   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-16 06:41:00.860   927  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 06:41:01.474   927  2981 D wifi    : set interface wlan0 flags (UP)
,09-16 06:41:01.475   927  2981 I WifiHAL : Initializing wifi
09-16 06:41:01.476   927  2981 I WifiHAL : Creating socket
,09-16 06:41:01.480   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 06:41:01.484   927  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 06:41:01.485   927  2981 D wifi    : Did set static halHandle = 0x7f6be18ea0
09-16 06:41:01.485   927  2981 D wifi    : halHandle = 0x7f6be18ea0, mVM = 0x7f81b4d140, mCls = 0x1066
,09-16 06:41:01.485   927  2981 D wifi    : array field set
09-16 06:41:01.485   927  2981 I WifiNative-HAL: interface[0] = wlan0
09-16 06:41:01.488   927  6001 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547270790816
,09-16 06:41:01.488   927  6001 D wifi    : waitForHalEvents called, vm = 0x7f81b4d140, obj = 0x1066, env = 0x7f663dc440
,09-16 06:41:01.534  6002  6002 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 06:41:01.555  6002  6002 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 06:41:01.565  6002  6002 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 06:41:01.565  6002  6002 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 06:41:01.588   927  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 06:41:01.599  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:01.603   927  2981 D WifiConfigStore: Loading config and enabling all networks 
,09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:41:01.607  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:41:01.609  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:41:01.611  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 06:41:01.613  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:41:01.615  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:01.619   927  2981 D WifiConfigStore: loaded 0 passpoint configs
,09-16 06:41:01.620   927  2981 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 06:41:01.620   927  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 06:41:01.621   927  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 06:41:01.622   927  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 06:41:01.623   927  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 06:41:01.623   927  2981 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-16 06:41:01.623   927  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 06:41:01.627   927  2981 D WifiNative-HAL: Setting external_sim to 1
09-16 06:41:01.627  4288  4288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 06:41:01.627   927  2981 D wifi    : setting dfs flag to true, 0x7f6813b880
09-16 06:41:01.628   927  2981 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 06:41:01.628   927  2981 D wifi    : setting scan oui 0x7f6813b880
09-16 06:41:01.628   927  2981 D WifiHAL : Sending mac address OUI
,09-16 06:41:01.633   927  2981 E native  : do suspend false
,09-16 06:41:01.640   927  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-16 06:41:01.640   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 06:41:01.640   927   927 D RttService: SCAN_AVAILABLE : 3
09-16 06:41:01.640   927  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 06:41:01.641   507   922 D CommandListener: Setting iface cfg
,09-16 06:41:01.645   927  2980 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,09-16 06:41:01.645   927  2980 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 06:41:01.653   927  2980 D WifiNative-HAL: p2pGetDeviceAddress
09-16 06:41:01.653   927  2980 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 06:41:01.659   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=414203 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-16 06:41:01.820   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:02.821   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:03.822   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:04.823   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:04.829  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:04.835  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:04.839  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:04.844  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:04.891   927  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 06:41:04.892   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-16 06:41:04.892   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:41:04.905   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 06:41:04.939   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 06:41:04.941  6002  6002 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-16 06:41:05.367  6002  6002 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 06:41:05.404  6002  6002 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 06:41:05.404  6002  6002 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 06:41:05.414   927  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 06:41:05.414   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 06:41:05.414   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 06:41:05.430   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:41:05.442   507   922 D CommandListener: Setting iface cfg
,09-16 06:41:05.448   927  2981 D WifiStateMachine: Start Dhcp Watchdog 3
,09-16 06:41:05.455   927  6007 D DhcpClient: Receive thread started
,09-16 06:41:05.459   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 06:41:05.459   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-16 06:41:05.459   927  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-16 06:41:05.541   927  2981 E native  : do suspend false
,09-16 06:41:05.552   927  6006 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 06:41:05.564   927  6007 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-16 06:41:05.564   927  6006 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-16 06:41:05.567   927  6006 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 06:41:05.580   927  6007 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 06:41:05.580   927  6006 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-16 06:41:05.584   507   922 D CommandListener: Setting iface cfg
,09-16 06:41:05.588   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 06:41:05.593   927  6006 D DhcpClient: Scheduling renewal in 86399s
,09-16 06:41:05.607   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 06:41:05.608   927  2981 D WifiConfigStore: No blacklist allowed without epno enabled
09-16 06:41:05.609   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-16 06:41:05.611   927  2983 D ConnectivityService: Adding iface wlan0 to network 102
09-16 06:41:05.617   927  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 06:41:05.666   927  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-16 06:41:05.667   927  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-16 06:41:05.668   927  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-16 06:41:05.671   927  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-16 06:41:05.673   927  2983 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-16 06:41:05.681   927  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 06:41:05.686   927  2983 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-16 06:41:05.686   927  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-16 06:41:05.686   927  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-16 06:41:05.686   927  2983 D ConnectivityService:    accepting network in place of null
09-16 06:41:05.687   927  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 06:41:05.688   927  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 06:41:05.688   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-16 06:41:05.698   927  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418243, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:41:05.708   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:41:05.741   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:41:05.743   927  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-16 06:41:05.743   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:41:05.744  3501  3698 W QCNEJ   : |CORE| network available: 102
,09-16 06:41:05.746   927  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-16 06:41:05.746  3501  3698 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-16 06:41:05.747  3501  3698 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-16 06:41:05.748   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 06:41:05.749  3501  3698 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:05.756  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:41:05.758  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:05.765  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:05.769  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:05.770  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 06:41:05.770  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 06:41:05.771  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 06:41:05.771  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:41:05.771  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-16 06:41:05.771  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:41:05.772  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 06:41:05.772  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:41:05.772  4938  4938 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 06:41:05.773  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 06:41:05.773  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:41:05.773  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:41:05.774   927  6004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-16 06:41:05.774  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:41:05.774  4938  4938 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 06:41:05.779  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000f003000000000000ffffffff]
09-16 06:41:05.779  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:41:05.779  4938  4952 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,09-16 06:41:05.780  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:41:05.780  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 06:41:05.781  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000f103000000000000ffffffff]
09-16 06:41:05.781  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:41:05.781  4938  4952 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-16 06:41:05.781  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:41:05.782  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 06:41:05.789   927   938 I ActivityManager: Start proc 6016:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-16 06:41:05.804  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 06:41:05.810  3889  5455 I iu.UploadsManager: num queued entries: 0
,09-16 06:41:05.810  3889  5455 I iu.UploadsManager: num updated entries: 0
09-16 06:41:05.812  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-16 06:41:05.814  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 06:41:05.816  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:41:05.820   927  6004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 10:41:05 GMT], X-Android-Received-Millis=[1474022465819], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474022465797]}
,09-16 06:41:05.820   927  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-16 06:41:05.820  5472  5472 D SprintDMHelper: simOperator: 
09-16 06:41:05.821  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-16 06:41:05.821   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-16 06:41:05.821   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-16 06:41:05.822   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 06:41:05.823  3889  5455 I iu.SyncManager: NEXT; no task
09-16 06:41:05.824   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:05.830  6016  6016 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:05.851  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:05.853  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:05.853  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:41:05.853  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7fca34c removed from the list
09-16 06:41:05.853  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:41:05.853  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:05.853  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:05.858  5356  6037 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-16 06:41:05.859  5356  6037 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 06:41:05.887  6016  6035 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,09-16 06:41:05.948  4288  6032 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 06:41:05.952  6016  6035 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,09-16 06:41:05.985  6016  6035 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-16 06:41:06.005  6016  6016 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-16 06:41:06.008  6052  6052 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads618796550.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads618796550.dex
,09-16 06:41:06.042  6052  6052 I dex2oat : dex2oat took 34.809ms (threads: 2) arena alloc=159KB java alloc=37KB native alloc=1258KB free=1045KB
,09-16 06:41:06.111  6016  6016 W InstanceID/Rpc: Found 10012
,09-16 06:41:06.526   927  3121 I ActivityManager: Killing 5740:com.google.android.partnersetup/u0a18 (adj 15): empty #17
,09-16 06:41:06.824   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:41:08.474   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 06:41:08.868  5356  6037 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-16 06:41:08.868  5356  6110 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-16 06:41:08.872  5356  6110 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-16 06:41:08.872  5356  6037 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-16 06:41:08.873  5356  6037 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 06:41:08.873  5356  6110 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 06:41:08.874  5356  6037 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 06:41:08.874  5356  6110 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 06:41:08.876  5356  6110 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-16 06:41:08.877  5356  6037 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-16 06:41:08.879  5356  6113 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 149, name: OutgoingSocketThread/Sender)
,09-16 06:41:08.882  5356  6112 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 150, name: IncomingSocketThread/Sender)
,09-16 06:41:08.883  5356  6114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 151, name: IncomingSocketThread/Receiver)
09-16 06:41:08.884  5356  6115 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Receiver)
,09-16 06:41:08.884  5356  6114 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 151, thread name: IncomingSocketThread/Receiver)
,09-16 06:41:08.884  5356  6114 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-16 06:41:08.884  5356  6114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 151, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-16 06:41:08.886  5356  6115 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 152, thread name: OutgoingSocketThread/Receiver)
09-16 06:41:08.886  5356  6115 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-16 06:41:08.886  5356  6115 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 152, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-16 06:41:11.865  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-16 06:41:11.866  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-16 06:41:11.872  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f4c6a67 Bundle[{}]
,09-16 06:41:11.873  5356  5402 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 06:41:11.874  5356  5402 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-16 06:41:11.876  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-16 06:41:11.877  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-16 06:41:11.877  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-16 06:41:11.879  5356  5402 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-16 06:41:11.886  5356  5402 I System.out: Running OutgoingSocketThread
,09-16 06:41:11.889  5356  6116 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-16 06:41:11.889  5356  6116 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 06:41:13.692   927  2983 D ConnectivityService: handlePromptUnvalidated 102
,09-16 06:41:14.899  5356  6117 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-16 06:41:14.900  5356  6116 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-16 06:41:14.900  5356  6117 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-16 06:41:14.900  5356  6116 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-16 06:41:14.900  5356  6117 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-16 06:41:14.900  5356  6116 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 06:41:14.903  5356  6117 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 06:41:14.903  5356  6116 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 06:41:14.905  5356  6120 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: IncomingSocketThread/Sender)
09-16 06:41:14.906  5356  6117 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-16 06:41:14.907  5356  6119 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: OutgoingSocketThread/Sender)
,09-16 06:41:14.908  5356  6116 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-16 06:41:14.915  5356  6121 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Receiver)
,09-16 06:41:14.915  5356  6122 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: OutgoingSocketThread/Receiver)
09-16 06:41:14.916  5356  6122 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: OutgoingSocketThread/Receiver)
09-16 06:41:14.916  5356  6121 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: IncomingSocketThread/Receiver)
09-16 06:41:14.916  5356  6122 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-16 06:41:14.916  5356  6121 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-16 06:41:14.917  5356  6121 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-16 06:41:14.917  5356  6122 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-16 06:41:16.655   927  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,09-16 06:41:17.898  5356  5402 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 173)
,09-16 06:41:17.899  5356  5402 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-16 06:41:17.900  5356  5402 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 174)
,09-16 06:41:17.905  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 06:41:17.906  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91adf95 added. We now have 3 listener(s)
,09-16 06:41:17.910  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 06:41:17.911  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:41:17.911  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:41:17.911  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:41:17.911  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cec8aa added. We now have 4 listener(s)
09-16 06:41:17.911  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 06:41:17.913  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 06:41:17.919  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:17.926  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:17.929  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:17.929  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:41:17.929  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:41:17.930  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:41:17.930  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:41:17.930  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:17.930  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:17.930  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-16 06:41:17.930  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 06:41:17.930  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91adf95 removed from the list
09-16 06:41:17.930  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:17.930  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cec8aa removed from the list
,09-16 06:41:17.933  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:17.933  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:41:17.933  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:17.934  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:17.934  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:17.935  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:17.935  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:41:17.935  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:17.935  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cec8aa not in the list
09-16 06:41:17.935  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:17.935  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:17.937  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:41:17.937  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:17.937  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:17.937  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cec8aa not in the list
09-16 06:41:17.937  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:17.937  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:41:17.937  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:17.937  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:17.937  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91adf95 not in the list
09-16 06:41:17.938  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 06:41:17.938  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef6a838 added. We now have 3 listener(s)
,09-16 06:41:17.940  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 06:41:17.940  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:41:17.940  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:41:17.941  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 06:41:17.941  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@996e011 added. We now have 4 listener(s)
09-16 06:41:17.941  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:41:17.942  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 06:41:17.945  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:17.950  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:41:17.951  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:17.951  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:41:17.952  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:41:17.952  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 06:41:17.952  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 06:41:17.952  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:41:17.952  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 06:41:17.956  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 06:41:17.956  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 06:41:17.957  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:17.960  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:17.960  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 06:41:17.960  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 06:41:17.960  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 06:41:17.964  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 06:41:17.964  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 06:41:17.964  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 06:41:17.964  5356  5402 D BluetoothAdapter: STATE_ON
,09-16 06:41:17.968  5947  5957 D BtGatt.GattService: registerClient() - UUID=fd902e62-88f8-45dd-abb6-627e5df313b1
09-16 06:41:17.968  5947  5963 D BtGatt.GattService: onClientRegistered() - UUID=fd902e62-88f8-45dd-abb6-627e5df313b1, clientIf=5
,09-16 06:41:17.969  5356  5367 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 06:41:17.970  5947  5986 D BtGatt.GattService: start scan with filters
,09-16 06:41:17.973  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 06:41:17.974  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 06:41:17.974  5947  5966 D BtGatt.ScanManager: handling starting scan
09-16 06:41:17.974  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 06:41:17.974  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 06:41:17.976  5947  5966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0dd568
,09-16 06:41:17.976  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:41:17.976  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 06:41:17.977  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 06:41:17.978  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 06:41:17.981  5356  5402 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 06:41:17.981  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:41:17.981  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 06:41:17.981  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:17.981  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 06:41:17.981  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:41:17.981  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:41:17.981  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 06:41:17.981  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 06:41:17.981  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 06:41:17.982  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 06:41:17.984  5356  5402 D BluetoothAdapter: STATE_ON
,09-16 06:41:17.984  5947  5963 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 06:41:17.984  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:17.984  5947  5966 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 06:41:17.985  5947  5986 D BtGatt.GattService: stopScan() - queue size =1
,09-16 06:41:17.986  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 06:41:17.986  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 06:41:17.986  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 06:41:17.986  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 06:41:17.986  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 06:41:17.986  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 06:41:17.987  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:41:17.988  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 06:41:17.988  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 06:41:17.988  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 06:41:17.988  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:17.989  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:41:17.989  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:41:17.990  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:41:17.990  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 06:41:17.991  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:17.991  5947  5966 D BtGatt.ScanManager: Starting BLE batch scan
09-16 06:41:17.991  5947  5966 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 06:41:18.003  5947  5963 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 06:41:18.003  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:18.010  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 06:41:18.010  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:18.017  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 06:41:18.018  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:18.018  5947  5966 D BtGatt.ScanManager: stopping BLe Batch
,09-16 06:41:18.025  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 06:41:18.025  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:18.025  5947  5966 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 06:41:18.032  5947  5963 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 06:41:18.032  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:18.491  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 06:41:18.491  5356  5356 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:41:18.492  5356  5356 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 06:41:20.990  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:41:20.990  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:41:20.991  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:41:20.991  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:20.991  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:41:20.991  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:20.991  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 06:41:20.992  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef6a838 removed from the list
09-16 06:41:20.992  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:20.992  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@996e011 removed from the list
09-16 06:41:20.992  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
,09-16 06:41:20.992  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:20.994  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:20.994  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:20.998  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:20.998  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:41:20.998  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:41:20.998  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@996e011 not in the list
,09-16 06:41:20.998  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:41:20.999  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:21.001  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:41:21.001  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:21.001  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-16 06:41:21.002  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@996e011 not in the list
09-16 06:41:21.002  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:21.002  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 06:41:21.002  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:21.002  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef6a838 not in the list
09-16 06:41:21.004  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 06:41:21.004  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53c302 added. We now have 3 listener(s)
09-16 06:41:21.008  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 06:41:21.008  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:41:21.009  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:41:21.009  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:41:21.009  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0d413 added. We now have 4 listener(s)
09-16 06:41:21.009  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:41:21.010  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 06:41:21.013  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:21.018  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:21.021  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:21.021  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:41:21.022  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-16 06:41:21.023  5356  5402 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-16 06:41:21.023  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-16 06:41:21.023  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 06:41:21.023  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-16 06:41:21.023  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-16 06:41:21.023  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:41:21.024  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 06:41:21.025  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-16 06:41:21.025  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 06:41:21.025  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 06:41:21.025  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-16 06:41:21.025  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:41:21.025  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:41:21.025  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 06:41:21.027  5356  6123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 06:41:21.029  5356  6123 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-16 06:41:21.025  5976  5976 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33135]" dev="sockfs" ino=33135 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 06:41:21.025  5976  5976 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33135]" dev="sockfs" ino=33135 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 06:41:21.030  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 06:41:21.030  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 06:41:21.032  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:41:21.032  5356  5356 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 06:41:21.035  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 06:41:21.036  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 06:41:21.036  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 06:41:21.038  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-16 06:41:21.039  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 06:41:21.039  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-16 06:41:21.040  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 06:41:21.040  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-16 06:41:21.040  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-16 06:41:21.041  5356  5402 D BluetoothAdapter: STATE_ON
,09-16 06:41:21.046  5947  5986 D BtGatt.GattService: registerClient() - UUID=18f96eec-6ba6-478b-8b5e-1700e2fbb0fc
,09-16 06:41:21.046  5947  5963 D BtGatt.GattService: onClientRegistered() - UUID=18f96eec-6ba6-478b-8b5e-1700e2fbb0fc, clientIf=5
09-16 06:41:21.047  5356  5493 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-16 06:41:21.048  5947  5965 D BtGatt.AdvertiseManager: message : 0
,09-16 06:41:21.050  5947  5965 D BtGatt.AdvertiseManager: starting multi advertising
,09-16 06:41:21.061  5947  5963 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-16 06:41:21.068  5947  5963 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-16 06:41:21.069  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-16 06:41:21.069  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 06:41:21.071  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 06:41:21.072  5356  5356 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-16 06:41:21.072  5356  5356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-16 06:41:21.072  5356  5356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-16 06:41:21.072  5356  5356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-16 06:41:21.072  5356  5356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-16 06:41:21.073  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-16 06:41:21.077  5356  5356 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-16 06:41:21.077  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-16 06:41:21.077  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 06:41:21.077  5356  5402 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 06:41:21.577  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-16 06:41:24.079  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:41:24.079  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-16 06:41:24.079  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 06:41:24.080  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-16 06:41:24.080  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 06:41:24.080  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 06:41:24.080  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 06:41:24.080  5356  6123 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-16 06:41:24.081  5356  5402 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 06:41:24.081  5356  6123 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 06:41:24.081  5356  6123 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 06:41:24.081  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:41:24.081  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:41:24.081  5356  5356 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 06:41:24.081  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-16 06:41:24.081  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 06:41:24.082  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 06:41:24.085  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:41:24.085  5356  5402 D BluetoothLeScanner: could not find callback wrapper
09-16 06:41:24.085  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 06:41:24.086  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-16 06:41:24.088  5947  5965 D BtGatt.AdvertiseManager: message : 1
,09-16 06:41:24.089  5947  5965 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-16 06:41:24.101  5947  5963 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-16 06:41:24.101  5947  5963 D BtGatt.GattService: Client app is not null!
,09-16 06:41:24.102  5947  5958 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 06:41:24.103  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-16 06:41:24.103  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-16 06:41:24.103  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-16 06:41:24.104  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-16 06:41:24.104  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-16 06:41:24.106  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 06:41:24.106  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-16 06:41:24.106  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 06:41:24.107  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:24.109  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 06:41:24.109  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:24.109  5356  5356 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-16 06:41:24.109  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:24.110  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:41:24.110  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 06:41:24.110  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:41:24.110  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 06:41:24.110  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53c302 removed from the list
09-16 06:41:24.110  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:24.111  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0d413 removed from the list
09-16 06:41:24.111  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:41:24.111  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:24.112  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:24.112  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:24.114  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:24.114  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:41:24.114  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:24.115  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0d413 not in the list
09-16 06:41:24.115  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:24.115  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:24.117  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:41:24.117  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:24.117  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:24.117  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da0d413 not in the list
09-16 06:41:24.117  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:24.117  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:24.118  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:24.118  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53c302 not in the list
09-16 06:41:24.119  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 06:41:24.119  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@995777c added. We now have 3 listener(s)
,09-16 06:41:24.121  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 06:41:24.121  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:41:24.121  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:41:24.122  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:41:24.122  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f3d805 added. We now have 4 listener(s)
09-16 06:41:24.122  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:41:24.122  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 06:41:24.125  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:24.131  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:24.134  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:24.134  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:41:24.134  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:41:24.134  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 06:41:24.134  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 06:41:24.134  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 06:41:24.135  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 06:41:24.138  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:24.141  5356  5402 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 06:41:24.142  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 06:41:24.142  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:41:24.146  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 06:41:24.146  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 06:41:24.146  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 06:41:24.151  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 06:41:24.151  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 06:41:24.151  5356  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 06:41:24.152  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:41:24.154  5947  5957 D BtGatt.GattService: registerClient() - UUID=669d5178-7bbb-459b-a953-db53b5034132
09-16 06:41:24.154  5947  5963 D BtGatt.GattService: onClientRegistered() - UUID=669d5178-7bbb-459b-a953-db53b5034132, clientIf=5
,09-16 06:41:24.155  5356  5366 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 06:41:24.155  5947  5958 D BtGatt.GattService: start scan with filters
,09-16 06:41:24.159  5947  5966 D BtGatt.ScanManager: handling starting scan
,09-16 06:41:24.159  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 06:41:24.159  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 06:41:24.159  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 06:41:24.159  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 06:41:24.163  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 06:41:24.163  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 06:41:24.163  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 06:41:24.164  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 06:41:24.166  5947  5963 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 06:41:24.166  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:24.166  5947  5966 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 06:41:24.171  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 06:41:24.172  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:24.172  5947  5966 D BtGatt.ScanManager: Starting BLE batch scan
,09-16 06:41:24.172  5947  5966 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 06:41:24.182  5947  5963 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 06:41:24.183  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:24.188  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 06:41:24.189  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:24.611  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 06:41:24.664  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-16 06:41:24.665  5356  5356 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:41:24.665  5356  5356 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-16 06:41:26.466   927  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:41:26.612   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 06:41:27.174  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 06:41:27.175  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 06:41:27.175  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 06:41:27.175  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.175  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-16 06:41:27.175  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 06:41:27.176  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 06:41:27.176  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 06:41:27.176  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 06:41:27.176  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 06:41:27.176  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 06:41:27.179  5356  5402 D BluetoothAdapter: STATE_ON
09-16 06:41:27.180  5947  5976 D BtGatt.GattService: stopScan() - queue size =1
09-16 06:41:27.183  5947  5957 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 06:41:27.185  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 06:41:27.185  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 06:41:27.186  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 06:41:27.186  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 06:41:27.186  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 06:41:27.188  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:41:27.189  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 06:41:27.189  5356  5402 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 06:41:27.189  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 06:41:27.191  5947  5947 D BtGatt.ScanManager: awakened up at time 439736
09-16 06:41:27.192  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:27.195  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-16 06:41:27.196  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-16 06:41:27.196  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.196  5356  5356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 06:41:27.196  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:27.196  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 06:41:27.196  5356  5356 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 06:41:27.196  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@995777c removed from the list
09-16 06:41:27.196  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:27.196  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f3d805 removed from the list
09-16 06:41:27.196  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:41:27.197  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:27.198  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.198  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:27.200  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:27.200  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:41:27.200  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:27.200  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f3d805 not in the list
09-16 06:41:27.201  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.201  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:27.202  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 06:41:27.203  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:27.203  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:27.203  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f3d805 not in the list
09-16 06:41:27.203  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:27.203  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.203  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:27.203  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@995777c not in the list
09-16 06:41:27.204  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 06:41:27.204  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab7826 added. We now have 3 listener(s)
,09-16 06:41:27.207  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 06:41:27.207  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 06:41:27.207  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 06:41:27.208  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 06:41:27.208  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501ec67 added. We now have 4 listener(s)
,09-16 06:41:27.208  5356  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 06:41:27.209  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 06:41:27.213  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:27.218  5356  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:27.220  5356  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:27.221  5356  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 06:41:27.221  5356  5402 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 06:41:27.221  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 06:41:27.221  5356  5402 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 06:41:27.221  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:27.221  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.221  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 06:41:27.221  5356  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 06:41:27.221  5356  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab7826 removed from the list
09-16 06:41:27.222  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:27.222  5356  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501ec67 removed from the list
,09-16 06:41:27.224  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 06:41:27.224  5356  5402 D io.jxcore.node.ConnectivityMonitor: stop
09-16 06:41:27.224  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:27.225  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.225  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:27.227  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 06:41:27.227  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:41:27.227  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:27.227  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501ec67 not in the list
09-16 06:41:27.227  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.227  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 06:41:27.228  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 06:41:27.230  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 06:41:27.230  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 06:41:27.230  5356  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 06:41:27.230  5356  5402 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@501ec67 not in the list
,09-16 06:41:27.230  5356  5402 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 06:41:27.230  5356  5402 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 06:41:27.230  5356  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 06:41:27.230  5356  5402 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab7826 not in the list
09-16 06:41:27.231  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-16 06:41:27.231  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 06:41:27.232  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 06:41:27.232  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 06:41:27.232  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 06:41:27.232  5356  5402 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 06:41:27.277  5947  5963 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 06:41:27.277  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 06:41:27.278  5947  5966 D BtGatt.ScanManager: stopping BLe Batch
,09-16 06:41:27.283  5947  5963 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 06:41:27.283  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:27.283  5947  5966 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 06:41:27.293  5947  5963 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-16 06:41:27.293  5947  5963 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 06:41:27.293  5947  5963 D BtGatt.GattService: current time is 439838264955
09-16 06:41:27.294  5947  5963 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -86, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -79, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-16 06:41:27.295  5947  5963 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-16 06:41:27.296  5947  5963 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-16 06:41:27.296  5947  5963 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-16 06:41:27.297  5947  5963 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-16 06:41:27.697  5356  5356 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 06:41:29.244  5356  6124 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: My test thread name)
,09-16 06:41:29.638   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-16 06:41:31.242  5356  5402 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 183
09-16 06:41:31.243  5356  5402 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 183, name: My test thread name)
,09-16 06:41:31.249  5356  6125 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name)
,09-16 06:41:31.249  5356  6125 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name)
09-16 06:41:31.249  5356  6125 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-16 06:41:31.253  5356  5402 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-16 06:41:31.259  5356  6126 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,09-16 06:41:31.260  5356  6126 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
,09-16 06:41:31.260  5356  6126 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-16 06:41:31.267  5356  5402 I jxcore-log: Total number of executed tests:  82
09-16 06:41:31.267  5356  5402 I jxcore-log: 
,09-16 06:41:31.268  5356  5402 I jxcore-log: Number of passed tests:  82
09-16 06:41:31.268  5356  5402 I jxcore-log: 
09-16 06:41:31.268  5356  5402 I jxcore-log: Number of failed tests:  0
09-16 06:41:31.268  5356  5402 I jxcore-log: 
09-16 06:41:31.268  5356  5402 I jxcore-log: Number of ignored tests:  0
09-16 06:41:31.268  5356  5402 I jxcore-log: 
,09-16 06:41:31.269  5356  5402 I jxcore-log: Total duration:  101501
09-16 06:41:31.269  5356  5402 I jxcore-log: 
,09-16 06:41:31.274  5356  5402 I jxcore-log: Unit Test app is loaded
09-16 06:41:31.274  5356  5402 I jxcore-log: 
,09-16 06:41:31.285  5356  6124 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-16 06:41:31.289  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.289  5356  5402 I jxcore-log: 
,09-16 06:41:31.296  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.296  5356  5402 I jxcore-log: 
,09-16 06:41:31.297  5356  5356 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-16 06:41:31.298  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.298  5356  5402 I jxcore-log: 
09-16 06:41:31.299  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.299  5356  5402 I jxcore-log: 
,09-16 06:41:31.302  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 06:41:31.302  5356  5402 I jxcore-log: 
,09-16 06:41:31.304  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 06:41:31.304  5356  5402 I jxcore-log: 
,09-16 06:41:31.307  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.307  5356  5402 I jxcore-log: 
,09-16 06:41:31.310  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.310  5356  5402 I jxcore-log: 
,09-16 06:41:31.311  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 06:41:31.311  5356  5402 I jxcore-log: 
09-16 06:41:31.311  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 06:41:31.311  5356  5402 I jxcore-log: 
09-16 06:41:31.312  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 06:41:31.312  5356  5402 I jxcore-log: 
,09-16 06:41:31.313  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.313  5356  5402 I jxcore-log: 
,09-16 06:41:31.314  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.314  5356  5402 I jxcore-log: 
,09-16 06:41:31.316  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.316  5356  5402 I jxcore-log: 
,09-16 06:41:31.317  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.317  5356  5402 I jxcore-log: 
09-16 06:41:31.318  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.318  5356  5402 I jxcore-log: 
,09-16 06:41:31.319  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.319  5356  5402 I jxcore-log: 
,09-16 06:41:31.320  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.320  5356  5402 I jxcore-log: 
09-16 06:41:31.321  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.321  5356  5402 I jxcore-log: 
09-16 06:41:31.322  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.322  5356  5402 I jxcore-log: 
,09-16 06:41:31.323  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.323  5356  5402 I jxcore-log: 
,09-16 06:41:31.324  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.324  5356  5402 I jxcore-log: 
,09-16 06:41:31.325  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.325  5356  5402 I jxcore-log: 
,09-16 06:41:31.326  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.326  5356  5402 I jxcore-log: 
09-16 06:41:31.327  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.327  5356  5402 I jxcore-log: 
09-16 06:41:31.328  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.328  5356  5402 I jxcore-log: 
09-16 06:41:31.329  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.329  5356  5402 I jxcore-log: 
09-16 06:41:31.329  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.329  5356  5402 I jxcore-log: 
,09-16 06:41:31.330  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.330  5356  5402 I jxcore-log: 
,09-16 06:41:31.331  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.331  5356  5402 I jxcore-log: 
,09-16 06:41:31.332  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.332  5356  5402 I jxcore-log: 
,09-16 06:41:31.333  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.333  5356  5402 I jxcore-log: 
09-16 06:41:31.334  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.334  5356  5402 I jxcore-log: 
09-16 06:41:31.334  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.334  5356  5402 I jxcore-log: 
09-16 06:41:31.335  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.335  5356  5402 I jxcore-log: 
09-16 06:41:31.335  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.335  5356  5402 I jxcore-log: 
,09-16 06:41:31.336  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.336  5356  5402 I jxcore-log: 
,09-16 06:41:31.337  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.337  5356  5402 I jxcore-log: 
09-16 06:41:31.338  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.338  5356  5402 I jxcore-log: 
09-16 06:41:31.339  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.339  5356  5402 I jxcore-log: 
,09-16 06:41:31.340  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 06:41:31.340  5356  5402 I jxcore-log: 
,09-16 06:41:31.341  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.341  5356  5402 I jxcore-log: 
,09-16 06:41:31.342  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 06:41:31.342  5356  5402 I jxcore-log: 
,09-16 06:41:31.343  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.343  5356  5402 I jxcore-log: 
,09-16 06:41:31.343  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.343  5356  5402 I jxcore-log: 
09-16 06:41:31.344  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.344  5356  5402 I jxcore-log: 
09-16 06:41:31.345  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.345  5356  5402 I jxcore-log: 
09-16 06:41:31.346  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.346  5356  5402 I jxcore-log: 
,09-16 06:41:31.346  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 06:41:31.346  5356  5402 I jxcore-log: 
,09-16 06:41:31.347  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.347  5356  5402 I jxcore-log: 
,09-16 06:41:31.348  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-16 06:41:31.348  5356  5402 I jxcore-log: 
,09-16 06:41:31.349  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.349  5356  5402 I jxcore-log: 
,09-16 06:41:31.350  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 06:41:31.350  5356  5402 I jxcore-log: 
09-16 06:41:31.350  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-16 06:41:31.350  5356  5402 I jxcore-log: 
,09-16 06:41:31.351  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:31.351  5356  5402 I jxcore-log: 
,09-16 06:41:31.352  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 06:41:31.352  5356  5402 I jxcore-log: 
,09-16 06:41:31.358  5356  5402 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-16 06:41:31.358  5356  5402 I jxcore-log:   bluetooth: 'on',
09-16 06:41:31.358  5356  5402 I jxcore-log:   wifi: 'off',
09-16 06:41:31.358  5356  5402 I jxcore-log:   cellular: 'doNotCare' }
09-16 06:41:31.358  5356  5402 I jxcore-log: 
,09-16 06:41:31.358  5356  5402 I jxcore-log: Toggling WIFI ON
09-16 06:41:31.358  5356  5402 I jxcore-log: 
,09-16 06:41:31.360   927   938 D WifiService: setWifiEnabled: true pid=5356, uid=10077
,09-16 06:41:31.360   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 06:41:31.368  5356  5402 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-16 06:41:31.368  5356  5402 I jxcore-log:   bluetooth: 'on',
09-16 06:41:31.368  5356  5402 I jxcore-log:   wifi: 'on',
09-16 06:41:31.368  5356  5402 I jxcore-log:   cellular: 'doNotCare',
09-16 06:41:31.368  5356  5402 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-16 06:41:31.368  5356  5402 I jxcore-log: 
,09-16 06:41:31.368  5356  5402 I jxcore-log: My device name is: Huawei-Nexus 6P
09-16 06:41:31.368  5356  5402 I jxcore-log: 
,09-16 06:41:31.369  6002  6002 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 06:41:31.369  5356  5402 I jxcore-log: WARN testUtils: myNameCallback not set!
09-16 06:41:31.369  5356  5402 I jxcore-log: 
09-16 06:41:31.369  5356  5402 I jxcore-log: Running for WIFI network type
09-16 06:41:31.369  5356  5402 I jxcore-log: 
,09-16 06:41:31.371   927  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 06:41:31.371   927  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-16 06:41:31.371   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 06:41:31.371   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:41:31.388  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,09-16 06:41:31.390   927  6006 D DhcpClient: Clearing IP address
09-16 06:41:31.390   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-16 06:41:31.393   507   922 D CommandListener: Setting iface cfg
,09-16 06:41:31.394   927  6007 D DhcpClient: Receive thread stopped
,09-16 06:41:31.400  3652  6049 V NativeCrypto: Read error: ssl=0x7f66a39000: I/O error during system call, Connection timed out
,09-16 06:41:31.402  3652  6049 V NativeCrypto: SSL shutdown failed: ssl=0x7f66a39000: I/O error during system call, Broken pipe
,09-16 06:41:31.404   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 06:41:31.404   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
09-16 06:41:31.407   533   533 E Parcel  : Reading a NULL string not supported here.
,09-16 06:41:31.407   927  2981 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-16 06:41:31.412   927  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-16 06:41:31.412   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 06:41:31.415   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-16 06:41:31.415   927  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
09-16 06:41:31.417  3501  3698 W QCNEJ   : |CORE| network lost: 102
09-16 06:41:31.418  3501  3698 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 06:41:31.419   927  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 06:41:31.419   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
09-16 06:41:31.419   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-16 06:41:31.429   927  2981 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:41:31.438   927  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-16 06:41:31.439  6002  6002 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
09-16 06:41:31.444   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:41:31.463   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:41:31.464   507   922 D TetherController: Setting IP forward enable = 0
,09-16 06:41:31.464   927  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-16 06:41:31.465   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:41:31.467   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:41:31.471  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:41:31.474  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 06:41:31.478  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 06:41:31.482  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 06:41:31.486  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 06:41:31.486  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 06:41:31.486  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 06:41:31.486  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:41:31.486  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 06:41:31.486  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:41:31.486  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 06:41:31.487  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-16 06:41:31.487  4938  4938 D QcrilMsgTunnelSocket: [1010] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 06:41:31.489  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 06:41:31.489  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:41:31.489  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:41:31.490  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:41:31.490  4938  4938 D QcrilMsgTunnelSocket: [1011] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 06:41:31.492  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000f203000000000000ffffffff]
,09-16 06:41:31.492  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:41:31.492  4938  4952 D QcrilMsgTunnelSocket: [1010] < OEM_HOOK_RAW [null]
09-16 06:41:31.492  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:41:31.493  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 06:41:31.494  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000f303000000000000ffffffff]
09-16 06:41:31.494  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-16 06:41:31.494  4938  4952 D QcrilMsgTunnelSocket: [1011] < OEM_HOOK_RAW [null]
09-16 06:41:31.495  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:41:31.495  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-16 06:41:31.500  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 06:41:31.506  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 06:41:31.507   507   922 E Netd    : netlink response contains error (No such file or directory)
09-16 06:41:31.507  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 06:41:31.508   507   922 D TetherController: Setting IP forward enable = 0
,09-16 06:41:31.509   927  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-16 06:41:31.510  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-16 06:41:31.513  5472  5472 D SprintDMHelper: simOperator: 
09-16 06:41:31.513  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 06:41:31.505  3889  5455 I iu.UploadsManager: num queued entries: 0
,09-16 06:41:31.525  3889  5455 I iu.UploadsManager: num updated entries: 0
,09-16 06:41:31.527  4288  6148 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 06:41:31.534  3889  5455 I iu.SyncManager: NEXT; no task
,09-16 06:41:31.825   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:41:31.825   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:41:31.847  6002  6002 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-16 06:41:31.881  6002  6002 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-16 06:41:31.882  6002  6002 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-16 06:41:31.896   927  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-16 06:41:31.896   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:41:31.896   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-16 06:41:31.911   927  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-16 06:41:31.923   507   922 D CommandListener: Setting iface cfg
,09-16 06:41:31.927   927  2981 D WifiStateMachine: Start Dhcp Watchdog 4
,09-16 06:41:31.937   927  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 103] to 60
,09-16 06:41:31.937   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-16 06:41:31.942   927  6152 D DhcpClient: Receive thread started
,09-16 06:41:32.022   927  2981 E native  : do suspend false
,09-16 06:41:32.038   927  6006 D DhcpClient: Broadcasting DHCPDISCOVER
,09-16 06:41:32.056   927  6152 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172774, domain null
,09-16 06:41:32.057   927  6006 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172774 seconds
,09-16 06:41:32.059   927  6006 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-16 06:41:32.074   927  6152 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-16 06:41:32.075   927  6006 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-16 06:41:32.078   507   922 D CommandListener: Setting iface cfg
09-16 06:41:32.083   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-16 06:41:32.087   927  6006 D DhcpClient: Scheduling renewal in 86399s
,09-16 06:41:32.098   927  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-16 06:41:32.100   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
09-16 06:41:32.100   927  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,09-16 06:41:32.101   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-16 06:41:32.103   927  2983 D ConnectivityService: Adding iface wlan0 to network 103
,09-16 06:41:32.110   927  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-16 06:41:32.162   927  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-16 06:41:32.163   927  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,09-16 06:41:32.165   927  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
09-16 06:41:32.169   927  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,09-16 06:41:32.171   927  2983 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,09-16 06:41:32.181   927  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:41:32.185   927  2983 D ConnectivityService: scheduleUnvalidatedPrompt 103
,09-16 06:41:32.186   927  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
09-16 06:41:32.186   927  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
09-16 06:41:32.186   927  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-16 06:41:32.186   927  2983 D ConnectivityService:    accepting network in place of null
,09-16 06:41:32.186   927  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 06:41:32.187   927  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-16 06:41:32.200   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=444745, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:41:32.209   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:41:32.229   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 06:41:32.232   927  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,09-16 06:41:32.232  3501  3698 W QCNEJ   : |CORE| network available: 103
09-16 06:41:32.232   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:41:32.233   927  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
,09-16 06:41:32.236   927   944 D Tethering: MasterInitialState.processMessage what=3
09-16 06:41:32.237  3501  3698 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-16 06:41:32.239  3501  3698 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-16 06:41:32.239  3501  3698 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:32.241  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 06:41:32.244  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 06:41:32.248  5356  5356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 06:41:32.251  5356  5356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 06:41:32.254  4909  4925 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 06:41:32.254  4909  4925 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-16 06:41:32.254  4909  4925 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-16 06:41:32.254  4909  4925 E SarControlService: no key has been found,reset the power
09-16 06:41:32.254  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 06:41:32.254  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 06:41:32.255  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 06:41:32.255  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:41:32.255  4938  4938 D QcrilMsgTunnelSocket: [1012] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 06:41:32.256  4909  4950 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 06:41:32.257  4909  4950 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 06:41:32.257  4909  4950 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-16 06:41:32.257  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 06:41:32.257  4938  4938 D QcrilMsgTunnelSocket: [1013] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 06:41:32.258  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000f403000000000000ffffffff]
09-16 06:41:32.258  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-16 06:41:32.258  4938  4952 D QcrilMsgTunnelSocket: [1012] < OEM_HOOK_RAW [null]
09-16 06:41:32.259  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-16 06:41:32.259  4909  4920 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-16 06:41:32.263  4938  4952 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c21b213 HexData = [00000000f503000000000000ffffffff]
,09-16 06:41:32.263  4938  4952 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 06:41:32.264  4938  4952 D QcrilMsgTunnelSocket: [1013] < OEM_HOOK_RAW [null]
09-16 06:41:32.264  4938  4938 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 06:41:32.265  4909  4919 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 06:41:32.269  3889  3889 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-16 06:41:32.277  3889  5455 I iu.UploadsManager: num queued entries: 0
,09-16 06:41:32.278  3889  5455 I iu.UploadsManager: num updated entries: 0
09-16 06:41:32.278  3889  5455 I iu.SyncManager: NEXT; no task
,09-16 06:41:32.280  3889  3889 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 06:41:32.281  3889  3889 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 06:41:32.284  5472  5472 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 06:41:32.287  5472  5472 D SprintDMHelper: simOperator: 
,09-16 06:41:32.287  5472  5472 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 06:41:32.396  4288  6164 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-16 06:41:32.550   927  5508 D ConnectivityService: reportNetworkConnectivity(103, true) by 10012
,09-16 06:41:32.562   927  3595 D ConnectivityService: reportNetworkConnectivity(103, true) by 10012
,09-16 06:41:32.565   927  3605 D ConnectivityService: reportNetworkConnectivity(103, true) by 10012
,09-16 06:41:32.921   927  6150 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-16 06:41:32.974   927  6150 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 10:41:32 GMT], X-Android-Received-Millis=[1474022492973], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474022492949]}
,09-16 06:41:32.975   927  6150 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Forcing reevaluation for UID 10012
09-16 06:41:32.975   927  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 06:41:32.976   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
09-16 06:41:32.976   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
09-16 06:41:32.977   927  6150 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-16 06:41:32.979   927  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-16 06:41:33.005   927  6150 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 16 Sep 2016 10:41:32 GMT], X-Android-Received-Millis=[1474022493004], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474022492982]}
,09-16 06:41:33.006   927  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-16 06:41:33.006   927  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
,09-16 06:41:33.060  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-16 06:41:33.060  5356  5402 I jxcore-log: 
,09-16 06:41:33.233   927  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,09-16 06:41:33.369  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-16 06:41:33.369  5356  5402 I jxcore-log: 
,09-16 06:41:33.395  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-16 06:41:33.395  5356  5402 I jxcore-log: 
,09-16 06:41:34.547  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-16 06:41:34.547  5356  5402 I jxcore-log: 
,09-16 06:41:34.550  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-16 06:41:34.550  5356  5402 I jxcore-log: 
,09-16 06:41:34.554  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-16 06:41:34.554  5356  5402 I jxcore-log: 
,09-16 06:41:34.600  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-16 06:41:34.600  5356  5402 I jxcore-log: 
,09-16 06:41:34.612  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-16 06:41:34.612  5356  5402 I jxcore-log: 
,09-16 06:41:34.615  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-16 06:41:34.615  5356  5402 I jxcore-log: 
,09-16 06:41:34.957   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:41:35.262  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-16 06:41:35.262  5356  5402 I jxcore-log: 
,09-16 06:41:35.492  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-16 06:41:35.492  5356  5402 I jxcore-log: 
,09-16 06:41:35.499  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-16 06:41:35.499  5356  5402 I jxcore-log: 
,09-16 06:41:35.505  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-16 06:41:35.505  5356  5402 I jxcore-log: 
,09-16 06:41:35.516  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-16 06:41:35.516  5356  5402 I jxcore-log: 
,09-16 06:41:35.542  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-16 06:41:35.542  5356  5402 I jxcore-log: 
,09-16 06:41:35.575  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-16 06:41:35.575  5356  5402 I jxcore-log: 
,09-16 06:41:35.580  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-16 06:41:35.580  5356  5402 I jxcore-log: 
,09-16 06:41:35.586  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-16 06:41:35.586  5356  5402 I jxcore-log: 
,09-16 06:41:35.599  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-16 06:41:35.599  5356  5402 I jxcore-log: 
,09-16 06:41:35.602  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-16 06:41:35.602  5356  5402 I jxcore-log: 
,09-16 06:41:35.606  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-16 06:41:35.606  5356  5402 I jxcore-log: 
,09-16 06:41:35.617  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-16 06:41:35.617  5356  5402 I jxcore-log: 
,09-16 06:41:35.635  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-16 06:41:35.635  5356  5402 I jxcore-log: 
,09-16 06:41:35.643  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-16 06:41:35.643  5356  5402 I jxcore-log: 
,09-16 06:41:35.653  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-16 06:41:35.653  5356  5402 I jxcore-log: 
,09-16 06:41:35.661  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-16 06:41:35.661  5356  5402 I jxcore-log: 
,09-16 06:41:35.672  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-16 06:41:35.672  5356  5402 I jxcore-log: 
,09-16 06:41:35.679  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-16 06:41:35.679  5356  5402 I jxcore-log: 
,09-16 06:41:35.683  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-16 06:41:35.683  5356  5402 I jxcore-log: 
,09-16 06:41:35.701  5356  5402 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-16 06:41:35.701  5356  5402 I jxcore-log: 
,09-16 06:41:35.709  5356  5402 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-16 06:41:35.710  5356  5402 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-16 06:41:35.710  5356  5402 I jxcore-log: 
,09-16 06:41:35.712  5356  5402 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-16 06:41:35.712  5356  5402 I jxcore-log: 
,09-16 06:41:35.712  5356  5402 I jxcore-log: ThaliTape :: Started ThaliTape
09-16 06:41:35.712  5356  5402 I jxcore-log: 
,09-16 06:41:35.716  5356  5402 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-16 06:41:35.716  5356  5402 I jxcore-log: 
,09-16 06:41:35.748  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 06:41:35.748  5356  5402 I jxcore-log: 
,09-16 06:41:35.749  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 06:41:35.749  5356  5402 I jxcore-log: 
,09-16 06:41:35.749  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:35.749  5356  5402 I jxcore-log: 
,09-16 06:41:35.749  5356  5402 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 06:41:35.749  5356  5402 I jxcore-log: 
,09-16 06:41:35.802  5356  5402 I jxcore-log: ThaliTape :: Connected to the test server
09-16 06:41:35.802  5356  5402 I jxcore-log: 
,09-16 06:41:36.123  5356  5402 I jxcore-log: TAP version 13
09-16 06:41:36.123  5356  5402 I jxcore-log: 
,09-16 06:41:36.127  5356  5402 I jxcore-log: # setup
09-16 06:41:36.127  5356  5402 I jxcore-log: 
,09-16 06:41:36.995  5356  5402 I jxcore-log: # 1. calling createNativeListener directly rejects
09-16 06:41:36.995  5356  5402 I jxcore-log: 
,09-16 06:41:37.622  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:37.622  5356  5402 I jxcore-log: 
,09-16 06:41:37.628  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 46334
09-16 06:41:37.628  5356  5402 I jxcore-log: 
,09-16 06:41:37.641  5356  5402 I jxcore-log: ok 1 Should throw
09-16 06:41:37.641  5356  5402 I jxcore-log: 
,09-16 06:41:37.646  5356  5402 I jxcore-log: # teardown
09-16 06:41:37.646  5356  5402 I jxcore-log: 
,09-16 06:41:38.548  5356  5402 I jxcore-log: # setup
09-16 06:41:38.548  5356  5402 I jxcore-log: 
,09-16 06:41:38.745  5356  5402 I jxcore-log: # 2. emits incomingConnectionState
09-16 06:41:38.745  5356  5402 I jxcore-log: 
,09-16 06:41:39.676  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:39.676  5356  5402 I jxcore-log: 
,09-16 06:41:39.682  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 38562
09-16 06:41:39.682  5356  5402 I jxcore-log: 
,09-16 06:41:39.696  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:39.696  5356  5402 I jxcore-log: 
,09-16 06:41:39.700  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:39.700  5356  5402 I jxcore-log: 
,09-16 06:41:39.711  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:39.711  5356  5402 I jxcore-log: 
,09-16 06:41:39.717  5356  5402 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-16 06:41:39.717  5356  5402 I jxcore-log: 
,09-16 06:41:39.740  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:39.740  5356  5402 I jxcore-log: 
,09-16 06:41:39.741  5356  5402 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-16 06:41:39.741  5356  5402 I jxcore-log: 
,09-16 06:41:39.748  5356  5402 I jxcore-log: # teardown
09-16 06:41:39.748  5356  5402 I jxcore-log: 
,09-16 06:41:40.080  5356  5402 I jxcore-log: # setup
09-16 06:41:40.080  5356  5402 I jxcore-log: 
,09-16 06:41:40.191   927  2983 D ConnectivityService: handlePromptUnvalidated 103
,09-16 06:41:40.987  5356  5402 I jxcore-log: # 3. emits routerPortConnectionFailed
09-16 06:41:40.987  5356  5402 I jxcore-log: 
,09-16 06:41:41.431  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:41.431  5356  5402 I jxcore-log: 
,09-16 06:41:41.436  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 42613
09-16 06:41:41.436  5356  5402 I jxcore-log: 
,09-16 06:41:41.445  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:41.445  5356  5402 I jxcore-log: 
,09-16 06:41:41.447  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:41.447  5356  5402 I jxcore-log: 
,09-16 06:41:41.449  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:41.449  5356  5402 I jxcore-log: 
,09-16 06:41:41.481  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:41.481  5356  5402 I jxcore-log: 
,09-16 06:41:41.484  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:41.484  5356  5402 I jxcore-log: 
,09-16 06:41:41.489  5356  5402 I jxcore-log: DEBUG createNativeListener: 
09-16 06:41:41.489  5356  5402 I jxcore-log: 
,09-16 06:41:41.490  5356  5402 I jxcore-log: ok 4 tried to connect to right port
09-16 06:41:41.490  5356  5402 I jxcore-log: 
09-16 06:41:41.491  5356  5402 I jxcore-log: ok 5 failed due to refused connection
09-16 06:41:41.491  5356  5402 I jxcore-log: 
09-16 06:41:41.491  5356  5402 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-16 06:41:41.491  5356  5402 I jxcore-log: 
09-16 06:41:41.493  5356  5402 I jxcore-log: # teardown
09-16 06:41:41.493  5356  5402 I jxcore-log: 
,09-16 06:41:41.495  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:41.495  5356  5402 I jxcore-log: 
,09-16 06:41:42.239  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:42.239  5356  5402 I jxcore-log: 
,09-16 06:41:42.248  5356  5402 I jxcore-log: # setup
09-16 06:41:42.248  5356  5402 I jxcore-log: 
09-16 06:41:42.250  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:42.250  5356  5402 I jxcore-log: 
,09-16 06:41:42.774  5356  5402 I jxcore-log: # 4. native server connections all up
09-16 06:41:42.774  5356  5402 I jxcore-log: 
,09-16 06:41:43.138  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:43.138  5356  5402 I jxcore-log: 
,09-16 06:41:43.147  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 44675
09-16 06:41:43.147  5356  5402 I jxcore-log: 
,09-16 06:41:43.164  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:43.164  5356  5402 I jxcore-log: 
,09-16 06:41:43.167  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:43.167  5356  5402 I jxcore-log: 
,09-16 06:41:43.171  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:43.171  5356  5402 I jxcore-log: 
,09-16 06:41:43.218  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:43.218  5356  5402 I jxcore-log: 
,09-16 06:41:43.223  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:43.223  5356  5402 I jxcore-log: 
,09-16 06:41:43.227  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:43.227  5356  5402 I jxcore-log: 
,09-16 06:41:43.230  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:43.230  5356  5402 I jxcore-log: 
,09-16 06:41:43.255  5356  5402 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-16 06:41:43.255  5356  5402 I jxcore-log: 
,09-16 06:41:43.256  5356  5402 I jxcore-log: ok 8 Send/recvd #1 should be same
09-16 06:41:43.256  5356  5402 I jxcore-log: 
,09-16 06:41:43.258  5356  5402 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-16 06:41:43.258  5356  5402 I jxcore-log: 
,09-16 06:41:43.259  5356  5402 I jxcore-log: ok 10 Send/recvd #2 should be same
09-16 06:41:43.259  5356  5402 I jxcore-log: 
,09-16 06:41:43.262  5356  5402 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-16 06:41:43.262  5356  5402 I jxcore-log: 
,09-16 06:41:43.269  5356  5402 I jxcore-log: # teardown
09-16 06:41:43.269  5356  5402 I jxcore-log: 
,09-16 06:41:43.866  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:43.866  5356  5402 I jxcore-log: 
,09-16 06:41:43.870  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:43.870  5356  5402 I jxcore-log: 
,09-16 06:41:43.875  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:43.875  5356  5402 I jxcore-log: 
,09-16 06:41:43.883  5356  5402 I jxcore-log: # setup
09-16 06:41:43.883  5356  5402 I jxcore-log: 
,09-16 06:41:43.885  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:43.885  5356  5402 I jxcore-log: 
,09-16 06:41:44.521  5356  5402 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-16 06:41:44.521  5356  5402 I jxcore-log: 
,09-16 06:41:45.144  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:45.144  5356  5402 I jxcore-log: 
,09-16 06:41:45.150  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 46236
09-16 06:41:45.150  5356  5402 I jxcore-log: 
,09-16 06:41:45.162  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:45.162  5356  5402 I jxcore-log: 
,09-16 06:41:45.165  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:45.165  5356  5402 I jxcore-log: 
,09-16 06:41:45.167  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:45.167  5356  5402 I jxcore-log: 
,09-16 06:41:45.187  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:45.187  5356  5402 I jxcore-log: 
,09-16 06:41:45.191  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:45.191  5356  5402 I jxcore-log: 
,09-16 06:41:45.207  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:45.207  5356  5402 I jxcore-log: 
,09-16 06:41:45.220  5356  5402 I jxcore-log: ok 12 socket shouldn't close until after stream
09-16 06:41:45.220  5356  5402 I jxcore-log: 
09-16 06:41:45.220  5356  5402 I jxcore-log: ok 13 incoming remains open
09-16 06:41:45.220  5356  5402 I jxcore-log: 
,09-16 06:41:45.223  5356  5402 I jxcore-log: # teardown
09-16 06:41:45.223  5356  5402 I jxcore-log: 
,09-16 06:41:45.671   927  2981 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,09-16 06:41:45.791  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:45.791  5356  5402 I jxcore-log: 
,09-16 06:41:45.799  5356  5402 I jxcore-log: # setup
09-16 06:41:45.799  5356  5402 I jxcore-log: 
,09-16 06:41:45.801  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:45.801  5356  5402 I jxcore-log: 
,09-16 06:41:46.458  5356  5402 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-16 06:41:46.458  5356  5402 I jxcore-log: 
,09-16 06:41:46.586  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:46.592  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:46.598  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:46.602  6002  6002 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-16 06:41:47.032  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:47.032  5356  5402 I jxcore-log: 
,09-16 06:41:47.038  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 38259
09-16 06:41:47.038  5356  5402 I jxcore-log: 
,09-16 06:41:47.050  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:47.050  5356  5402 I jxcore-log: 
,09-16 06:41:47.052  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:47.052  5356  5402 I jxcore-log: 
,09-16 06:41:47.055  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:47.055  5356  5402 I jxcore-log: 
,09-16 06:41:47.075  5356  5402 I jxcore-log: ok 14 we should not have gotten an error
09-16 06:41:47.075  5356  5402 I jxcore-log: 
,09-16 06:41:47.082  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:47.082  5356  5402 I jxcore-log: 
,09-16 06:41:47.088  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:47.088  5356  5402 I jxcore-log: 
,09-16 06:41:47.097  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:47.097  5356  5402 I jxcore-log: 
,09-16 06:41:47.099  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:47.099  5356  5402 I jxcore-log: 
,09-16 06:41:47.106  5356  5402 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-16 06:41:47.106  5356  5402 I jxcore-log: 
,09-16 06:41:47.107  5356  5402 I jxcore-log: ok 16 incoming is cleaned up
09-16 06:41:47.107  5356  5402 I jxcore-log: 
,09-16 06:41:47.109  5356  5402 I jxcore-log: # teardown
09-16 06:41:47.109  5356  5402 I jxcore-log: 
,09-16 06:41:47.763  5356  5402 I jxcore-log: # setup
09-16 06:41:47.763  5356  5402 I jxcore-log: 
,09-16 06:41:48.371  5356  5402 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-16 06:41:48.371  5356  5402 I jxcore-log: 
,09-16 06:41:48.874  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:48.874  5356  5402 I jxcore-log: 
,09-16 06:41:48.880  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 44748
09-16 06:41:48.880  5356  5402 I jxcore-log: 
,09-16 06:41:48.892  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:48.892  5356  5402 I jxcore-log: 
,09-16 06:41:48.894  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:48.894  5356  5402 I jxcore-log: 
,09-16 06:41:48.900  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:48.900  5356  5402 I jxcore-log: 
,09-16 06:41:48.920  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:48.920  5356  5402 I jxcore-log: 
,09-16 06:41:48.924  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:48.924  5356  5402 I jxcore-log: 
,09-16 06:41:48.940  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:48.940  5356  5402 I jxcore-log: 
,09-16 06:41:48.956  5356  5402 I jxcore-log: ok 17 stream was closed
09-16 06:41:48.956  5356  5402 I jxcore-log: 
,09-16 06:41:48.957  5356  5402 I jxcore-log: ok 18 incoming should survive
09-16 06:41:48.957  5356  5402 I jxcore-log: 
09-16 06:41:48.957  5356  5402 I jxcore-log: ok 19 mux should have no streams
09-16 06:41:48.957  5356  5402 I jxcore-log: 
,09-16 06:41:48.961  5356  5402 I jxcore-log: # teardown
09-16 06:41:48.961  5356  5402 I jxcore-log: 
,09-16 06:41:49.599  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:49.599  5356  5402 I jxcore-log: 
,09-16 06:41:49.612  5356  5402 I jxcore-log: # setup
09-16 06:41:49.612  5356  5402 I jxcore-log: 
,09-16 06:41:49.614  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:49.614  5356  5402 I jxcore-log: 
,09-16 06:41:51.136  5356  5402 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-16 06:41:51.136  5356  5402 I jxcore-log: 
,09-16 06:41:51.751  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:51.751  5356  5402 I jxcore-log: 
,09-16 06:41:51.756  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 41286
09-16 06:41:51.756  5356  5402 I jxcore-log: 
,09-16 06:41:51.766  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:51.766  5356  5402 I jxcore-log: 
,09-16 06:41:51.767  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:51.767  5356  5402 I jxcore-log: 
09-16 06:41:51.769  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:51.769  5356  5402 I jxcore-log: 
,09-16 06:41:51.778  5356  5402 I jxcore-log: ok 20 we should not have gotten an error
09-16 06:41:51.778  5356  5402 I jxcore-log: 
,09-16 06:41:51.786  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:51.786  5356  5402 I jxcore-log: 
,09-16 06:41:51.790  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:51.790  5356  5402 I jxcore-log: 
,09-16 06:41:51.799  5356  5402 I jxcore-log: ok 21 Buffers are identical
09-16 06:41:51.799  5356  5402 I jxcore-log: 
,09-16 06:41:51.801  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:51.801  5356  5402 I jxcore-log: 
,09-16 06:41:51.803  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:51.803  5356  5402 I jxcore-log: 
,09-16 06:41:51.806  5356  5402 I jxcore-log: ok 22 native server is nulled out
09-16 06:41:51.806  5356  5402 I jxcore-log: 
,09-16 06:41:51.806  5356  5402 I jxcore-log: ok 23 native server should be closed
09-16 06:41:51.806  5356  5402 I jxcore-log: 
09-16 06:41:51.806  5356  5402 I jxcore-log: ok 24 incoming has been removed
09-16 06:41:51.806  5356  5402 I jxcore-log: 
09-16 06:41:51.806  5356  5402 I jxcore-log: ok 25 Incoming should be done
09-16 06:41:51.806  5356  5402 I jxcore-log: 
09-16 06:41:51.807  5356  5402 I jxcore-log: ok 26 The mux object should be closed
09-16 06:41:51.807  5356  5402 I jxcore-log: 
09-16 06:41:51.807  5356  5402 I jxcore-log: ok 27 The mux stream should be closed
09-16 06:41:51.807  5356  5402 I jxcore-log: 
09-16 06:41:51.807  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:51.807  5356  5402 I jxcore-log: 
,09-16 06:41:51.819  5356  5402 I jxcore-log: # teardown
09-16 06:41:51.819  5356  5402 I jxcore-log: 
,09-16 06:41:51.826   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:52.166   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:41:52.331  5356  5402 I jxcore-log: # setup
09-16 06:41:52.331  5356  5402 I jxcore-log: 
,09-16 06:41:52.536  5356  5402 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-16 06:41:52.536  5356  5402 I jxcore-log: 
,09-16 06:41:52.612  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:52.612  5356  5402 I jxcore-log: 
,09-16 06:41:52.617  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 42688
09-16 06:41:52.617  5356  5402 I jxcore-log: 
,09-16 06:41:52.652  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.652  5356  5402 I jxcore-log: 
,09-16 06:41:52.654  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.654  5356  5402 I jxcore-log: 
09-16 06:41:52.655  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.655  5356  5402 I jxcore-log: 
,09-16 06:41:52.659  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.659  5356  5402 I jxcore-log: 
,09-16 06:41:52.660  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.660  5356  5402 I jxcore-log: 
09-16 06:41:52.661  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.661  5356  5402 I jxcore-log: 
,09-16 06:41:52.664  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.664  5356  5402 I jxcore-log: 
,09-16 06:41:52.665  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.665  5356  5402 I jxcore-log: 
,09-16 06:41:52.667  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.667  5356  5402 I jxcore-log: 
,09-16 06:41:52.670  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.670  5356  5402 I jxcore-log: 
,09-16 06:41:52.671  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.671  5356  5402 I jxcore-log: 
09-16 06:41:52.672  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.672  5356  5402 I jxcore-log: 
,09-16 06:41:52.675  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.675  5356  5402 I jxcore-log: 
,09-16 06:41:52.676  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.676  5356  5402 I jxcore-log: 
09-16 06:41:52.677  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.677  5356  5402 I jxcore-log: 
09-16 06:41:52.680  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.680  5356  5402 I jxcore-log: 
,09-16 06:41:52.680  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.680  5356  5402 I jxcore-log: 
,09-16 06:41:52.681  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.681  5356  5402 I jxcore-log: 
,09-16 06:41:52.688  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.688  5356  5402 I jxcore-log: 
,09-16 06:41:52.690  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.690  5356  5402 I jxcore-log: 
,09-16 06:41:52.691  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.691  5356  5402 I jxcore-log: 
,09-16 06:41:52.696  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.696  5356  5402 I jxcore-log: 
,09-16 06:41:52.697  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.697  5356  5402 I jxcore-log: 
,09-16 06:41:52.698  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.698  5356  5402 I jxcore-log: 
,09-16 06:41:52.700  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.700  5356  5402 I jxcore-log: 
,09-16 06:41:52.701  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.701  5356  5402 I jxcore-log: 
,09-16 06:41:52.702  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.702  5356  5402 I jxcore-log: 
,09-16 06:41:52.706  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:52.706  5356  5402 I jxcore-log: 
,09-16 06:41:52.706  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:52.706  5356  5402 I jxcore-log: 
,09-16 06:41:52.707  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:52.707  5356  5402 I jxcore-log: 
,09-16 06:41:52.775  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.775  5356  5402 I jxcore-log: 
,09-16 06:41:52.777  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.777  5356  5402 I jxcore-log: 
,09-16 06:41:52.779  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.779  5356  5402 I jxcore-log: 
,09-16 06:41:52.780  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.780  5356  5402 I jxcore-log: 
,09-16 06:41:52.781  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.781  5356  5402 I jxcore-log: 
,09-16 06:41:52.782  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.782  5356  5402 I jxcore-log: 
,09-16 06:41:52.783  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.783  5356  5402 I jxcore-log: 
,09-16 06:41:52.784  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.784  5356  5402 I jxcore-log: 
,09-16 06:41:52.786  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.786  5356  5402 I jxcore-log: 
,09-16 06:41:52.787  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.787  5356  5402 I jxcore-log: 
,09-16 06:41:52.787  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.787  5356  5402 I jxcore-log: 
,09-16 06:41:52.790  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.790  5356  5402 I jxcore-log: 
,09-16 06:41:52.791  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.791  5356  5402 I jxcore-log: 
,09-16 06:41:52.792  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.792  5356  5402 I jxcore-log: 
,09-16 06:41:52.793  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.793  5356  5402 I jxcore-log: 
,09-16 06:41:52.794  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.794  5356  5402 I jxcore-log: 
,09-16 06:41:52.795  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.795  5356  5402 I jxcore-log: 
,09-16 06:41:52.796  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.796  5356  5402 I jxcore-log: 
,09-16 06:41:52.797  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.797  5356  5402 I jxcore-log: 
,09-16 06:41:52.797  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.797  5356  5402 I jxcore-log: 
09-16 06:41:52.798  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.798  5356  5402 I jxcore-log: 
,09-16 06:41:52.799  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.799  5356  5402 I jxcore-log: 
,09-16 06:41:52.799  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.799  5356  5402 I jxcore-log: 
09-16 06:41:52.800  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.800  5356  5402 I jxcore-log: 
,09-16 06:41:52.801  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.801  5356  5402 I jxcore-log: 
,09-16 06:41:52.802  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.802  5356  5402 I jxcore-log: 
09-16 06:41:52.803  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.803  5356  5402 I jxcore-log: 
,09-16 06:41:52.803  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.803  5356  5402 I jxcore-log: 
09-16 06:41:52.804  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.804  5356  5402 I jxcore-log: 
,09-16 06:41:52.804  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.804  5356  5402 I jxcore-log: 
,09-16 06:41:52.805  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.805  5356  5402 I jxcore-log: 
09-16 06:41:52.806  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.806  5356  5402 I jxcore-log: 
,09-16 06:41:52.807  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.807  5356  5402 I jxcore-log: 
,09-16 06:41:52.807  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.807  5356  5402 I jxcore-log: 
09-16 06:41:52.808  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.808  5356  5402 I jxcore-log: 
,09-16 06:41:52.809  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.809  5356  5402 I jxcore-log: 
09-16 06:41:52.809  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.809  5356  5402 I jxcore-log: 
09-16 06:41:52.810  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.810  5356  5402 I jxcore-log: 
,09-16 06:41:52.815  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.815  5356  5402 I jxcore-log: 
,09-16 06:41:52.816  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.816  5356  5402 I jxcore-log: 
,09-16 06:41:52.818  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.818  5356  5402 I jxcore-log: 
,09-16 06:41:52.819  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.819  5356  5402 I jxcore-log: 
,09-16 06:41:52.820  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.820  5356  5402 I jxcore-log: 
09-16 06:41:52.820  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.820  5356  5402 I jxcore-log: 
,09-16 06:41:52.821  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.821  5356  5402 I jxcore-log: 
09-16 06:41:52.822  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.822  5356  5402 I jxcore-log: 
,09-16 06:41:52.822  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.822  5356  5402 I jxcore-log: 
,09-16 06:41:52.823  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.823  5356  5402 I jxcore-log: 
,09-16 06:41:52.824  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.824  5356  5402 I jxcore-log: 
09-16 06:41:52.825  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.825  5356  5402 I jxcore-log: 
,09-16 06:41:52.825  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.825  5356  5402 I jxcore-log: 
,09-16 06:41:52.826  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.826  5356  5402 I jxcore-log: 
09-16 06:41:52.826   535   535 I ServiceManager: Waiting for service AtCmdFwd...
09-16 06:41:52.826  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.826  5356  5402 I jxcore-log: 
,09-16 06:41:52.827  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.827  5356  5402 I jxcore-log: 
09-16 06:41:52.828  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.828  5356  5402 I jxcore-log: 
,09-16 06:41:52.828  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.828  5356  5402 I jxcore-log: 
09-16 06:41:52.829  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.829  5356  5402 I jxcore-log: 
,09-16 06:41:52.830  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.830  5356  5402 I jxcore-log: 
,09-16 06:41:52.830  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.830  5356  5402 I jxcore-log: 
,09-16 06:41:52.831  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.831  5356  5402 I jxcore-log: 
09-16 06:41:52.832  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.832  5356  5402 I jxcore-log: 
,09-16 06:41:52.832  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.832  5356  5402 I jxcore-log: 
09-16 06:41:52.833  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.833  5356  5402 I jxcore-log: 
09-16 06:41:52.834  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.834  5356  5402 I jxcore-log: 
,09-16 06:41:52.834  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.834  5356  5402 I jxcore-log: 
,09-16 06:41:52.835  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.835  5356  5402 I jxcore-log: 
09-16 06:41:52.836  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.836  5356  5402 I jxcore-log: 
09-16 06:41:52.837  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.837  5356  5402 I jxcore-log: 
,09-16 06:41:52.837  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.837  5356  5402 I jxcore-log: 
09-16 06:41:52.838  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.838  5356  5402 I jxcore-log: 
,09-16 06:41:52.838  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.838  5356  5402 I jxcore-log: 
09-16 06:41:52.839  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.839  5356  5402 I jxcore-log: 
,09-16 06:41:52.840  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.840  5356  5402 I jxcore-log: 
,09-16 06:41:52.841  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.841  5356  5402 I jxcore-log: 
09-16 06:41:52.841  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.841  5356  5402 I jxcore-log: 
09-16 06:41:52.842  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.842  5356  5402 I jxcore-log: 
,09-16 06:41:52.843  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.843  5356  5402 I jxcore-log: 
09-16 06:41:52.843  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.843  5356  5402 I jxcore-log: 
,09-16 06:41:52.844  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:52.844  5356  5402 I jxcore-log: 
09-16 06:41:52.844  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:52.844  5356  5402 I jxcore-log: 
,09-16 06:41:52.893  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.893  5356  5402 I jxcore-log: 
,09-16 06:41:52.894  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.894  5356  5402 I jxcore-log: 
,09-16 06:41:52.895  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.895  5356  5402 I jxcore-log: 
,09-16 06:41:52.896  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.896  5356  5402 I jxcore-log: 
,09-16 06:41:52.897  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.897  5356  5402 I jxcore-log: 
,09-16 06:41:52.898  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.898  5356  5402 I jxcore-log: 
09-16 06:41:52.899  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.899  5356  5402 I jxcore-log: 
,09-16 06:41:52.899  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.899  5356  5402 I jxcore-log: 
,09-16 06:41:52.900  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.900  5356  5402 I jxcore-log: 
,09-16 06:41:52.900  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.900  5356  5402 I jxcore-log: 
,09-16 06:41:52.901  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.901  5356  5402 I jxcore-log: 
09-16 06:41:52.903  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.903  5356  5402 I jxcore-log: 
09-16 06:41:52.904  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.904  5356  5402 I jxcore-log: 
09-16 06:41:52.904  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.904  5356  5402 I jxcore-log: 
,09-16 06:41:52.905  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.905  5356  5402 I jxcore-log: 
,09-16 06:41:52.909  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.909  5356  5402 I jxcore-log: 
,09-16 06:41:52.911  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.911  5356  5402 I jxcore-log: 
,09-16 06:41:52.912  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.912  5356  5402 I jxcore-log: 
,09-16 06:41:52.913  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.913  5356  5402 I jxcore-log: 
09-16 06:41:52.913  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.913  5356  5402 I jxcore-log: 
,09-16 06:41:52.914  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.914  5356  5402 I jxcore-log: 
09-16 06:41:52.914  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.914  5356  5402 I jxcore-log: 
09-16 06:41:52.915  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.915  5356  5402 I jxcore-log: 
,09-16 06:41:52.915  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.915  5356  5402 I jxcore-log: 
,09-16 06:41:52.916  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.916  5356  5402 I jxcore-log: 
09-16 06:41:52.917  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.917  5356  5402 I jxcore-log: 
,09-16 06:41:52.917  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.917  5356  5402 I jxcore-log: 
09-16 06:41:52.917  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.917  5356  5402 I jxcore-log: 
,09-16 06:41:52.918  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.918  5356  5402 I jxcore-log: 
09-16 06:41:52.919  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.919  5356  5402 I jxcore-log: 
,09-16 06:41:52.919  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.919  5356  5402 I jxcore-log: 
09-16 06:41:52.919  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.919  5356  5402 I jxcore-log: 
,09-16 06:41:52.920  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.920  5356  5402 I jxcore-log: 
09-16 06:41:52.920  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.920  5356  5402 I jxcore-log: 
09-16 06:41:52.921  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.921  5356  5402 I jxcore-log: 
,09-16 06:41:52.921  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.921  5356  5402 I jxcore-log: 
09-16 06:41:52.922  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.922  5356  5402 I jxcore-log: 
,09-16 06:41:52.922  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.922  5356  5402 I jxcore-log: 
09-16 06:41:52.923  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.923  5356  5402 I jxcore-log: 
,09-16 06:41:52.923  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.923  5356  5402 I jxcore-log: 
09-16 06:41:52.923  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.923  5356  5402 I jxcore-log: 
09-16 06:41:52.924  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.924  5356  5402 I jxcore-log: 
,09-16 06:41:52.924  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.924  5356  5402 I jxcore-log: 
09-16 06:41:52.925  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.925  5356  5402 I jxcore-log: 
,09-16 06:41:52.925  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.925  5356  5402 I jxcore-log: 
09-16 06:41:52.926  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.926  5356  5402 I jxcore-log: 
,09-16 06:41:52.926  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.926  5356  5402 I jxcore-log: 
09-16 06:41:52.926  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.926  5356  5402 I jxcore-log: 
,09-16 06:41:52.927  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:52.927  5356  5402 I jxcore-log: 
09-16 06:41:52.927  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:52.927  5356  5402 I jxcore-log: 
,09-16 06:41:52.929  5356  5402 I jxcore-log: ok 28 native server is nulled out
09-16 06:41:52.929  5356  5402 I jxcore-log: 
,09-16 06:41:52.930  5356  5402 I jxcore-log: ok 29 native server should be closed
09-16 06:41:52.930  5356  5402 I jxcore-log: 
09-16 06:41:52.930  5356  5402 I jxcore-log: ok 30 incoming has been removed
09-16 06:41:52.930  5356  5402 I jxcore-log: 
09-16 06:41:52.931  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.931  5356  5402 I jxcore-log: 
,09-16 06:41:52.931  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.931  5356  5402 I jxcore-log: 
09-16 06:41:52.931  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.931  5356  5402 I jxcore-log: 
09-16 06:41:52.932  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.932  5356  5402 I jxcore-log: 
09-16 06:41:52.932  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.932  5356  5402 I jxcore-log: 
,09-16 06:41:52.932  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.932  5356  5402 I jxcore-log: 
09-16 06:41:52.932  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.932  5356  5402 I jxcore-log: 
09-16 06:41:52.932  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.932  5356  5402 I jxcore-log: 
09-16 06:41:52.933  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.933  5356  5402 I jxcore-log: 
09-16 06:41:52.933  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:52.933  5356  5402 I jxcore-log: 
,09-16 06:41:53.012  5356  5402 I jxcore-log: # teardown
09-16 06:41:53.012  5356  5402 I jxcore-log: 
,09-16 06:41:53.097  5356  5402 I jxcore-log: # setup
09-16 06:41:53.097  5356  5402 I jxcore-log: 
,09-16 06:41:53.827   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:54.511  5356  5402 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-16 06:41:54.511  5356  5402 I jxcore-log: 
,09-16 06:41:54.828   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:55.023  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:55.023  5356  5402 I jxcore-log: 
,09-16 06:41:55.030  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 49218
09-16 06:41:55.030  5356  5402 I jxcore-log: 
,09-16 06:41:55.042  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:55.042  5356  5402 I jxcore-log: 
,09-16 06:41:55.045  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:55.045  5356  5402 I jxcore-log: 
,09-16 06:41:55.048  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:55.048  5356  5402 I jxcore-log: 
,09-16 06:41:55.060  5356  5402 I jxcore-log: ok 31 we should not have gotten an error
09-16 06:41:55.060  5356  5402 I jxcore-log: 
,09-16 06:41:55.075  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:55.075  5356  5402 I jxcore-log: 
,09-16 06:41:55.079  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:55.079  5356  5402 I jxcore-log: 
,09-16 06:41:55.089  5356  5402 I jxcore-log: ok 32 Buffers are identical
09-16 06:41:55.089  5356  5402 I jxcore-log: 
,09-16 06:41:55.090  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:55.090  5356  5402 I jxcore-log: 
09-16 06:41:55.091  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:55.091  5356  5402 I jxcore-log: 
,09-16 06:41:55.104  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:55.104  5356  5402 I jxcore-log: 
,09-16 06:41:55.105  5356  5402 I jxcore-log: ok 33 server should be fine
09-16 06:41:55.105  5356  5402 I jxcore-log: 
,09-16 06:41:55.106  5356  5402 I jxcore-log: ok 34 server should be open
09-16 06:41:55.106  5356  5402 I jxcore-log: 
,09-16 06:41:55.107  5356  5402 I jxcore-log: ok 35 incoming has been removed
09-16 06:41:55.107  5356  5402 I jxcore-log: 
09-16 06:41:55.107  5356  5402 I jxcore-log: ok 36 The mux object should be closed
09-16 06:41:55.107  5356  5402 I jxcore-log: 
09-16 06:41:55.108  5356  5402 I jxcore-log: ok 37 The mux stream should be closed
09-16 06:41:55.108  5356  5402 I jxcore-log: 
,09-16 06:41:55.113  5356  5402 I jxcore-log: # teardown
09-16 06:41:55.113  5356  5402 I jxcore-log: 
,09-16 06:41:55.750  5356  5402 I jxcore-log: # setup
09-16 06:41:55.750  5356  5402 I jxcore-log: 
,09-16 06:41:55.829   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:41:56.359  5356  5402 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-16 06:41:56.359  5356  5402 I jxcore-log: 
,09-16 06:41:56.528  5356  5402 I jxcore-log: DEBUG createNativeListener: creating native server
09-16 06:41:56.528  5356  5402 I jxcore-log: 
,09-16 06:41:56.535  5356  5402 I jxcore-log: DEBUG createNativeListener: listening 37253
09-16 06:41:56.535  5356  5402 I jxcore-log: 
,09-16 06:41:56.544  5356  5402 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-16 06:41:56.544  5356  5402 I jxcore-log: 
,09-16 06:41:56.545  5356  5402 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-16 06:41:56.545  5356  5402 I jxcore-log: 
,09-16 06:41:56.547  5356  5402 I jxcore-log: DEBUG createNativeListener: new mux
09-16 06:41:56.547  5356  5402 I jxcore-log: 
,09-16 06:41:56.556  5356  5402 I jxcore-log: ok 38 we should not have gotten an error
09-16 06:41:56.556  5356  5402 I jxcore-log: 
,09-16 06:41:56.561  5356  5402 I jxcore-log: DEBUG createNativeListener: new stream: 
09-16 06:41:56.561  5356  5402 I jxcore-log: 
,09-16 06:41:56.563  5356  5402 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-16 06:41:56.563  5356  5402 I jxcore-log: 
,09-16 06:41:56.569  5356  5402 I jxcore-log: ok 39 Buffers are identical
09-16 06:41:56.569  5356  5402 I jxcore-log: 
,09-16 06:41:56.573  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-16 06:41:56.573  5356  5402 I jxcore-log: 
,09-16 06:41:56.574  5356  5402 I jxcore-log: DEBUG createNativeListener: stream close:
09-16 06:41:56.574  5356  5402 I jxcore-log: 
09-16 06:41:56.576  5356  5402 I jxcore-log: DEBUG createNativeListener: mux close
09-16 06:41:56.576  5356  5402 I jxcore-log: 
,09-16 06:41:56.580  5356  5402 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-16 06:41:56.580  5356  5402 I jxcore-log: 
,09-16 06:41:56.580  5356  5402 I jxcore-log: ok 40 server should be fine
09-16 06:41:56.580  5356  5402 I jxcore-log: 
09-16 06:41:56.580  5356  5402 I jxcore-log: ok 41 server should be open
09-16 06:41:56.580  5356  5402 I jxcore-log: 
09-16 06:41:56.581  5356  5402 I jxcore-log: ok 42 incoming has been removed
09-16 06:41:56.581  5356  5402 I jxcore-log: 
09-16 06:41:56.581  5356  5402 I jxcore-log: ok 43 The mux object should be closed
09-16 06:41:56.581  5356  5402 I jxcore-log: 
09-16 06:41:56.581  5356  5402 I jxcore-log: ok 44 The mux stream should be closed
09-16 06:41:56.581  5356  5402 I jxcore-log: 
,09-16 06:41:56.587  5356  5402 I jxcore-log: # teardown
09-16 06:41:56.587  5356  5402 I jxcore-log: 
,09-16 06:41:56.830   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:41:57.588  5356  5402 I jxcore-log: # setup
09-16 06:41:57.588  5356  5402 I jxcore-log: 
,09-16 06:41:58.659  5356  5402 I jxcore-log: # 12. Coordinated seq test
09-16 06:41:58.659  5356  5402 I jxcore-log: 
,09-16 06:42:01.831   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:02.832   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:03.833   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:04.834   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:05.836   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:06.836   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:42:11.216   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:14.243   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:16.838   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:17.839   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:18.840   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:19.842   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:20.306   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=492850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:42:20.844   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:21.845   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:42:29.381   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:30.853   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=503397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:42:32.171   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:42:35.414   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:36.846   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:37.847   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:38.848   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:39.849   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:40.851   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:42:41.461   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:41.852   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:42:44.493   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:45.373   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=517917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:42:47.529   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:50.565   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:42:55.906   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=528450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:43:01.853   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:02.658   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:02.854   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:03.855   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:04.856   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:05.858   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:06.859   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:43:08.724   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:10.440   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=542984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:43:12.176   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:43:17.813   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:20.851   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:20.946   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=553490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:43:23.879   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:31.860   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:43:31.860   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:43:32.179   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:43:35.453   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=567997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:43:35.998   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:39.028   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:45.986   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=578530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:43:51.138   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:54.156   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:43:56.871   535  1235 E QC-QMI  : qmi_client [535] 9: failed to locate client data
,09-16 06:43:56.873   519   519 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 06:43:56.874   519   519 E QC-QMI  : QMUX qmux_client_id=9 not found in qmux client list, unable to remove
,09-16 06:43:56.877   535   535 I Atfwd_Daemon: Stop the daemon....
,09-16 06:43:57.000  6184  6184 I libmdmdetect: ESOC framework not supported
,09-16 06:43:56.995  6184  6184 W ATFWD-daemon: type=1400 audit(0.0:118): avc: denied { read write } for name="diag" dev="tmpfs" ino=11960 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-16 06:43:57.000  6184  6184 I libmdmdetect: Found internal modem: modem
09-16 06:43:57.001  6184  6184 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 06:43:57.009  6184  6184 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-16 06:43:57.009  6184  6184 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 06:43:57.010  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:58.014  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:43:59.016  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:00.017  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:00.680   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=593224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:44:01.018  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:02.019  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:44:07.020  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:08.022  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:09.023  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:09.278   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:44:10.025  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:11.026  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:11.226   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=603770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:44:12.027  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:44:12.185   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:44:15.330   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:44:22.028  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:23.029  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:24.031  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:25.032  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:25.746   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=618290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:44:26.034  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:27.034  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:44:27.439   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:44:32.188   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:44:33.500   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:44:35.866   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=628410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:44:42.036  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:42.574   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:44:43.037  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:44.038  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:45.040  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:45.612   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:44:46.041  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:44:47.041  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:44:50.813   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=643357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:44:52.190   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:44:54.702   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:01.032   927   940 I ActivityManager: Start proc 6192:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-16 06:45:01.091  6192  6192 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,09-16 06:45:01.116  6192  6192 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-16 06:45:01.116  6192  6192 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-16 06:45:01.116  6192  6192 I GAv4    :   adb logcat -s GAv4
,09-16 06:45:01.129  6192  6192 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-16 06:45:01.134  6192  6192 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-16 06:45:01.148  6192  6207 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-16 06:45:01.219   927  3439 I ActivityManager: Killing 4696:com.android.vending/u0a22 (adj 15): empty #17
,09-16 06:45:01.319   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=653863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:45:03.789   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:07.043  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:08.044  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:09.047  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:10.048  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:11.049  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:12.050  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:45:15.826   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=668370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:45:26.360   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=678904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:45:31.046   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:32.194   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:45:37.051  6184  6184 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:45:37.051  6184  6184 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:45:37.108   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:40.147   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:40.893   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=693437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:45:42.052  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:43.053  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:43.181   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:44.054  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:45.056  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:46.057  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:47.058  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:45:51.399   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=703943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:45:52.059  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:52.198   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:45:52.260   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:53.061  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:54.063  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:55.065  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:55.299   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:45:56.066  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:45:57.067  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:46:04.389   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:05.906   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=718450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:46:07.068  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:07.413   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:08.070  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:09.071  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:10.073  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:11.074  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:11.253   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=723797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:46:12.075  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:46:12.199   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:46:19.529   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:27.076  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:28.077  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:28.619   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:29.079  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:30.080  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:30.946   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=743490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:46:31.082  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:32.083  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:46:32.200   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:46:37.400   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=749944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:46:37.706   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:43.770   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:52.084  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:52.204   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:46:52.866   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:46:53.085  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:54.086  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:55.088  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:56.039   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=768583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:46:56.089  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:46:57.090  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:46:58.925   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:05.640   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=778184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:47:11.038   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:14.056   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:21.053   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=793597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:47:22.091  6184  6184 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:47:22.091  6184  6184 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:47:26.170   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:29.203   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:31.573   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=804117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:47:32.093  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:32.210   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:47:33.094  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:34.095  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:35.097  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:36.098  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:37.099  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:47:42.101  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:43.102  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:44.104  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:44.349   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:45.106  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:46.066   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=818610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:47:46.107  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:47.108  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:47:50.416   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:47:52.212   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:47:56.626   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=829170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:47:57.109  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:58.111  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:59.112  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:47:59.505   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:00.113  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:01.114  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:02.115  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:48:05.558   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:11.133   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=843677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:48:12.213   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:48:17.116  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:17.665   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:18.118  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:19.119  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:20.120  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:21.122  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:21.666   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=854210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:48:22.123  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:48:23.718   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:29.781   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:32.216   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:48:32.815   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:35.845   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:36.200   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=868744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:48:38.876   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:42.124  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:43.126  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:44.127  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:45.128  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:46.129  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:48:46.706   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=879250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:48:47.130  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:48:50.974   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:48:52.217   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:48:54.010   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:01.213   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=893757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:49:09.159   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:11.746   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=904290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:49:12.131  6184  6184 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:49:12.131  6184  6184 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:49:12.194   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:12.217   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:49:21.281   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:24.317   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:26.279   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=918824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:49:27.132  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:28.134  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:29.136  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:30.137  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:31.139  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:32.140  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:49:32.219   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:49:36.786   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=929330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:49:37.141  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:38.143  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:39.144  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:39.469   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:40.145  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:41.146  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:42.147  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:49:45.523   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:48.554   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:51.580   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:49:51.720   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=944264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:49:52.148  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:53.149  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:54.151  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:55.152  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:56.153  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:49:57.154  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:50:02.266   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=954810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:50:12.156  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:12.225   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:50:13.157  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:14.159  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:15.160  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:15.792   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:16.161  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:16.786   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=969331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:50:17.161  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:50:24.881   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:27.306   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=979850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:50:27.917   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:30.959   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:32.226   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:50:33.991   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:37.024   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:37.163  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:38.164  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:39.166  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:40.167  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:41.169  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:50:41.800   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=994344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:50:42.169  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:50:49.129   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:52.164   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:52.227   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:50:52.346   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1004890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:50:55.206   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:50:58.233   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:01.265   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:06.866   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1019410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:51:07.170  6184  6184 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:51:07.171  6184  6184 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:51:07.329   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:12.228   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:51:16.418   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:17.400   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1029944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:51:22.478   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:27.172  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:28.174  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:29.175  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:30.177  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:31.178  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:31.986   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1044530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:51:32.179  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:51:32.230   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:51:37.180  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:37.614   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:38.182  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:39.183  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:40.185  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:40.643   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:51:41.186  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:42.187  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:51:42.519   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1055063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:51:52.188  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:52.233   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:51:53.190  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:54.191  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:55.193  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:56.194  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:51:57.053   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1069597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:51:57.195  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:52:07.586   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1080130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:52:07.918   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:12.196  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:12.235   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:52:13.197  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:13.967   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:14.198  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:15.200  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:16.201  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:17.202  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:52:22.760   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1095304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:52:23.049   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:29.109   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:32.236   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:52:33.320   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1105864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:52:35.171   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:37.203  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:38.204   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:38.205  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:39.206  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:40.208  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:41.209  6184  6184 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:52:41.237   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:42.210  6184  6184 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:52:47.880   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1120424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:52:52.239   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:52:53.347   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:56.380   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:52:58.413   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1130957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:53:02.439   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:07.211  6184  6184 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:53:07.211  6184  6184 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:53:11.529   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:12.241   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:53:12.893   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1145437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:53:20.630   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:23.453   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1155997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:53:28.560   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1161103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:53:29.711   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:32.223  6184  6186 E QC-QMI  : qmi_client [6184] 1d: failed to locate client data
,09-16 06:53:32.227   519   519 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 06:53:32.228   519   519 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-16 06:53:32.230  6184  6184 I Atfwd_Daemon: Stop the daemon....
,09-16 06:53:32.243   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:53:32.265  6229  6229 I libmdmdetect: ESOC framework not supported
,09-16 06:53:32.262  6229  6229 W ATFWD-daemon: type=1400 audit(0.0:119): avc: denied { read write } for name="diag" dev="tmpfs" ino=11960 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-16 06:53:32.266  6229  6229 I libmdmdetect: Found internal modem: modem
09-16 06:53:32.266  6229  6229 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 06:53:32.271  6229  6229 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-16 06:53:32.271  6229  6229 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 06:53:32.272  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:33.276  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:34.277  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:35.279  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:35.771   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:36.280  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:37.281  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:53:42.282  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:43.284  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:44.285  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:45.287  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:46.289  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:47.290  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:53:47.882   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:48.493   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1181037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:53:50.915   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:53:53.600   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1186144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:53:57.291  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:58.293  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:53:59.294  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:00.296  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:01.297  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:02.298  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:54:03.020   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:09.077   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:12.246   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:54:13.533   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1206077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:54:17.300  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:18.301  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:18.640   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1211184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:54:19.303  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:20.304  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:21.204   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:21.305  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:22.306  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:54:24.245   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:27.139   927   939 I UsageStatsService: User[0] Flushing usage stats to disk
,09-16 06:54:32.247   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:54:36.344   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:38.573   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1231117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:54:42.307  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:42.398   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:43.309  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:43.693   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1236237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:54:44.310  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:45.311  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:46.313  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:54:47.314  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:54:51.488   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:54:52.249   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:54:57.546   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:03.933   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1256477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:55:09.052   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1261597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:55:09.667   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:12.252   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:55:12.315  6229  6229 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:55:12.315  6229  6229 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:55:12.691   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:17.316  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:18.318  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:19.319  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:20.321  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:21.322  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:22.322  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:55:24.804   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:27.324  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:28.325  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:28.973   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1281517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:55:29.327  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:30.328  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:30.862   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:31.330  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:32.254   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:55:32.330  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:55:34.092   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1286637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:55:39.944   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:42.332  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:43.333  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:44.334  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:45.336  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:46.337  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:55:47.338  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:55:49.021   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:51.884  5947  5962 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,09-16 06:55:52.255   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:55:54.053   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1306597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:55:58.104   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:55:59.159   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1311704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:56:02.339  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:03.341  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:04.342  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:05.344  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:06.345  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:07.181   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:07.345  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:56:12.257   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:56:16.268   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:19.106   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1331650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:56:22.321   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:24.359   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1336903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:56:27.347  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:28.348  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:29.350  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:30.351  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:31.353  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:56:31.411   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:32.259   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:56:32.353  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:56:37.475   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:44.306   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1356850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:56:49.426   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1361970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:56:49.584   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:52.262   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:56:55.620   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:56:57.354  6229  6229 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:56:57.354  6229  6229 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:57:04.715   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:07.356  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:08.357  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:09.358  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:09.359   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1381903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:57:10.359  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:10.759   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:11.361  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:12.263   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:57:12.362  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:57:14.466   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1387010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:57:17.363  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:18.364  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:19.366  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:20.367  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:21.368  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:22.369  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:57:22.857   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:28.919   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:32.264   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:57:32.370  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:33.372  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:34.373  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:34.413   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1406957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:57:35.375  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:36.376  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:37.377  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:57:38.012   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:40.093   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1412637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:57:44.077   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:52.267   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:57:52.378  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:53.379  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:54.380  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:55.382  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:56.190   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:57:56.383  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:57:57.384  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:58:00.026   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1432570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:58:02.259   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:58:05.133   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1437677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:58:11.343   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:58:12.267   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:58:17.385  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:58:17.400   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:58:18.386  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:58:19.388  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:58:20.390  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:58:21.391  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:58:22.391  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 06:58:25.066   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1457610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:58:28.260   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1460804, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:58:32.270   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:58:47.392  6229  6229 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 06:58:47.392  6229  6229 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 06:58:47.647   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:58:50.106   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1482650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:58:50.681   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:58:52.271   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:58:53.313   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1485857, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:58:59.761   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:02.393  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:02.794   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:03.395  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:04.396  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:05.398  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:06.400  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:07.400  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 06:59:12.272   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:59:12.402  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:13.403  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:14.404  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:15.172   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1507716, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:59:15.405  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:16.407  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:17.408  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 06:59:17.948   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:18.459   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1511003, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:59:20.987   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:27.049   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:27.409  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:28.410  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:29.411  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:30.080   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:30.413  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:31.414  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:32.275   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 06:59:32.415  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 06:59:33.105   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:39.173   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:40.346   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1532890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 06:59:43.540   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1536084, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 06:59:47.417  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:48.418  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:49.420  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:50.421  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:51.294   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 06:59:51.422  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 06:59:52.423  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 06:59:54.316   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:05.386   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1557930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:00:08.586   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1561130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:00:12.280   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:00:12.424  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:00:13.426  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:00:14.427  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:00:15.428  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:00:16.429  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:00:17.430  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 07:00:21.549   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:24.580   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:27.612   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:30.440   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1582984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-16 07:00:30.632   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:32.283   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:00:38.653   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1591197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:00:39.716   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:42.431  6229  6229 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 07:00:42.431  6229  6229 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 07:00:42.749   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:00:52.284   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:00:55.480   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1608024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:00:58.666   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1611210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:01:02.432  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:03.433  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:03.959   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:04.435  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:05.437  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:06.438  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:06.997   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:07.439  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 07:01:12.287   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:01:12.440  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:13.047   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:13.441  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:14.443  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:15.444  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:16.082   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:16.446  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:17.447  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 07:01:19.113   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:20.520   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1633064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:01:22.150   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:23.726   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1636270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:01:27.448  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:28.450  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:29.451  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:30.453  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:31.454  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:32.289   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:01:32.455  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-16 07:01:45.573   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1658117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:01:46.381   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:47.456  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:48.458  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:48.773   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1661316, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:01:49.407   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:01:49.459  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:50.460  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:51.462  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:01:52.292   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:01:52.462  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-16 07:02:01.508   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:04.543   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:10.626   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1683170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:02:12.294   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:02:12.463  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:02:13.465  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:02:13.827   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1686371, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:02:14.466  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:02:15.468  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:02:16.469  6229  6229 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 07:02:17.470  6229  6229 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-16 07:02:32.295   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:02:35.679   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1708223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:02:38.873   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1711417, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:02:40.871   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:42.471  6229  6229 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-16 07:02:42.472  6229  6229 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-16 07:02:43.899   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:49.951   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:52.298   927  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-16 07:02:52.982   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:56.008   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:02:59.037   927  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-16 07:03:00.733   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1733277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-16 07:03:04.559   927  6151 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1737103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-16 07:03:07.482  6229  6231 E QC-QMI  : qmi_client [6229] 1e: failed to locate client data
,09-16 07:03:07.485   519   519 E QC-QMI  : qmuxd: RX on fd=18 returned error=0 errno[2:No such file or directory]
,09-16 07:03:07.485   519   519 E QC-QMI  : QMUX qmux_client_id=1e not found in qmux client list, unable to remove
,09-16 07:03:07.488  6229  6229 I Atfwd_Daemon: Stop the daemon....
,09-16 07:03:07.534  6246  6246 I libmdmdetect: ESOC framework not supported
,09-16 07:03:07.532  6246  6246 W ATFWD-daemon: type=1400 audit(0.0:120): avc: denied { read write } for name="diag" dev="tmpfs" ino=11960 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-16 07:03:07.535  6246  6246 I libmdmdetect: Found internal modem: modem
09-16 07:03:07.536  6246  6246 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-16 07:03:07.545  6246  6246 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-16 07:03:07.545  6246  6246 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-16 07:03:07.546  6246  6246 I ServiceManager: Waiting for service AtCmdFwd...
,TIME-OUT KILL (timeout was 1400000ms),09-16 07:03:08.221  6250  6250 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 07:03:08.226  6250  6250 D AndroidRuntime: CheckJNI is OFF
09-16 07:03:08.261  6250  6250 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 07:03:08.296  6250  6250 I Radio-JNI: register_android_hardware_Radio DONE
09-16 07:03:08.313  6250  6250 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-16 07:03:08.323   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-16 07:03:08.324   927   940 I ActivityManager: Killing 5356:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-16 07:03:08.415   927   938 I WindowState: WIN DEATH: Window{5ed8036 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-16 07:03:08.415   927  2982 D WifiService: Client connection lost with reason: 4
09-16 07:03:08.416   927  3440 D GraphicsStats: Buffer count: 2
09-16 07:03:08.458   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-16 07:03:08.458   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-16 07:03:08.459   927   950 I art     : Starting a blocking GC Explicit
09-16 07:03:08.459   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-16 07:03:08.459   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-16 07:03:08.459   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:08.459   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:08.459   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 07:03:08.459   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 07:03:08.461   927   940 I ActivityManager:   Force finishing activity ActivityRecord{43b5c7b u0 com.test.thalitest/.MainActivity t4}
09-16 07:03:08.471   927  3572 W ActivityManager: Spurious death for ProcessRecord{cf09aea 0:com.test.thalitest/u0a77}, curProc for 5356: null
09-16 07:03:08.474   927   945 W WindowManager: Attempted to add application window with unknown token Token{5960a98 ActivityRecord{43b5c7b u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
09-16 07:03:08.475   927   945 W WindowManager: Token{5960a98 ActivityRecord{43b5c7b u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{5960a98 ActivityRecord{43b5c7b u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-16 07:03:08.475   927   945 W WindowManager: view not successfully added to wm, removing view
09-16 07:03:08.475   927   945 W WindowManager: Exception when adding starting window
09-16 07:03:08.475   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{20c478d V.E...... R.....ID 0,0-0,0} not attached to window manager
09-16 07:03:08.475   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-16 07:03:08.475   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-16 07:03:08.475   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-16 07:03:08.475   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-16 07:03:08.475   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-16 07:03:08.475   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:08.475   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:08.475   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 07:03:08.475   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 07:03:08.551  6246  6246 I ServiceManager: Waiting for service AtCmdFwd...
09-16 07:03:08.557   927   950 I art     : Explicit concurrent mark sweep GC freed 143473(9MB) AllocSpace objects, 84(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.516ms total 97.857ms
09-16 07:03:08.579   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-16 07:03:08.582  6250  6250 I art     : System.exit called, status: 0
09-16 07:03:08.582  6250  6250 I AndroidRuntime: VM exiting with result code 0.
09-16 07:03:08.599   927   950 I ActivityManager: Start proc 6260:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-16 07:03:08.599   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-16 07:03:08.605   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-16 07:03:08.609  5947  5947 D BluetoothMapAppObserver: onReceive
09-16 07:03:08.609  5947  5947 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-16 07:03:08.612  3476  3948 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-16 07:03:08.615  3405  3405 I Keyboard.Facilitator: resetDictionaries() : en_US
09-16 07:03:08.622   927  2955 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-16 07:03:08.629  3405  6272 I Keyboard.Facilitator.DecoderInitializer: run()
09-16 07:03:08.634  3405  6272 I Decoder : createOrResetDecoder
09-16 07:03:08.657  5754  6275 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-16 07:03:08.666   927  3438 I ActivityManager: Start proc 6277:com.android.musicfx/u0a21 for broadcast com.android.musicfx/.Compatibility$Receiver
09-16 07:03:08.667  3535  3535 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-16 07:03:08.671  3652  3652 I ConfigService: onCreate
09-16 07:03:08.675   446   446 W kworker/7:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 07:03:08.679   446   446 W kworker/7:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 07:03:08.693   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-16 07:03:08.704  3405  6272 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-16 07:03:08.702   446   446 W kworker/7:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 07:03:08.706  3574  3736 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-16 07:03:08.720   927  3572 I ActivityManager: Start proc 6292:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-16 07:03:08.721  3574  3736 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-16 07:03:08.721  3574  3736 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3574
09-16 07:03:08.721  3574  3736 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:08.721  3574  3736 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 07:03:08.725   927  3121 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 07:03:08.725   927  6299 E DropBoxManagerService: Can't write: system_app_crash
09-16 07:03:08.725   927  6299 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 07:03:08.725   927  6299 E DropBoxManagerService: 	... 5 more
09-16 07:03:08.730  3574  3736 I Process : Sending signal. PID: 3574 SIG: 9
09-16 07:03:08.764  5754  6275 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-16 07:03:08.777  6277  6277 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm64
09-16 07:03:08.777  5754  6275 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-16 07:03:08.777  5754  6275 E AndroidRuntime: Process: android.process.acore, PID: 5754
09-16 07:03:08.777  5754  6275 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:08.777  5754  6275 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 07:03:08.782  5754  6275 I Process : Sending signal. PID: 5754 SIG: 9
09-16 07:03:08.805   381   381 E lowmemorykiller: Error writing /proc/5754/oom_score_adj; errno=22
09-16 07:03:08.825   927  3437 I ActivityManager: Start proc 6310:com.android.vending/u0a22 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
09-16 07:03:08.854   381   381 E lowmemorykiller: Error writing /proc/5754/oom_score_adj; errno=22
09-16 07:03:08.863   927  3438 I WindowState: WIN DEATH: Window{5590bf5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-16 07:03:08.863   927  3572 D GraphicsStats: Buffer count: 1
09-16 07:03:08.869   927  3572 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3574) has died
09-16 07:03:08.869   927  3572 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-16 07:03:08.871   927  3572 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 07:03:08.888   927   940 I ActivityManager: Start proc 6324:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 07:03:08.889   927  3605 I ActivityManager: Process android.process.acore (pid 5754) has died
09-16 07:03:08.889   927  3605 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 07:03:08.930  6324  6324 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 07:03:08.930  6324  6324 D AndroidRuntime: Shutting down VM
09-16 07:03:08.938  6324  6324 E AndroidRuntime: FATAL EXCEPTION: main
09-16 07:03:08.938  6324  6324 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6324
09-16 07:03:08.938  6324  6324 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 07:03:08.938  6324  6324 E AndroidRuntime: 	... 10 more
09-16 07:03:08.941   927  5508 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 07:03:08.942  6324  6324 I Process : Sending signal. PID: 6324 SIG: 9
09-16 07:03:08.964   927  3437 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6324) has died
09-16 07:03:08.965   927  3437 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 07:03:08.980   927   940 I ActivityManager: Start proc 6337:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 07:03:09.033  6337  6337 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 07:03:09.033  6337  6337 D AndroidRuntime: Shutting down VM
09-16 07:03:09.044  6337  6337 E AndroidRuntime: FATAL EXCEPTION: main
09-16 07:03:09.044  6337  6337 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6337
09-16 07:03:09.044  6337  6337 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-16 07:03:09.044  6337  6337 E AndroidRuntime: 	... 10 more
09-16 07:03:09.047   927  3121 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-16 07:03:09.048  6337  6337 I Process : Sending signal. PID: 6337 SIG: 9
09-16 07:03:09.071   927  3440 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6337) has died
09-16 07:03:09.073   927  3440 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-16 07:03:09.083   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
