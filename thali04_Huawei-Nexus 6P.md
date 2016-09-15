#### Test 82914073713e010_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
,09-15 12:58:57.537   594   594 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 12:58:57.538   594   594 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-15 12:58:58.047  5470  5470 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 12:58:58.053  5470  5470 D AndroidRuntime: CheckJNI is OFF
09-15 12:58:58.081  5470  5470 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 12:58:58.112  5470  5470 I Radio-JNI: register_android_hardware_Radio DONE
09-15 12:58:58.127  5470  5470 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 12:58:58.130   926  3411 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 12:58:58.169   926  3411 I ActivityManager: Start proc 5479:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 12:58:58.174  5470  5470 D AndroidRuntime: Shutting down VM
09-15 12:58:58.270  5479  5479 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 12:58:58.304  5479  5479 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 12:58:58.331  5479  5479 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 619-638)
09-15 12:58:58.331  5479  5479 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 12:58:58.350  5479  5479 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0ff39f}
09-15 12:58:58.351  5479  5479 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 12:58:58.354  5479  5479 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 12:58:58.359  5479  5479 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 12:58:58.361  5479  5479 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 12:58:58.399  5479  5479 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-15 12:58:58.413  5479  5479 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 12:58:58.414  5479  5479 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 12:58:58.414  5479  5479 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 12:58:58.414  5479  5479 I Adreno  : Build Date                       : 12/06/15
09-15 12:58:58.414  5479  5479 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 12:58:58.414  5479  5479 I Adreno  : Local Branch                     : mybranch17112971
09-15 12:58:58.414  5479  5479 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 12:58:58.414  5479  5479 I Adreno  : Remote Branch                    : NONE
09-15 12:58:58.414  5479  5479 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 12:58:58.479   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c051c0c:true
,09-15 12:58:58.512   696   696 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[14294]" dev="sockfs" ino=14294 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 12:58:58.512   696   696 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14294]" dev="sockfs" ino=14294 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 12:58:58.528  5479  5479 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 12:58:58.537  5479  5479 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 12:58:58.562   696   696 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31360]" dev="sockfs" ino=31360 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 12:58:58.566  5479  5516 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-15 12:58:58.562   696   696 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31360]" dev="sockfs" ino=31360 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 12:58:58.566  3507  3507 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[14305]" dev="sockfs" ino=14305 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 12:58:58.566  3507  3507 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14305]" dev="sockfs" ino=14305 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 12:58:58.574  5479  5503 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 12:58:58.614  5479  5516 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 12:58:58.690   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +472ms (total +546ms)
,09-15 12:58:58.711  5479  5479 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5479
,09-15 12:58:58.796  5479  5479 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 12:58:58.944  5479  5519 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -585365200
,09-15 12:58:58.955  5479  5519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 12:58:58.955  5479  5519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 12:58:58.955  5479  5519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 12:58:58.955  5479  5519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 12:58:58.955  5479  5519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 12:58:58.955  5479  5519 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d472e44 added. We now have 1 listener(s)
,09-15 12:58:58.959  5479  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 12:58:58.960  5479  5519 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 12:58:58.960  5479  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:58:58.961  5479  5519 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-15 12:58:58.965  5479  5519 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@785cdf3 added. We now have 1 listener(s)
09-15 12:58:58.965  5479  5519 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:58:58.969   926  2944 D WifiService: New client listening to asynchronous messages
,09-15 12:58:58.970  5479  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 12:58:58.970  5479  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 12:58:58.970  5479  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 12:58:58.970  5479  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 12:58:58.970  5479  5519 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 12:58:58.973  5479  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:58:58.974  5479  5519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 12:58:58.981  5479  5519 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:58:58.981  5479  5519 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 12:58:58.981  5479  5519 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 12:58:58.981  5479  5519 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:58:58.982  5479  5519 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 12:58:58.984  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:58:58.986  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:58:59.009  5479  5479 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 12:58:59.262  5479  5525 W jxcore-log: Initializing JXcore engine
09-15 12:58:59.262  5479  5525 W jxcore-log: JXcore engine is ready
,09-15 12:58:59.282  5525  5525 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-15 12:58:59.282  5525  5525 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[13660]" dev="sockfs" ino=13660 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 12:58:59.282  5525  5525 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 12:58:59.282  5525  5525 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31333]" dev="sockfs" ino=31333 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 12:58:59.294  5479  5525 W jxcore-log: Starting JXcore engine
,09-15 12:58:59.344  5479  5525 W jxcore-log: Platform android
09-15 12:58:59.344  5479  5525 W jxcore-log: 
,09-15 12:58:59.344  5479  5525 W jxcore-log: Process ARCH arm
09-15 12:58:59.344  5479  5525 W jxcore-log: 
,09-15 12:58:59.444  5479  5525 I jxcore-log: JXcore Cordova bridge is ready!
09-15 12:58:59.444  5479  5525 I jxcore-log: 
,09-15 12:58:59.445  5479  5525 W jxcore-log: JXcore engine is started
,09-15 12:58:59.448  5479  5519 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 12:58:59.451  5479  5479 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 12:59:06.004  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 12:59:06.004  5479  5525 I jxcore-log: 
,09-15 12:59:06.006  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 12:59:06.006  5479  5525 I jxcore-log: 
,09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.010  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 12:59:06.012  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 12:59:06.013  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 12:59:06.013  5479  5525 I jxcore-log: 
,09-15 12:59:06.015  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 12:59:06.015  5479  5525 I jxcore-log: 
,09-15 12:59:06.356  5479  5525 D executeNativeTests: Running unit tests
,09-15 12:59:06.391  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 12:59:06.391  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 added. We now have 2 listener(s)
09-15 12:59:06.392  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:06.392  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:06.392  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 12:59:06.392  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 12:59:06.392  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd added. We now have 2 listener(s)
09-15 12:59:06.392  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:06.393  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 12:59:06.394  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.396  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 12:59:06.397  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.398  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 12:59:06.399  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 12:59:06.399  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-15 12:59:06.399  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 12:59:06.400  5479  5525 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 12:59:06.400  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-15 12:59:06.400  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 12:59:06.400  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 12:59:06.400  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 12:59:06.400  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.400  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.400  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.400  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.400  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 12:59:06.400  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:06.400  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:06.400  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 removed from the list
09-15 12:59:06.401  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.401  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd removed from the list
09-15 12:59:06.403  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:06.410  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:06.410  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 12:59:06.410  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.411  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.411  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 12:59:06.411  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 12:59:06.411  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.411  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 12:59:06.411  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
,09-15 12:59:06.412  5479  5525 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-15 12:59:06.413  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.413  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.413  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.413  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.413  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.413  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.413  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.413  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.413  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.413  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.413  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.413  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.413  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.413  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.413  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.413  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.413  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.414  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemove,AllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-15 12:59:06.416  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 12:59:06.417  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-15 12:59:06.417  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 12:59:06.417  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 12:59:06.417  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 12:59:06.417  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 12:59:06.417  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.417  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.417  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.417  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.417  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.417  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
,09-15 12:59:06.417  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.417  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.417  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.417  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.417  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.417  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.417  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.418  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.418  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.418  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-15 12:59:06.418  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.418  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 12:59:06.419  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.424  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 12:59:06.427  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.428  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:59:06.428  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:06.428  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 12:59:06.428  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 12:59:06.428  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:06.428  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 12:59:06.432  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 12:59:06.432  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 12:59:06.433  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.434  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 12:59:06.435  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 12:59:06.435  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 12:59:06.436  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.437  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-15 12:59:06.438  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 12:59:06.438  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 12:59:06.438  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 12:59:06.438  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 12:59:06.439  5479  5525 D BluetoothAdapter: STATE_ON
,09-15 12:59:06.441  4448  4463 D BtGatt.GattService: registerClient() - UUID=b164d660-56ce-4e72-9b63-36382a23d4f7
,09-15 12:59:06.441  4448  4510 D BtGatt.GattService: onClientRegistered() - UUID=b164d660-56ce-4e72-9b63-36382a23d4f7, clientIf=5
,09-15 12:59:06.442  5479  5489 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 12:59:06.443  4448  4659 D BtGatt.GattService: start scan with filters
,09-15 12:59:06.447  4448  4515 D BtGatt.ScanManager: handling starting scan
,09-15 12:59:06.448  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 12:59:06.448  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 12:59:06.448  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 12:59:06.448  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 12:59:06.449  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:06.449  4448  4515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:06.449  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 12:59:06.449  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:06.450  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 12:59:06.451  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
09-15 12:59:06.452  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.452  5479  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 12:59:06.452  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.452  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 12:59:06.452  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 12:59:06.452  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 12:59:06.452  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 12:59:06.452  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:06.452  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 12:59:06.453  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 12:59:06.453  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 12:59:06.453  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 12:59:06.453  5479  5525 D BluetoothAdapter: STATE_ON
,09-15 12:59:06.453  4448  4462 D BtGatt.GattService: stopScan() - queue size =1
,09-15 12:59:06.454  4448  4463 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 12:59:06.455  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 12:59:06.455  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 12:59:06.455  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 12:59:06.455  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 12:59:06.455  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 12:59:06.457  4448  4510 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 12:59:06.457  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.457  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 12:59:06.457  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 12:59:06.457  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 12:59:06.457  4448  4515 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 12:59:06.458  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 12:59:06.458  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 12:59:06.459  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.459  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.459  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.459  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.460  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:06.460  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:06.460  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.460  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 12:59:06.460  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.460  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.460  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.464  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 12:59:06.464  4448  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 12:59:06.464  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.464  4448  4515 D BtGatt.ScanManager: Starting BLE batch scan
09-15 12:59:06.465  4448  4515 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 12:59:06.466  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.468  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 12:59:06.471  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 12:59:06.471  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:59:06.471  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:06.471  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 12:59:06.471  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 12:59:06.472  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:06.472  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 12:59:06.473  4448  4510 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 12:59:06.473  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.474  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 12:59:06.474  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 12:59:06.475  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.476  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 12:59:06.477  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 12:59:06.477  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 12:59:06.478  4448  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 12:59:06.478  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:06.478  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:06.479  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 12:59:06.479  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 12:59:06.480  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 12:59:06.480  5479  5525 D BluetoothAdapter: STATE_ON
,09-15 12:59:06.482  4448  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 12:59:06.482  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.482  4448  4515 D BtGatt.ScanManager: stopping BLe Batch
09-15 12:59:06.482  4448  4462 D BtGatt.GattService: registerClient() - UUID=6aec1e8d-1a31-4903-9d8d-79623cffb5e8
09-15 12:59:06.482  4448  4510 D BtGatt.GattService: onClientRegistered() - UUID=6aec1e8d-1a31-4903-9d8d-79623cffb5e8, clientIf=5
,09-15 12:59:06.483  5479  5490 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 12:59:06.483  4448  4463 D BtGatt.GattService: start scan with filters
,09-15 12:59:06.486  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 12:59:06.486  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 12:59:06.486  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-15 12:59:06.486  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 12:59:06.487  4448  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 12:59:06.487  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.488  4448  4515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 12:59:06.488  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:06.488  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 12:59:06.488  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 12:59:06.490  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 12:59:06.491  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 12:59:06.492  4448  4510 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 12:59:06.492  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.493  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.493  5479  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 12:59:06.494  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.494  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 12:59:06.494  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.494  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 12:59:06.494  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 12:59:06.494  4448  4515 D BtGatt.ScanManager: handling starting scan
09-15 12:59:06.494  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:06.494  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 12:59:06.494  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 12:59:06.494  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 12:59:06.494  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 12:59:06.495  5479  5525 D BluetoothAdapter: STATE_ON
09-15 12:59:06.495  4448  4462 D BtGatt.GattService: stopScan() - queue size =1
,09-15 12:59:06.496  4448  4659 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 12:59:06.496  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 12:59:06.496  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 12:59:06.496  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 12:59:06.496  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 12:59:06.496  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 12:59:06.497  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:06.497  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 12:59:06.497  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 12:59:06.497  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 12:59:06.498  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 12:59:06.499  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.499  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.499  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.499  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:06.499  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.499  4448  4510 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 12:59:06.500  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:06.500  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
,09-15 12:59:06.500  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.500  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.500  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.500  4448  4515 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 12:59:06.500  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.500  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 12:59:06.500  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.500  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.501  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.501  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.501  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 12:59:06.501  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.502  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 12:59:06.503  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:06.505  4448  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 12:59:06.505  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.505  4448  4515 D BtGatt.ScanManager: Starting BLE batch scan
09-15 12:59:06.505  4448  4515 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.506  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 12:59:06.508  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.509  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 12:59:06.509  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 12:59:06.509  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 12:59:06.509  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 12:59:06.509  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:06.509  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 12:59:06.511  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.512  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 12:59:06.512  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 12:59:06.513  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.515  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 12:59:06.516  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 12:59:06.516  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 12:59:06.517  4448  4510 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 12:59:06.517  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:06.518  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 12:59:06.519  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 12:59:06.519  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 12:59:06.519  5479  5525 D BluetoothAdapter: STATE_ON
,09-15 12:59:06.521  4448  4462 D BtGatt.GattService: registerClient() - UUID=b27c7b17-d2fb-42d5-b424-fef7ed6f83f6
,09-15 12:59:06.522  4448  4510 D BtGatt.GattService: onClientRegistered() - UUID=b27c7b17-d2fb-42d5-b424-fef7ed6f83f6, clientIf=5
,09-15 12:59:06.522  5479  5490 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 12:59:06.522  4448  4659 D BtGatt.GattService: start scan with filters
,09-15 12:59:06.523  4448  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 12:59:06.523  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.525  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 12:59:06.525  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 12:59:06.525  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 12:59:06.525  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 12:59:06.527  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 12:59:06.527  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 12:59:06.527  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:06.528  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 12:59:06.530  4448  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 12:59:06.530  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
09-15 12:59:06.530  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.530  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.530  5479  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 12:59:06.530  4448  4515 D BtGatt.ScanManager: stopping BLe Batch
09-15 12:59:06.530  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.530  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 12:59:06.530  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.530  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 12:59:06.530  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 12:59:06.530  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:06.530  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 12:59:06.530  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 12:59:06.531  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 12:59:06.531  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 12:59:06.531  5479  5525 D BluetoothAdapter: STATE_ON
09-15 12:59:06.532  4448  4463 D BtGatt.GattService: stopScan() - queue size =0
09-15 12:59:06.533  4448  4462 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 12:59:06.533  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 12:59:06.533  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 12:59:06.533  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 12:59:06.533  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 12:59:06.533  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 12:59:06.535  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 12:59:06.535  4448  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 12:59:06.535  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 12:59:06.535  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.535  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 12:59:06.535  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 12:59:06.535  4448  4515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 12:59:06.535  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:06.536  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.536  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 12:59:06.537  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.537  5479  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 12:59:06.537  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.537  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:06.537  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.537  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.537  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.537  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:06.537  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.537  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 12:59:06.537  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.537  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.537  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.538  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.538  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.538  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.539  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.539  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.539  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
,09-15 12:59:06.539  5479  5525 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 12:59:06.540  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.540  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.540  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.540  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.540  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.540  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.540  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.540  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.540  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.540  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 12:59:06.540  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.540  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.540  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.540  4448  4510 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 12:59:06.540  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.540  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:06.542  4448  4515 D BtGatt.ScanManager: handling starting scan
09-15 12:59:06.543  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.543  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.543  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.543  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.543  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 12:59:06.543  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.544  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.544  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.544  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.544  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.544  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.544  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.544  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.544  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.544  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.544  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.544  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.544  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.544  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.545  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.545  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.545  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.545  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.546  5479  5525 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 12:59:06.546  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.546  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.546  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.546  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.546  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.546  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.546  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.546  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.546  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.546  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.547  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.547  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.547  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.547  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.547  4448  4510 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 12:59:06.548  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.548  4448  4515 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 12:59:06.548  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.548  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.548  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.548  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.548  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-15 12:59:06.549  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.549  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.549  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.549  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.549  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.549  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.549  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.549  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.549  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.549  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.549  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.550  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.550  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.550  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.552  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.552  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.552  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.552  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.552  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 12:59:06.552  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 12:59:06.552  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 12:59:06.552  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 12:59:06.552  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 12:59:06.552  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 12:59:06.553  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.553  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.553  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.553  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.553  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.553  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.553  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.553  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.553  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.553  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.553  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.553  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.553  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.553  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.554  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.554  4448  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 12:59:06.554  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.554  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.554  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.554  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.554  4448  4515 D BtGatt.ScanManager: Starting BLE batch scan
09-15 12:59:06.554  4448  4515 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 12:59:06.554  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 12:59:06.554  5479  5525 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 12:59:06.554  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 12:59:06.556  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 12:59:06.556  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 12:59:06.556  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 12:59:06.557  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 12:59:06.557  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 12:59:06.558  5479  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 12:59:06.558  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 12:59:06.558  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 12:59:06.558  5479  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 12:59:06.558  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 12:59:06.558  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 12:59:06.558  5479  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 12:59:06.558  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 12:59:06.560  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 12:59:06.561  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 12:59:06.561  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 12:59:06.561  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 12:59:06.561  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 12:59:06.561  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 12:59:06.561  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 12:59:06.561  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 12:59:06.562  5479  5526 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 12:59:06.562  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.562  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.562  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.562  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.562  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.562  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.562  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 12:59:06.563  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.563  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.563  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.563  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.563  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.563  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.563  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.563  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.563  4448  4510 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 12:59:06.563  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.563  5479  5526 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 12:59:06.564  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.564  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.564  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.564  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.565  5479  5525 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 12:59:06.565  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.565  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.565  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.565  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.565  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.565  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.565  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.565  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.565  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.565  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.565  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.565  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.566  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.566  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.559  4462  4462 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32125]" dev="sockfs" ino=32125 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 12:59:06.567  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.567  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.567  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.567  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.567  5479  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 12:59:06.567  5479  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-15 12:59:06.567  5479  5525 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 12:59:06.567  5479  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-15 12:59:06.567  5479  5526 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-15 12:59:06.567  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.568  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.568  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.568  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.568  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.568  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.568  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.568  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.568  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.568  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.568  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.568  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.568  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.568  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.567  4448  4657 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-15 12:59:06.559  4462  4462 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32125]" dev="sockfs" ino=32125 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 12:59:06.572  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.572  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.572  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.572  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 12:59:06.573  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 12:59:06.573  5479  5525 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 12:59:06.573  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 12:59:06.573  5479  5525 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 12:59:06.573  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 12:59:06.573  5479  5525 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 12:59:06.573  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.573  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.573  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.573  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.573  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.573  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.573  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.573  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.573  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.573  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.574  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.574  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.574  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.574  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.574  4448  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 12:59:06.574  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.574  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.574  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.575  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.575  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.575  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.575  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.576  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.576  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.576  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.576  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.576  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.576  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.576  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.576  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.576  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.576  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.576  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.576  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.576  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.576  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.576  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.576  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.576  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.576  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.576  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.577  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.577  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.577  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.577  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.577  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.577  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.577  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.578  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 12:59:06.578  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:06.579  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 12:59:06.579  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 12:59:06.579  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 12:59:06.579  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 12:59:06.579  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 12:59:06.579  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 12:59:06.579  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.579  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 12:59:06.579  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 12:59:06.580  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.580  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.580  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 12:59:06.580  5479  5528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 12:59:06.580  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.580  5479  5528 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.580  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:06.580  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 12:59:06.581  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.581  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.581  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.581  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:06.581  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 12:59:06.581  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.581  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.581  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:06.581  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.581  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.581  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.581  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.581  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.581  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.581  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.581  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.581  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.581  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.581  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.582  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.582  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.582  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.582  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.582  5479  5525 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 12:59:06.582  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 12:59:06.582  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 12:59:06.583  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 12:59:06.583  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.583  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.583  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.583  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.583  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.583  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.583  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.583  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.583  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.583  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.583  4448  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 12:59:06.583  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.583  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.583  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.583  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.583  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.583  4448  4515 D BtGatt.ScanManager: stopping BLe Batch
09-15 12:59:06.584  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.584  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.584  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.584  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.587  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.587  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.587  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.587  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.587  4448  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 12:59:06.587  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.587  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.587  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.587  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.587  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.587  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.587  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.587  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.587  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.587  4448  4515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 12:59:06.587  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.587  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.588  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.588  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.588  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.588  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.588  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:06.588  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:06.588  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:06.589  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:06.589  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.589  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.589  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbec14 not in the list
09-15 12:59:06.589  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.589  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.589  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:06.589  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.589  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.589  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:06.589  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:06.591  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:06.591  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:06.591  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:06.591  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@469ccbd not in the list
09-15 12:59:06.591  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 12:59:06.591  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 12:59:06.592  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 12:59:06.592  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 12:59:06.592  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 12:59:06.592  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 12:59:06.593  4448  4510 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 12:59:06.593  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 12:59:06.593  4448  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:06.593  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 12:59:06.593  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 12:59:06.593  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 12:59:06.593  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 12:59:06.593  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 12:59:06.593  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 12:59:06.593  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 12:59:06.594  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 12:59:06.594  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 12:59:06.594  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 12:59:06.594  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 12:59:06.594  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 12:59:06.594  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 12:59:06.595  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:06.595  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8f7757 added. We now have 2 listener(s)
09-15 12:59:06.595  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:06.596  5479  5525 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 12:59:06.596   926  3147 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-15 12:59:06.596   926  3147 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 12:59:06.596  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:06.596  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abc8244 added. We now have 3 listener(s)
09-15 12:59:06.596  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:06.599  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:06.599  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68c5f2d added. We now have 4 listener(s)
09-15 12:59:06.599  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:06.600  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:06.601  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8926c62 added. We now have 5 listener(s)
09-15 12:59:06.601  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:06.602   926  3545 D WifiService: setWifiEnabled: false pid=5479, uid=10077
09-15 12:59:06.602   926  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 12:59:06.604   926  2943 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 12:59:06.604   926  2943 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 12:59:06.604   926  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 12:59:06.604   926  2943 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 12:59:06.606  4448  4506 D BluetoothAdapterState: Current state: ON, message: 23
09-15 12:59:06.606  4448  4506 D BluetoothAdapterProperties: Setting state to 13
09-15 12:59:06.606  4448  4506 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 12:59:06.606  4448  4506 D BluetoothAdapterProperties: onBluetoothDisable()
,09-15 12:59:06.607  4448  4506 I BluetoothAdapterState: Entering PendingCommandState
09-15 12:59:06.608  4448  4510 D BluetoothAdapterProperties: Scan Mode:20
09-15 12:59:06.608  4448  4506 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 12:59:06.609  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:06.611  4448  4448 D BluetoothMapService: onReceive
09-15 12:59:06.611  4448  4448 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 12:59:06.611  4448  4448 D BluetoothMapService: STATE_TURNING_OFF
09-15 12:59:06.611  4448  4448 D BluetoothMapService: MAP Service closeService in
09-15 12:59:06.611  4448  4448 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 12:59:06.611  4448  4448 D ObexServerSockets0: shutdown(block = true)
09-15 12:59:06.612  4448  4448 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 12:59:06.613  4448  4680 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 12:59:06.613  4448  4448 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 12:59:06.613  4448  4681 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 12:59:06.614  4448  4448 I BtOppRfcommListener: stopping Accept Thread
09-15 12:59:06.614   926  2943 E native  : do suspend true
09-15 12:59:06.614  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.614  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 12:59:06.615  4448  4657 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 12:59:06.615  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.615  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.615  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:59:06.615  4448  5135 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 12:59:06.615  4448  5135 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 12:59:06.621  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.624  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.627  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 12:59:06.627  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 12:59:06.629  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.629  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 12:59:06.631  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.633  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.636  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.637   926   939 I ActivityManager: Start proc 5532:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-15 12:59:06.638   926  5180 D DhcpClient: Clearing IP address
09-15 12:59:06.638   505   920 D CommandListener: Clearing all IP addresses on wlan0
09-15 12:59:06.640  4448  4448 D HeadsetService: Received stop request...Stopping profile...
09-15 12:59:06.641   926   926 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:06.641   926   926 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:06.641  3523  3781 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:06.642  3134  3310 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:06.642   926   926 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:06.642  3134  3134 D HeadsetProfile: Bluetooth service disconnected
09-15 12:59:06.643  4448  4448 D A2dpService: Received stop request...Stopping profile...
09-15 12:59:06.644   505   920 D CommandListener: Setting iface cfg
09-15 12:59:06.645  4448  4662 D A2dpStateMachine: Exit Disconnected: -1
09-15 12:59:06.646   926   926 D BluetoothA2dp: Proxy object disconnected
09-15 12:59:06.647  3134  3134 D BluetoothA2dp: Proxy object disconnected
09-15 12:59:06.647  4448  4448 D HidService: Received stop request...Stopping profile...
09-15 12:59:06.647  4448  4448 D HidService: Stopping Bluetooth HidService
09-15 12:59:06.648  3134  3134 D BluetoothInputDevice: Proxy object disconnected
09-15 12:59:06.648  3134  3134 D HidProfile: Bluetooth service disconnected
09-15 12:59:06.648  4448  4448 D HealthService: Received stop request...Stopping profile...
09-15 12:59:06.649  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.649  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:06.649  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.649  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 12:59:06.650  3597  5231 V NativeCrypto: Read error: ssl=0x7f8d252700: I/O error during system call, Connection timed out
09-15 12:59:06.651  3597  5231 V NativeCrypto: SSL shutdown failed: ssl=0x7f8d252700: I/O error during system call, Broken pipe
09-15 12:59:06.653   926   936 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-15 12:59:06.654   926  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 12:59:06.654   926  2945 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-15 12:59:06.655   926  5178 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-15 12:59:06.656  4448  4448 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 12:59:06.656  4448  4448 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 12:59:06.657  4448  4448 D PanService: Received stop request...Stopping profile...
09-15 12:59:06.657  4448  4510 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 12:59:06.657  4448  4654 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-15 12:59:06.657  4448  4654 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:06.657  4448  4654 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:06.658  4448  4510 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 12:59:06.658   926   926 D RttService: SCAN_AVAILABLE : 1
09-15 12:59:06.658   926  5178 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-15 12:59:06.658   926  3052 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-15 12:59:06.659   592   592 E Parcel  : Reading a NULL string not supported here.
,09-15 12:59:06.660  3134  3134 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 12:59:06.660  3134  3134 D PanProfile: Bluetooth service disconnected
09-15 12:59:06.660  4448  4448 D BluetoothMapService: Received stop request...Stopping profile...
09-15 12:59:06.660  4448  4448 D BluetoothMapService: stop()
,09-15 12:59:06.660  4448  4448 D BluetoothMapAppObserver: deinitObservers()
09-15 12:59:06.660  4448  4448 D BluetoothMapAppObserver: removeReceiver()
09-15 12:59:06.663  4448  4448 D SapService: Received stop request...Stopping profile...
09-15 12:59:06.663  4448  4448 V SapService: stop()
,09-15 12:59:06.664   926  2945 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-15 12:59:06.667  3490  3642 W QCNEJ   : |CORE| network lost: 100
09-15 12:59:06.668  3490  3642 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 12:59:06.669   926  5181 D DhcpClient: Receive thread stopped
09-15 12:59:06.669  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.670  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:06.670  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.670  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:06.672  4448  4510 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-15 12:59:06.672  4448  4654 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:06.672  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.672  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:06.672  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.672  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:06.672  4448  4654 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:06.672  4448  4654 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 12:59:06.672  4448  4654 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-15 12:59:06.672  4448  4654 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 12:59:06.672  4448  4448 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 12:59:06.672  4448  4654 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 12:59:06.672  4448  4510 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 12:59:06.672  4448  4448 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 12:59:06.673  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.674  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:06.674  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.674  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:06.674  4448  4448 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-15 12:59:06.674  4448  4510 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 12:59:06.674  4448  4448 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 12:59:06.675  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.675  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:06.675  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.675  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:06.675  4448  4448 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 12:59:06.675  4448  4448 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 12:59:06.677  4448  4448 D BluetoothMapService: MAP Service closeService in
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isTurningOn()=false
,09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 12:59:06.677  4448  4448 D BluetoothMapService: cleanup()
09-15 12:59:06.677  4448  4448 D BluetoothMapService: MAP Service closeService in
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:06.677  4448  4448 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:06.678  4448  4506 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 12:59:06.678  4448  4506 D BluetoothAdapterProperties: Setting state to 15
09-15 12:59:06.678  4448  4506 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-15 12:59:06.680  3134  3148 D BluetoothPan: onBluetoothStateChange on: false
09-15 12:59:06.680  4448  4506 I BluetoothAdapterState: Entering BleOnState
09-15 12:59:06.680  3523  3551 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:06.681   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:06.681  3134  3310 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 12:59:06.682  3134  3674 D BluetoothMap: onBluetoothStateChange: up=false
09-15 12:59:06.682  3134  3134 D BluetoothMap: Proxy object disconnected
09-15 12:59:06.682  3134  3134 D MapProfile: Bluetooth service disconnected
09-15 12:59:06.683   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:06.683  3134  3310 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:06.683  3134  3148 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 12:59:06.684  3134  3146 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 12:59:06.685   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 12:59:06.685   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:06.685  4448  4506 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 12:59:06.686  4448  4506 D BluetoothAdapterProperties: Setting state to 16
09-15 12:59:06.686  4448  4506 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 12:59:06.686  4448  4506 D BluetoothAdapterProperties: onBleDisable
09-15 12:59:06.686  4448  4506 I BluetoothAdapterState: Entering PendingCommandState
,09-15 12:59:06.687  4448  4507 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 12:59:06.687  5532  5532 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-15 12:59:06.689  4448  4654 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 12:59:06.689  4448  4654 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:06.689  4448  4510 D BluetoothAdapterProperties: Scan Mode:20
,09-15 12:59:06.690   926  2943 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-15 12:59:06.692  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:06.692  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:06.693  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.693  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:06.695  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:06.696  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:06.696   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-15 12:59:06.698  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.698  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:06.700  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.701   926  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 12:59:06.701  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.701   926  2943 E native  : do suspend true
,09-15 12:59:06.704  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 12:59:06.714  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 12:59:06.715   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e233688:true
,09-15 12:59:06.722   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 12:59:06.723   505   920 D CommandListener: Clearing all IP addresses on wlan0
09-15 12:59:06.723   505   920 D TetherController: Setting IP forward enable = 0
09-15 12:59:06.724   926  2945 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 12:59:06.724   926  2945 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 12:59:06.727   926  3531 I ActivityManager: Start proc 5553:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 12:59:06.731   926  2943 D DhcpClient: doQuit
09-15 12:59:06.731   926  2943 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 12:59:06.731   926  5180 D DhcpClient: onQuitting
,09-15 12:59:06.732  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.732  3622  3622 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 12:59:06.732   926   943 D Tethering: MasterInitialState.processMessage what=3
09-15 12:59:06.732  4789  4789 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-15 12:59:06.736  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:06.736  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:06.737  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 12:59:06.737  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:06.741  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:06.741  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:06.742  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:06.742  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:06.743  4882  4896 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 12:59:06.743  4882  4896 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 12:59:06.743  4882  4896 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 12:59:06.743  4882  4896 E SarControlService: no key has been found,reset the power
09-15 12:59:06.743  4882  4922 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 12:59:06.743  4882  4922 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 12:59:06.743  4882  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 12:59:06.744  4910  4910 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-15 12:59:06.744  4910  4910 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 12:59:06.745  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:06.745  4882  4922 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 12:59:06.745  4882  4922 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 12:59:06.745  4882  4922 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-15 12:59:06.746  4910  4910 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 12:59:06.746  4910  4910 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-15 12:59:06.750  4910  4924 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b96a5f9 HexData = [00000000ea03000000000000ffffffff]
,09-15 12:59:06.750  4910  4924 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 12:59:06.750  4910  4924 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 12:59:06.751  4910  4910 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 12:59:06.751  4882  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 12:59:06.757  4910  4924 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b96a5f9 HexData = [00000000eb03000000000000ffffffff]
,09-15 12:59:06.757  4910  4924 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 12:59:06.757  4910  4924 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 12:59:06.757  4910  4910 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 12:59:06.757  4882  4892 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-15 12:59:06.758  3622  3622 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 12:59:06.762  3622  3622 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 12:59:06.763  5532  5532 D LocalBluetoothProfileManager: Adding local MAP profile
,09-15 12:59:06.772  5532  5532 D BluetoothMap: Create BluetoothMap proxy object
,09-15 12:59:06.783  5532  5532 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 12:59:06.785  5553  5553 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 12:59:06.789  3622  3622 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 12:59:06.797  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,09-15 12:59:06.802   926  3147 I ActivityManager: Killing 5218:com.android.chrome/u0a39 (adj 15): empty #17
,09-15 12:59:06.806  3622  3622 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 12:59:06.835  4294  4294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 12:59:06.835   926  2943 D wifi    : In wifi stop Hal
09-15 12:59:06.836   926  2943 D wifi    : halHandle = 0x7f8cd38440, mVM = 0x7fa848d140, mCls = 0x100b66
09-15 12:59:06.836   926  3616 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 12:59:06.836   926  3616 D WifiHAL : Got a signal to exit!!!
09-15 12:59:06.836   926  3616 I WifiHAL : Exit wifi_event_loop
09-15 12:59:06.837   926  2943 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 12:59:06.837   926  2943 E WifiHAL : Event processing terminated
09-15 12:59:06.837   926  2943 D wifi    : In wifi cleaned up handler
,09-15 12:59:06.837   926  2943 I WifiHAL : Internal cleanup completed
09-15 12:59:06.837  3465  4008 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 12:59:06.839  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:06.840  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:06.860   926  3616 D wifi    : set interface wlan0 flags (DOWN)
,09-15 12:59:06.860   926  2943 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 12:59:06.895  4448  4510 I bt_hci  : shut_down
,09-15 12:59:06.898  4448  4516 D bt_hwcfg: hw_epilog_process
,09-15 12:59:06.899  4448  4516 I bt_vendor: low_power_mode_cb
,09-15 12:59:06.901  4448  4516 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 12:59:06.901  4448  4516 I bt_vendor: epilog_cb
09-15 12:59:06.901  4448  4516 I bt_hci  : epilog_finished_callback
,09-15 12:59:06.903  4448  4510 I bt_hci_h4: hal_close
,09-15 12:59:06.904  4448  4510 I bt_userial_vendor: device fd = 54 close
,09-15 12:59:06.969  5553  5553 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 12:59:06.969  5553  5553 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.969  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.970  5553  5553 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.970  5553  5553 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.970  5553  5553 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.970  5553  5553 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.970  5553  5553 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.970  5553  5553 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:06.970  5553  5553 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:06.975  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 12:59:06.980  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 12:59:06.980  5532  5532 D DockEventReceiver: finishStartingService: stopping service
09-15 12:59:06.984   926  3147 I ActivityManager: Killing 4856:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 12:59:07.011  4448  4507 D bt_stack_manager: event_shut_down_stack finished.
09-15 12:59:07.011  4448  4506 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-15 12:59:07.013  4448  4506 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 12:59:07.013  4448  4448 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 12:59:07.013  4448  4448 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 12:59:07.013  4448  4448 D BtGatt.GattService: stop()
09-15 12:59:07.013  4448  4448 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 12:59:07.015  4448  4448 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:07.015  4448  4448 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:07.015  4448  4448 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:07.015  4448  4448 V BluetoothAdapterState: isBleTurningOff()=true
09-15 12:59:07.016  4448  4506 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 12:59:07.016  4448  4506 D BluetoothAdapterProperties: Setting state to 10
09-15 12:59:07.016  4448  4506 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 12:59:07.016  4448  4506 I BluetoothAdapterState: Entering OffState
09-15 12:59:07.017  3909  3909 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-15 12:59:07.018   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-15 12:59:07.026  4448  4448 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 12:59:07.026  4448  4448 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 12:59:07.026  4448  4448 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 12:59:07.027  4448  4507 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-15 12:59:07.034  4448  4448 I art     : System.exit called, status: 0
09-15 12:59:07.034  4448  4448 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-15 12:59:07.043  3909  5203 I iu.UploadsManager: num queued entries: 0
09-15 12:59:07.043  3909  5203 I iu.UploadsManager: num updated entries: 0
09-15 12:59:07.044  3909  5203 I iu.SyncManager: NEXT; no task
09-15 12:59:07.046  3909  3909 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-15 12:59:07.047  3909  3909 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 12:59:07.059   926   936 I ActivityManager: Start proc 5592:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 12:59:07.063   926   943 D Tethering: InitialState.processMessage what=4
,09-15 12:59:07.066   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 12:59:07.074   926  3566 I ActivityManager: Process com.android.bluetooth (pid 4448) has died
,09-15 12:59:07.081  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 12:59:07.098  5592  5592 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 12:59:07.110  5592  5592 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 12:59:07.116  5592  5592 D SprintDMHelper: simOperator: 
09-15 12:59:07.116  5592  5592 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 12:59:07.128   926  3932 I ActivityManager: Start proc 5604:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-15 12:59:07.129   926  3932 I ActivityManager: Killing 4966:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-15 12:59:07.228  4294  5619 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 12:59:07.241   926   937 I ActivityManager: Start proc 5620:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 12:59:07.243   926   937 I ActivityManager: Killing 5252:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-15 12:59:07.285  5620  5620 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 12:59:07.295   926  3149 I ActivityManager: Killing 4520:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 12:59:07.382  5553  5580 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 12:59:07.391   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8299bc9:true
,09-15 12:59:07.540   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:07.817   505   920 E Netd    : netlink response contains error (No such file or directory)
,09-15 12:59:07.820   926  2945 E NetdConnector: NDC Command {52 network destroy 100} took too long (1091ms)
,09-15 12:59:07.820   926  2945 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-15 12:59:07.821   926  2941 E NetdConnector: NDC Command {53 bandwidth setglobalalert 2097152} took too long (1078ms)
,09-15 12:59:07.822   926  2940 E NetdConnector: NDC Command {54 bandwidth gettetherstats} took too long (756ms)
,09-15 12:59:07.822   505   920 D TetherController: Setting IP forward enable = 0
,09-15 12:59:08.542   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:09.544   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:09.617   926  3507 D WifiService: setWifiEnabled: true pid=5479, uid=10077
,09-15 12:59:09.617   926  3507 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 12:59:09.624   505   920 D SoftapController: Softap fwReload - Ok
,09-15 12:59:09.628   505   920 D CommandListener: Setting iface cfg
,09-15 12:59:09.629   505   920 D CommandListener: Trying to bring down wlan0
,09-15 12:59:09.631   505   920 D CommandListener: Clearing all IP addresses on wlan0
,09-15 12:59:09.637   926  2943 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 12:59:10.250   926  2943 D wifi    : set interface wlan0 flags (UP)
,09-15 12:59:10.254   926  2943 I WifiHAL : Initializing wifi
,09-15 12:59:10.254   926  2943 I WifiHAL : Creating socket
,09-15 12:59:10.259   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 12:59:10.262   926  2943 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 12:59:10.263   926  2943 D wifi    : Did set static halHandle = 0x7f8cd38440
,09-15 12:59:10.263   926  2943 D wifi    : halHandle = 0x7f8cd38440, mVM = 0x7fa848d140, mCls = 0x101852
09-15 12:59:10.263   926  2943 D wifi    : array field set
09-15 12:59:10.264   926  2943 I WifiNative-HAL: interface[0] = wlan0
09-15 12:59:10.265   926  5643 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547823518784
09-15 12:59:10.265   926  5643 D wifi    : waitForHalEvents called, vm = 0x7fa848d140, obj = 0x101852, env = 0x7f8d242b40
,09-15 12:59:10.345  5644  5644 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 12:59:10.366  5644  5644 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 12:59:10.367   926  2943 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 12:59:10.377  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:10.378  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:10.399  5644  5644 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 12:59:10.399  5644  5644 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 12:59:10.414   926  2943 D WifiConfigStore: Loading config and enabling all networks 
,09-15 12:59:10.415  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:10.415  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:10.415  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:10.415  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:10.417  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:10.417  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:10.417  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:10.417  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:10.425   926  2943 D WifiConfigStore: loaded 0 passpoint configs
,09-15 12:59:10.425   926  2943 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 12:59:10.426   926  2943 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 12:59:10.427   926  2943 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 12:59:10.428   926  2943 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 12:59:10.428   926  2943 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 12:59:10.428   926  2943 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 12:59:10.429   926  2943 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 12:59:10.432  4294  4294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 12:59:10.432   926  2943 D WifiNative-HAL: Setting external_sim to 1
09-15 12:59:10.433   926  2943 D wifi    : setting dfs flag to true, 0x7f8eb2bcc0
09-15 12:59:10.433   926  2943 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 12:59:10.434   926  2943 D wifi    : setting scan oui 0x7f8eb2bcc0
09-15 12:59:10.434   926  2943 D WifiHAL : Sending mac address OUI
,09-15 12:59:10.448   926  2943 E native  : do suspend true
,09-15 12:59:10.454   926  2943 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 12:59:10.454   926   926 D RttService: SCAN_AVAILABLE : 3
,09-15 12:59:10.454   505   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 12:59:10.454   926  3052 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 12:59:10.455   505   920 D CommandListener: Setting iface cfg
,09-15 12:59:10.462   926  2942 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
09-15 12:59:10.462   926  2942 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 12:59:10.472   926  2942 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 12:59:10.472   926  2942 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 12:59:10.478   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=232785 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,09-15 12:59:10.545   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:11.546   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:12.546   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 12:59:12.622   926  3545 D WifiService: setWifiEnabled: false pid=5479, uid=10077
,09-15 12:59:12.623   926  3545 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 12:59:12.630   926   926 D RttService: SCAN_AVAILABLE : 1
,09-15 12:59:12.630   926  3052 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 12:59:12.646   926  2943 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 12:59:12.647   505   920 D CommandListener: Clearing all IP addresses on wlan0
,09-15 12:59:12.651   926  2943 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 12:59:12.652  5644  5644 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 12:59:12.658  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:12.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:12.659  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:12.659  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:12.661  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:12.661  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:12.661  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:12.661  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:12.668  5644  5644 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 12:59:12.678  5644  5644 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 12:59:12.703  5644  5644 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 12:59:12.810  4294  4294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 12:59:12.810   926  2943 D wifi    : In wifi stop Hal
09-15 12:59:12.812   926  2943 D wifi    : halHandle = 0x7f8cd38440, mVM = 0x7fa848d140, mCls = 0x101852
,09-15 12:59:12.814   926  5643 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 12:59:12.814   926  5643 D WifiHAL : Got a signal to exit!!!
09-15 12:59:12.814   926  5643 I WifiHAL : Exit wifi_event_loop
09-15 12:59:12.815   926  2943 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-15 12:59:12.816   926  2943 E WifiHAL : Event processing terminated
09-15 12:59:12.816  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:12.818   926  2943 D wifi    : In wifi cleaned up handler
09-15 12:59:12.819  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:12.818   926  2943 I WifiHAL : Internal cleanup completed
09-15 12:59:12.822  3465  4008 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 12:59:12.849   926  5643 D wifi    : set interface wlan0 flags (DOWN)
,09-15 12:59:12.849   926  2943 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 12:59:13.055   926   943 D Tethering: InitialState.processMessage what=4
,09-15 12:59:13.061   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 12:59:15.661   926   943 I ActivityManager: Start proc 5648:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 12:59:15.727  5648  5648 D AdapterServiceConfig: Adding HeadsetService
,09-15 12:59:15.728  5648  5648 D AdapterServiceConfig: Adding A2dpService
09-15 12:59:15.728  5648  5648 D AdapterServiceConfig: Adding HidService
09-15 12:59:15.728  5648  5648 D AdapterServiceConfig: Adding HealthService
09-15 12:59:15.728  5648  5648 D AdapterServiceConfig: Adding PanService
09-15 12:59:15.728  5648  5648 D AdapterServiceConfig: Adding GattService
09-15 12:59:15.728  5648  5648 D AdapterServiceConfig: Adding BluetoothMapService
,09-15 12:59:15.729  5648  5648 D AdapterServiceConfig: Adding SapService
,09-15 12:59:15.742   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67228df:true
,09-15 12:59:15.742  5648  5648 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 12:59:15.745  5648  5648 I bt_bluedroid: init
09-15 12:59:15.745  5648  5660 I BluetoothAdapterState: Entering OffState
,09-15 12:59:15.746  5648  5661 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 12:59:15.747  5648  5661 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 12:59:15.747  5648  5661 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 12:59:15.747  5648  5661 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 12:59:15.747  5648  5648 I bt_bluedroid: get_profile_interface socket
,09-15 12:59:15.749  5648  5648 I bt_bluedroid: get_profile_interface sdp
,09-15 12:59:15.749  5648  5664 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 12:59:15.751  5648  5664 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 12:59:15.753  5648  5659 I bt_bluedroid: config_hci_snoop_log
,09-15 12:59:15.754   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 12:59:15.758  5648  5660 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 12:59:15.758  5648  5660 D BluetoothAdapterProperties: Setting state to 14
09-15 12:59:15.758  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 12:59:15.760  5648  5660 D BluetoothBondStateMachine: make
,09-15 12:59:15.762  5648  5665 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 12:59:15.765  5648  5660 I BluetoothAdapterState: Entering PendingCommandState
,09-15 12:59:15.765  5648  5648 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 12:59:15.767  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:15.768  5648  5648 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 12:59:15.768  5648  5648 D BtGatt.GattService: Received start request. Starting profile...
09-15 12:59:15.768  5648  5648 D BtGatt.GattService: start()
09-15 12:59:15.768  5648  5648 I bt_bluedroid: get_profile_interface gatt
09-15 12:59:15.769  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:15.769  5648  5648 D BtGatt.AdvertiseManager: advertise manager created
09-15 12:59:15.773  5648  5648 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:15.773  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:15.773  5648  5648 V BluetoothAdapterState: isBleTurningOn()=true
09-15 12:59:15.773  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:15.774  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 12:59:15.775  5648  5660 I bt_bluedroid: bt_bluedroid
09-15 12:59:15.775  5648  5661 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 12:59:15.775  5648  5661 I bt_hci  : start_up
09-15 12:59:15.780  5648  5661 I bt_vendor: alloc value 0xf3c49871
09-15 12:59:15.780  5648  5661 I bt_vendor: init
09-15 12:59:15.780  5648  5661 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 12:59:15.780  5648  5661 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 12:59:15.892  5648  5661 D bt_hci  : start_up starting async portion
,09-15 12:59:15.893  5648  5668 I bt_hci  : event_finish_startup
09-15 12:59:15.893  5648  5668 I bt_hci_h4: hal_open
09-15 12:59:15.893  5648  5668 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 12:59:15.897  5648  5668 I bt_userial_vendor: device fd = 54 open
,09-15 12:59:15.889  5669  5669 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 12:59:15.910  5648  5668 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 12:59:15.913  5648  5668 D bt_hwcfg: Chipset BCM4358A3
,09-15 12:59:15.913  5648  5668 D bt_hwcfg: Target name = [BCM4358A3]
09-15 12:59:15.914  5648  5668 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 12:59:16.314  5648  5668 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 12:59:16.314  5648  5668 D bt_hwcfg: Settlement delay -- 100 ms
09-15 12:59:16.314  5648  5668 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 12:59:16.449  5648  5668 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 12:59:16.450  5648  5668 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-15 12:59:16.451  5648  5668 I bt_hwcfg: vendor lib fwcfg completed
,09-15 12:59:16.451  5648  5668 I bt_vendor: firmware callback
,09-15 12:59:16.451  5648  5668 I bt_hci  : firmware_config_callback
,09-15 12:59:16.459   926   926 E WifiNative-wlan0: set PNO failure
,09-15 12:59:16.463  5648  5671 I bt_btu  : btu_task pending for preload complete event
,09-15 12:59:16.464  5648  5671 I bt_btu_task: Bluetooth chip preload is complete
09-15 12:59:16.464  5648  5671 I bt_btu  : btu_task received preload complete event
,09-15 12:59:16.469  5648  5671 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 12:59:16.469  5648  5671 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 12:59:16.469  5648  5671 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_PAN
,09-15 12:59:16.470  5648  5671 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 12:59:16.471  5648  5671 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 12:59:16.471  5648  5671 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 12:59:16.471  5648  5671 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 12:59:16.471  5648  5671 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 12:59:16.551  5648  5671 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bc7549
09-15 12:59:16.552  5648  5671 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bc7549 
,09-15 12:59:16.567  5648  5664 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 12:59:16.568  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 12:59:16.569  5648  5664 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 12:59:16.571  5648  5664 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 12:59:16.575  5648  5664 D BluetoothAdapterProperties: Scan Mode:20
09-15 12:59:16.575  5648  5664 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 12:59:16.575  5648  5664 D bt_hci  : do_postload posting postload work item
,09-15 12:59:16.577  5648  5668 I bt_hci  : event_postload
09-15 12:59:16.577  5648  5668 I bt_vendor: sco_config_cb
09-15 12:59:16.577  5648  5668 I bt_hci  : sco_config_callback postload finished.
,09-15 12:59:16.580  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:16.583  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:16.585  5648  5668 I bt_vendor: low_power_mode_cb
09-15 12:59:16.585  5648  5664 D bt_bte_conf: Device ID record 1 : primary
,09-15 12:59:16.585  5648  5664 D bt_bte_conf:   vendorId            = 000f
09-15 12:59:16.585  5648  5664 D bt_bte_conf:   vendorIdSource      = 0001
09-15 12:59:16.585  5648  5664 D bt_bte_conf:   product             = 1200
,09-15 12:59:16.585  5648  5664 D bt_bte_conf:   version             = 1436
,09-15 12:59:16.585  5648  5664 D bt_bte_conf:   clientExecutableURL = 
,09-15 12:59:16.585  5648  5664 D bt_bte_conf:   serviceDescription  = 
09-15 12:59:16.586  5648  5664 D bt_bte_conf:   documentationURL    = 
09-15 12:59:16.586  5648  5664 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-15 12:59:16.586  5648  5661 D bt_stack_manager: event_start_up_stack finished
09-15 12:59:16.587  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 12:59:16.587  5648  5660 D BluetoothAdapterProperties: Setting state to 15
09-15 12:59:16.587  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-15 12:59:16.589  5648  5660 I BluetoothAdapterState: Entering BleOnState
,09-15 12:59:16.594  5648  5660 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 12:59:16.594  5648  5660 D BluetoothAdapterProperties: Setting state to 11
09-15 12:59:16.594  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-15 12:59:16.598  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:16.598  5648  5648 D HeadsetService: Received start request. Starting profile...
,09-15 12:59:16.600  5648  5648 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-15 12:59:16.601  5648  5648 D HeadsetStateMachine: make
,09-15 12:59:16.607  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:16.612  5648  5648 D HeadsetStateMachine: max_hf_connections = 1
,09-15 12:59:16.612  5648  5648 I bt_bluedroid: get_profile_interface handsfree
09-15 12:59:16.612  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 12:59:16.612  5648  5664 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-15 12:59:16.613  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:16.614  5648  5660 I BluetoothAdapterState: Entering PendingCommandState
09-15 12:59:16.616  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:16.617  5648  5648 D A2dpService: Received start request. Starting profile...
,09-15 12:59:16.617  5648  5648 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 12:59:16.618  5648  5648 I bt_bluedroid: get_profile_interface avrcp
,09-15 12:59:16.622  5648  5648 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 12:59:16.622  5648  5648 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 12:59:16.622  5648  5648 D A2dpStateMachine: make
09-15 12:59:16.623  5648  5648 I bt_bluedroid: get_profile_interface a2dp
,09-15 12:59:16.624  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 12:59:16.625  5648  5679 D A2dpStateMachine: Enter Disconnected: -2
,09-15 12:59:16.625  5648  5648 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 12:59:16.626  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:16.627  5532  5532 D BluetoothInputDevice: Proxy object connected
,09-15 12:59:16.627  5648  5648 D HidService: Received start request. Starting profile...
09-15 12:59:16.627  5648  5648 I bt_bluedroid: get_profile_interface hidhost
09-15 12:59:16.627  5648  5648 D HidService: setHidService(): set to: null
09-15 12:59:16.627  5648  5664 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ba856d
09-15 12:59:16.628  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 12:59:16.628  5532  5532 D HidProfile: Bluetooth service connected
09-15 12:59:16.628  5648  5648 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 12:59:16.629  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:16.629  5648  5648 D HealthService: Received start request. Starting profile...
,09-15 12:59:16.630  5648  5648 I bt_bluedroid: get_profile_interface health
09-15 12:59:16.632  5648  5648 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 12:59:16.633  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:16.633  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 12:59:16.634  5648  5648 D PanService: Received start request. Starting profile...
09-15 12:59:16.634  5648  5648 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 12:59:16.634  5648  5648 I bt_bluedroid: get_profile_interface pan
09-15 12:59:16.634  5648  5664 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 12:59:16.636  5532  5532 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 12:59:16.636  5532  5532 D PanProfile: Bluetooth service connected
09-15 12:59:16.638  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:16.639  5532  5532 D BluetoothMap: Proxy object connected
,09-15 12:59:16.639  5532  5532 D MapProfile: Bluetooth service connected
09-15 12:59:16.640  5532  5532 D BluetoothMap: getConnectedDevices()
09-15 12:59:16.640  5648  5648 D BluetoothMapService: Received start request. Starting profile...
09-15 12:59:16.640  5648  5648 D BluetoothMapService: start()
09-15 12:59:16.643  5648  5648 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-15 12:59:16.645  5648  5648 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 12:59:16.645  5648  5648 D BluetoothMapAppObserver: createReceiver()
09-15 12:59:16.646  5532  5532 D BluetoothMap: Bluetooth is Not enabled
,09-15 12:59:16.646  5648  5648 D BluetoothMapAppObserver: initObservers()
09-15 12:59:16.646  5648  5648 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 12:59:16.652  5648  5648 V SapService: SapBinder()
,09-15 12:59:16.652  5648  5648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:16.652  5648  5648 D SapService: Received start request. Starting profile...
09-15 12:59:16.652  5648  5648 V SapService: start()
,09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOff()=false
,09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:16.654  5648  5676 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOff()=false
,09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOff()=false
,09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOn()=true
,09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:16.654  5648  5648 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:16.655  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:16.656  5648  5648 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:16.656  5648  5648 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:16.656  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 12:59:16.656  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:16.656  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 12:59:16.656  5648  5660 D BluetoothAdapterProperties: ScanMode =  20
09-15 12:59:16.656  5648  5660 D BluetoothAdapterProperties: State =  11
09-15 12:59:16.657  5648  5660 D BluetoothAdapterProperties: Setting state to 12
09-15 12:59:16.657  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-15 12:59:16.657  5648  5660 I BluetoothAdapterState: Entering OnState
09-15 12:59:16.657  3134  3310 D BluetoothPan: onBluetoothStateChange on: true
,09-15 12:59:16.659  3134  3134 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 12:59:16.660  3134  3134 D PanProfile: Bluetooth service connected
09-15 12:59:16.660  5648  5664 D BluetoothAdapterProperties: Scan Mode:21
09-15 12:59:16.660  5648  5664 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 12:59:16.660  3523  3551 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:16.660   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:16.660  3134  3674 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 12:59:16.662  3134  3148 D BluetoothMap: onBluetoothStateChange: up=true
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:16.664  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:16.664  5532  5542 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 12:59:16.664  3134  3134 D BluetoothMap: Proxy object connected
09-15 12:59:16.664  3134  3134 D MapProfile: Bluetooth service connected
09-15 12:59:16.664  5532  5543 D BluetoothPan: onBluetoothStateChange on: true
09-15 12:59:16.664  3134  3134 D BluetoothMap: getConnectedDevices()
09-15 12:59:16.664   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:16.664  3134  3148 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:16.665  5532  5542 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 12:59:16.667  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:16.667  3134  3146 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 12:59:16.667  3134  3134 D BluetoothA2dp: Proxy object connected
09-15 12:59:16.668  3134  3310 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 12:59:16.669  3134  3134 D BluetoothInputDevice: Proxy object connected
09-15 12:59:16.669  3134  3134 D HidProfile: Bluetooth service connected
,09-15 12:59:16.670   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:16.671  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:16.671   926   926 D BluetoothA2dp: Proxy object connected
09-15 12:59:16.672  5648  5648 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 12:59:16.672  5532  5543 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 12:59:16.672  5648  5648 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 12:59:16.672   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:16.675  5648  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 12:59:16.677  5532  5532 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 12:59:16.677   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 12:59:16.677  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:16.678  5648  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 12:59:16.679  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:16.680  5648  5648 D ObexServerSockets: Succeed to create listening sockets 
09-15 12:59:16.680  5648  5648 D ObexServerSockets0: startAccept()
09-15 12:59:16.680  5648  5648 D ObexServerSockets0: prepareForNewConnect()
09-15 12:59:16.680  5532  5532 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-15 12:59:16.681  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:16.682  5648  5648 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 12:59:16.682  5648  5648 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-15 12:59:16.683  5648  5648 D BluetoothMapService: onReceive
09-15 12:59:16.683  5648  5648 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-15 12:59:16.683  5648  5648 D BluetoothMapService: STATE_ON
09-15 12:59:16.683  5648  5687 D ObexServerSockets0: Accepting socket connection...
09-15 12:59:16.684  5648  5688 D ObexServerSockets0: Accepting socket connection...
,09-15 12:59:16.685  5648  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 12:59:16.687  5648  5689 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-15 12:59:16.687  5648  5689 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 12:59:16.690  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 12:59:16.692  5532  5532 D BluetoothA2dp: Proxy object connected
,09-15 12:59:16.696  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 12:59:16.697  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,09-15 12:59:16.702  3134  3134 D BluetoothPbap: Proxy object connected
,09-15 12:59:16.702  3134  3134 D PbapServerProfile: Bluetooth service connected
09-15 12:59:16.703  5532  5532 D BluetoothPbap: Proxy object connected
09-15 12:59:16.703  5532  5532 D PbapServerProfile: Bluetooth service connected
,09-15 12:59:16.708  5648  5648 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 12:59:16.708  5648  5648 D ObexServerSockets0: prepareForNewConnect()
,09-15 12:59:16.710  5648  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 12:59:16.723  5648  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 12:59:16.724  5648  5697 I BtOppRfcommListener: Accept thread started.
,09-15 12:59:16.761   926   926 D BluetoothHeadset: Proxy object connected
,09-15 12:59:16.761   926   926 D BluetoothHeadset: Proxy object connected
09-15 12:59:16.762  3523  3546 D BluetoothHeadset: Proxy object connected
,09-15 12:59:16.762  3134  3310 D BluetoothHeadset: Proxy object connected
,09-15 12:59:16.762  3134  3134 D HeadsetProfile: Bluetooth service connected
09-15 12:59:16.762   926   926 D BluetoothHeadset: Proxy object connected
,09-15 12:59:16.765   926   943 D BluetoothHeadset: Proxy object connected
09-15 12:59:16.765  3134  3148 D BluetoothHeadset: Proxy object connected
09-15 12:59:16.765  3134  3134 D HeadsetProfile: Bluetooth service connected
,09-15 12:59:16.772   926   943 D BluetoothHeadset: Proxy object connected
,09-15 12:59:16.784  5532  5543 D BluetoothHeadset: Proxy object connected
,09-15 12:59:16.785  5532  5532 D HeadsetProfile: Bluetooth service connected
,09-15 12:59:17.547   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:18.548   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:18.640  5648  5660 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 12:59:18.640  5648  5660 D BluetoothAdapterProperties: Setting state to 13
,09-15 12:59:18.640  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 12:59:18.641  5648  5660 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 12:59:18.645  5648  5660 I BluetoothAdapterState: Entering PendingCommandState
,09-15 12:59:18.651  5648  5648 D BluetoothMapService: onReceive
09-15 12:59:18.651  5648  5648 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 12:59:18.651  5648  5648 D BluetoothMapService: STATE_TURNING_OFF
09-15 12:59:18.652  5648  5648 D BluetoothMapService: MAP Service closeService in
09-15 12:59:18.652  5648  5648 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 12:59:18.652  5648  5648 D ObexServerSockets0: shutdown(block = true)
09-15 12:59:18.653  5648  5687 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-15 12:59:18.653  5648  5648 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 12:59:18.654  5648  5648 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 12:59:18.654  5648  5673 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 12:59:18.654  5648  5688 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 12:59:18.657  5648  5664 D BluetoothAdapterProperties: Scan Mode:20
09-15 12:59:18.658  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 12:59:18.658  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:18.658  5648  5648 I BtOppRfcommListener: stopping Accept Thread
,09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:18.658  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:18.658  5648  5697 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 12:59:18.659  5648  5697 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 12:59:18.659  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:18.660  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:18.666  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:18.666  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:18.667  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 12:59:18.669  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 12:59:18.669  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:18.670  5648  5648 D HeadsetService: Received stop request...Stopping profile...
09-15 12:59:18.671  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:18.673  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:18.677   926   926 D BluetoothHeadset: Proxy object disconnected
,09-15 12:59:18.677   926   926 D BluetoothHeadset: Proxy object disconnected
,09-15 12:59:18.677  3523  3781 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:18.678  5648  5648 D A2dpService: Received stop request...Stopping profile...
09-15 12:59:18.678  5648  5679 D A2dpStateMachine: Exit Disconnected: -1
09-15 12:59:18.678  5532  5532 D DockEventReceiver: finishStartingService: stopping service
09-15 12:59:18.678  3134  3148 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:18.678   926   926 D BluetoothHeadset: Proxy object disconnected
09-15 12:59:18.679  5532  5543 D BluetoothHeadset: Proxy object disconnected
,09-15 12:59:18.680   926   926 D BluetoothA2dp: Proxy object disconnected
09-15 12:59:18.680  5648  5648 D HidService: Received stop request...Stopping profile...
09-15 12:59:18.680  5648  5648 D HidService: Stopping Bluetooth HidService
09-15 12:59:18.680  5532  5532 D HeadsetProfile: Bluetooth service disconnected
09-15 12:59:18.681  5648  5648 D HealthService: Received stop request...Stopping profile...
09-15 12:59:18.682  5532  5532 D BluetoothA2dp: Proxy object disconnected
09-15 12:59:18.683  5532  5532 D BluetoothInputDevice: Proxy object disconnected
09-15 12:59:18.683  5532  5532 D HidProfile: Bluetooth service disconnected
09-15 12:59:18.685  3134  3134 D HeadsetProfile: Bluetooth service disconnected
09-15 12:59:18.686  3134  3134 D BluetoothA2dp: Proxy object disconnected
09-15 12:59:18.686  5648  5648 D PanService: Received stop request...Stopping profile...
09-15 12:59:18.686  3134  3134 D BluetoothInputDevice: Proxy object disconnected
,09-15 12:59:18.686  3134  3134 D HidProfile: Bluetooth service disconnected
09-15 12:59:18.686  3134  3134 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 12:59:18.686  3134  3134 D PanProfile: Bluetooth service disconnected
09-15 12:59:18.686  5532  5532 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 12:59:18.687  5532  5532 D PanProfile: Bluetooth service disconnected
09-15 12:59:18.688  5648  5648 D BluetoothMapService: Received stop request...Stopping profile...
09-15 12:59:18.688  5648  5648 D BluetoothMapService: stop()
09-15 12:59:18.689  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 12:59:18.690  5648  5648 D BluetoothMapAppObserver: deinitObservers()
09-15 12:59:18.690  5648  5648 D BluetoothMapAppObserver: removeReceiver()
,09-15 12:59:18.693  3134  3134 D BluetoothMap: Proxy object disconnected
09-15 12:59:18.693  3134  3134 D MapProfile: Bluetooth service disconnected
09-15 12:59:18.693  5532  5532 D BluetoothMap: Proxy object disconnected
09-15 12:59:18.693  5532  5532 D MapProfile: Bluetooth service disconnected
09-15 12:59:18.693  5648  5648 D SapService: Received stop request...Stopping profile...
09-15 12:59:18.693  5648  5648 V SapService: stop()
09-15 12:59:18.694  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.695  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.695  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 12:59:18.695  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 12:59:18.696  5648  5648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 12:59:18.696  5648  5648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 12:59:18.696  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-15 12:59:18.697  5648  5671 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:18.697  5648  5671 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:18.697  5648  5671 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:18.697  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.697  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.697  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:18.697  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 12:59:18.698  5648  5664 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-15 12:59:18.699  5648  5671 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-15 12:59:18.699  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.699  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.699  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:18.699  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:18.699  5648  5671 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:18.699  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 12:59:18.699  5648  5648 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 12:59:18.699  5648  5671 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 12:59:18.699  5648  5648 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-15 12:59:18.699  5648  5671 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 12:59:18.699  5648  5671 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 12:59:18.699  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.699  5648  5671 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:18.700  5648  5648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-15 12:59:18.700  5648  5664 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 12:59:18.700  5648  5664 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 12:59:18.700  5648  5648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:18.700  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:18.701  5648  5648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 12:59:18.701  5648  5648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 12:59:18.703  3134  3134 D BluetoothPbap: Proxy object disconnected
09-15 12:59:18.703  3134  3134 D PbapServerProfile: Bluetooth service disconnected
09-15 12:59:18.703  5532  5532 D BluetoothPbap: Proxy object disconnected
09-15 12:59:18.703  5532  5532 D PbapServerProfile: Bluetooth service disconnected
09-15 12:59:18.703  5648  5648 D BluetoothMapService: MAP Service closeService in
09-15 12:59:18.703  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.703  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.703  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:18.703  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:18.704  5648  5648 D BluetoothMapService: cleanup()
09-15 12:59:18.704  5648  5648 D BluetoothMapService: MAP Service closeService in
09-15 12:59:18.704  5648  5648 V BluetoothAdapterState: isTurningOff()=true
09-15 12:59:18.704  5648  5648 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:18.704  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:18.704  5648  5648 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:18.704  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 12:59:18.704  5648  5660 D BluetoothAdapterProperties: Setting state to 15
09-15 12:59:18.704  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 12:59:18.705  3134  3310 D BluetoothPan: onBluetoothStateChange on: false
09-15 12:59:18.706  5648  5660 I BluetoothAdapterState: Entering BleOnState
,09-15 12:59:18.706  3523  3551 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:18.706   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:18.706  3134  3148 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 12:59:18.709  3134  3146 D BluetoothMap: onBluetoothStateChange: up=false
,09-15 12:59:18.710  5532  5701 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 12:59:18.711  5532  5542 D BluetoothPan: onBluetoothStateChange on: false
09-15 12:59:18.711  5532  5543 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 12:59:18.713   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:18.713  3134  3674 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:18.713  5532  5701 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 12:59:18.714  3134  3310 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-15 12:59:18.714  3134  3148 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 12:59:18.715   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 12:59:18.715  5532  5542 D BluetoothMap: onBluetoothStateChange: up=false
09-15 12:59:18.715   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 12:59:18.715  5532  5543 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 12:59:18.716  5648  5660 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 12:59:18.716  5648  5660 D BluetoothAdapterProperties: Setting state to 16
09-15 12:59:18.716  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 12:59:18.716  5648  5660 D BluetoothAdapterProperties: onBleDisable
09-15 12:59:18.716  5648  5660 I BluetoothAdapterState: Entering PendingCommandState
,09-15 12:59:18.717  5648  5661 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 12:59:18.718  5648  5664 D BluetoothAdapterProperties: Scan Mode:20
09-15 12:59:18.719  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 12:59:18.719  5648  5671 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 12:59:18.719  5648  5671 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 12:59:18.720  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:18.722  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:18.724  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:18.724  5532  5532 D DockEventReceiver: finishStartingService: stopping service
09-15 12:59:18.725  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 12:59:18.726  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:18.927  5648  5664 I bt_hci  : shut_down
,09-15 12:59:18.931  5648  5668 D bt_hwcfg: hw_epilog_process
,09-15 12:59:18.931  5648  5668 I bt_vendor: low_power_mode_cb
,09-15 12:59:18.934  5648  5668 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 12:59:18.934  5648  5668 I bt_vendor: epilog_cb
09-15 12:59:18.934  5648  5668 I bt_hci  : epilog_finished_callback
,09-15 12:59:18.936  5648  5664 I bt_hci_h4: hal_close
,09-15 12:59:18.936  5648  5664 I bt_userial_vendor: device fd = 54 close
,09-15 12:59:19.043  5648  5661 D bt_stack_manager: event_shut_down_stack finished.
,09-15 12:59:19.044  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 12:59:19.047  5648  5648 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 12:59:19.047  5648  5660 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 12:59:19.048  5648  5648 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 12:59:19.048  5648  5648 D BtGatt.GattService: stop()
09-15 12:59:19.048  5648  5648 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 12:59:19.051  5648  5648 V BluetoothAdapterState: isTurningOff()=false
,09-15 12:59:19.051  5648  5648 V BluetoothAdapterState: isTurningOn()=false
,09-15 12:59:19.051  5648  5648 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 12:59:19.051  5648  5648 V BluetoothAdapterState: isBleTurningOff()=true
,09-15 12:59:19.052  5648  5660 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 12:59:19.052  5648  5660 D BluetoothAdapterProperties: Setting state to 10
09-15 12:59:19.052  5648  5660 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 12:59:19.053  5648  5660 I BluetoothAdapterState: Entering OffState
09-15 12:59:19.053   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 12:59:19.064  5648  5648 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 12:59:19.064  5648  5648 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 12:59:19.064  5648  5648 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 12:59:19.065  5648  5661 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 12:59:19.069  5648  5648 I art     : System.exit called, status: 0
,09-15 12:59:19.069  5648  5648 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 12:59:19.091   926  3945 I ActivityManager: Process com.android.bluetooth (pid 5648) has died
,09-15 12:59:19.549   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:20.550   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:21.551   594   594 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 12:59:21.640  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 12:59:21.641  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 12:59:22.552   594   594 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 12:59:24.650  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 12:59:24.650  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7217eb0 added. We now have 6 listener(s)
09-15 12:59:24.651  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:59:24.654  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:24.655  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9fcc129 added. We now have 7 listener(s)
,09-15 12:59:24.655  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:24.656  5479  5525 I System.out: IsBluetoothEnabled
,09-15 12:59:24.665  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:24.695   926   943 I ActivityManager: Start proc 5706:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 12:59:24.774  5706  5706 D AdapterServiceConfig: Adding HeadsetService
,09-15 12:59:24.774  5706  5706 D AdapterServiceConfig: Adding A2dpService
09-15 12:59:24.774  5706  5706 D AdapterServiceConfig: Adding HidService
09-15 12:59:24.774  5706  5706 D AdapterServiceConfig: Adding HealthService
09-15 12:59:24.774  5706  5706 D AdapterServiceConfig: Adding PanService
09-15 12:59:24.775  5706  5706 D AdapterServiceConfig: Adding GattService
09-15 12:59:24.775  5706  5706 D AdapterServiceConfig: Adding BluetoothMapService
09-15 12:59:24.775  5706  5706 D AdapterServiceConfig: Adding SapService
,09-15 12:59:24.784   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d0241ec:true
,09-15 12:59:24.784  5706  5706 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 12:59:24.787  5706  5706 I bt_bluedroid: init
,09-15 12:59:24.787  5706  5718 I BluetoothAdapterState: Entering OffState
,09-15 12:59:24.789  5706  5719 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 12:59:24.789  5706  5719 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 12:59:24.789  5706  5719 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 12:59:24.789  5706  5719 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 12:59:24.790  5706  5706 I bt_bluedroid: get_profile_interface socket
,09-15 12:59:24.791  5706  5722 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 12:59:24.792  5706  5706 I bt_bluedroid: get_profile_interface sdp
09-15 12:59:24.793  5706  5722 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 12:59:24.796  5706  5717 I bt_bluedroid: config_hci_snoop_log
,09-15 12:59:24.797   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-15 12:59:24.801  5706  5718 D BluetoothAdapterState: Current state: OFF, message: 0
09-15 12:59:24.801  5706  5718 D BluetoothAdapterProperties: Setting state to 14
09-15 12:59:24.801  5706  5718 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 12:59:24.803  5706  5718 D BluetoothBondStateMachine: make
,09-15 12:59:24.804  5706  5723 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 12:59:24.807  5706  5718 I BluetoothAdapterState: Entering PendingCommandState
,09-15 12:59:24.808  5706  5706 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 12:59:24.810  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:24.810  5706  5706 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 12:59:24.811  5706  5706 D BtGatt.GattService: Received start request. Starting profile...
,09-15 12:59:24.811  5706  5706 D BtGatt.GattService: start()
09-15 12:59:24.811  5706  5706 I bt_bluedroid: get_profile_interface gatt
,09-15 12:59:24.813  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:24.814  5706  5706 D BtGatt.AdvertiseManager: advertise manager created
,09-15 12:59:24.818  5706  5706 V BluetoothAdapterState: isTurningOff()=false
,09-15 12:59:24.818  5706  5706 V BluetoothAdapterState: isTurningOn()=false
09-15 12:59:24.818  5706  5706 V BluetoothAdapterState: isBleTurningOn()=true
09-15 12:59:24.818  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:24.819  5706  5718 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 12:59:24.820  5706  5718 I bt_bluedroid: bt_bluedroid
09-15 12:59:24.820  5706  5719 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-15 12:59:24.820  5706  5719 I bt_hci  : start_up
,09-15 12:59:24.825  5706  5719 I bt_vendor: alloc value 0xf3c49871
,09-15 12:59:24.825  5706  5719 I bt_vendor: init
09-15 12:59:24.825  5706  5719 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 12:59:24.825  5706  5719 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 12:59:24.936  5706  5719 D bt_hci  : start_up starting async portion
09-15 12:59:24.936  5706  5726 I bt_hci  : event_finish_startup
,09-15 12:59:24.936  5706  5726 I bt_hci_h4: hal_open
09-15 12:59:24.937  5706  5726 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 12:59:24.940  5706  5726 I bt_userial_vendor: device fd = 54 open
,09-15 12:59:24.932  5727  5727 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 12:59:24.953  5706  5726 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 12:59:24.956  5706  5726 D bt_hwcfg: Chipset BCM4358A3
,09-15 12:59:24.956  5706  5726 D bt_hwcfg: Target name = [BCM4358A3]
09-15 12:59:24.956  5706  5726 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 12:59:25.357  5706  5726 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 12:59:25.358  5706  5726 D bt_hwcfg: Settlement delay -- 100 ms
09-15 12:59:25.359  5706  5726 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 12:59:25.491  5706  5726 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 12:59:25.492  5706  5726 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 12:59:25.494  5706  5726 I bt_hwcfg: vendor lib fwcfg completed
,09-15 12:59:25.494  5706  5726 I bt_vendor: firmware callback
,09-15 12:59:25.494  5706  5726 I bt_hci  : firmware_config_callback
,09-15 12:59:25.502  5706  5729 I bt_btu  : btu_task pending for preload complete event
09-15 12:59:25.502  5706  5729 I bt_btu_task: Bluetooth chip preload is complete
,09-15 12:59:25.503  5706  5729 I bt_btu  : btu_task received preload complete event
,09-15 12:59:25.509  5706  5729 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 12:59:25.510  5706  5729 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 12:59:25.511  5706  5729 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 12:59:25.511  5706  5729 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 12:59:25.511  5706  5729 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 12:59:25.511  5706  5729 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-15 12:59:25.511  5706  5729 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 12:59:25.593  5706  5729 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bc7549
,09-15 12:59:25.594  5706  5729 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bc7549 
,09-15 12:59:25.609  5706  5722 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 12:59:25.610  5706  5722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 12:59:25.611  5706  5722 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 12:59:25.613  5706  5722 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 12:59:25.616  5706  5722 D BluetoothAdapterProperties: Scan Mode:20
,09-15 12:59:25.617  5706  5722 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 12:59:25.617  5706  5722 D bt_hci  : do_postload posting postload work item
09-15 12:59:25.618  5706  5726 I bt_hci  : event_postload
09-15 12:59:25.618  5706  5726 I bt_vendor: sco_config_cb
09-15 12:59:25.618  5706  5726 I bt_hci  : sco_config_callback postload finished.
,09-15 12:59:25.621  5706  5722 D bt_bte_conf: Device ID record 1 : primary
09-15 12:59:25.621  5706  5722 D bt_bte_conf:   vendorId            = 000f
09-15 12:59:25.621  5706  5722 D bt_bte_conf:   vendorIdSource      = 0001
09-15 12:59:25.621  5706  5722 D bt_bte_conf:   product             = 1200
09-15 12:59:25.621  5706  5722 D bt_bte_conf:   version             = 1436
09-15 12:59:25.621  5706  5722 D bt_bte_conf:   clientExecutableURL = 
09-15 12:59:25.622  5706  5722 D bt_bte_conf:   serviceDescription  = 
09-15 12:59:25.622  5706  5722 D bt_bte_conf:   documentationURL    = 
09-15 12:59:25.622  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:25.622  5706  5722 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 12:59:25.622  5706  5719 D bt_stack_manager: event_start_up_stack finished
09-15 12:59:25.624  5706  5718 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 12:59:25.624  5706  5718 D BluetoothAdapterProperties: Setting state to 15
09-15 12:59:25.624  5706  5718 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-15 12:59:25.626  5706  5718 I BluetoothAdapterState: Entering BleOnState
,09-15 12:59:25.629  5706  5726 I bt_vendor: low_power_mode_cb
09-15 12:59:25.630  5706  5718 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 12:59:25.630  5706  5718 D BluetoothAdapterProperties: Setting state to 11
09-15 12:59:25.630  5706  5718 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 12:59:25.640  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:25.641  5706  5706 D HeadsetService: Received start request. Starting profile...
09-15 12:59:25.641  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:25.644  5706  5706 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 12:59:25.644  5706  5706 D HeadsetStateMachine: make
,09-15 12:59:25.651  5706  5718 I BluetoothAdapterState: Entering PendingCommandState
,09-15 12:59:25.654  5706  5706 D HeadsetStateMachine: max_hf_connections = 1
,09-15 12:59:25.654  5706  5706 I bt_bluedroid: get_profile_interface handsfree
09-15 12:59:25.655  5706  5722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 12:59:25.655  5706  5722 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-15 12:59:25.660  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:25.660  5706  5706 D A2dpService: Received start request. Starting profile...
09-15 12:59:25.661  5706  5706 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 12:59:25.661  5706  5706 I bt_bluedroid: get_profile_interface avrcp
09-15 12:59:25.667  5706  5706 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-15 12:59:25.667  5706  5706 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 12:59:25.667  5706  5706 D A2dpStateMachine: make
09-15 12:59:25.668  5706  5706 I bt_bluedroid: get_profile_interface a2dp
09-15 12:59:25.669  5706  5722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 12:59:25.670  5706  5737 D A2dpStateMachine: Enter Disconnected: -2
,09-15 12:59:25.671  5706  5706 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 12:59:25.671  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:25.672  5706  5706 D HidService: Received start request. Starting profile...
09-15 12:59:25.672  5706  5706 I bt_bluedroid: get_profile_interface hidhost
09-15 12:59:25.673  5706  5706 D HidService: setHidService(): set to: null
09-15 12:59:25.673  5706  5722 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ba856d
09-15 12:59:25.673  5706  5722 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 12:59:25.673  5706  5706 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 12:59:25.674  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:25.674  5706  5706 D HealthService: Received start request. Starting profile...
,09-15 12:59:25.676  5706  5706 I bt_bluedroid: get_profile_interface health
09-15 12:59:25.677  5706  5706 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 12:59:25.677  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:25.678  5706  5706 D PanService: Received start request. Starting profile...
,09-15 12:59:25.678  5706  5706 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 12:59:25.678  5706  5706 I bt_bluedroid: get_profile_interface pan
09-15 12:59:25.679  5706  5722 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 12:59:25.682  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
09-15 12:59:25.682  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 12:59:25.683  5706  5706 D BluetoothMapService: Received start request. Starting profile...
09-15 12:59:25.683  5706  5706 D BluetoothMapService: start()
,09-15 12:59:25.685  5706  5706 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 12:59:25.686  5706  5706 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 12:59:25.686  5706  5706 D BluetoothMapAppObserver: createReceiver()
09-15 12:59:25.688  5706  5706 D BluetoothMapAppObserver: initObservers()
09-15 12:59:25.688  5706  5706 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 12:59:25.695  5706  5706 V SapService: SapBinder()
09-15 12:59:25.695  5706  5706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:25.696  5706  5706 D SapService: Received start request. Starting profile...
09-15 12:59:25.696  5706  5706 V SapService: start()
,09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isTurningOff()=false
,09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:25.699  5706  5735 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:25.699  5706  5706 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.700  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 12:59:25.701  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:25.702  5706  5706 V BluetoothAdapterState: isTurningOff()=false
09-15 12:59:25.702  5706  5706 V BluetoothAdapterState: isTurningOn()=true
09-15 12:59:25.702  5706  5706 V BluetoothAdapterState: isBleTurningOn()=false
09-15 12:59:25.702  5706  5706 V BluetoothAdapterState: isBleTurningOff()=false
09-15 12:59:25.702  5706  5718 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 12:59:25.702  5706  5718 D BluetoothAdapterProperties: ScanMode =  20
09-15 12:59:25.702  5706  5718 D BluetoothAdapterProperties: State =  11
09-15 12:59:25.703  5706  5718 D BluetoothAdapterProperties: Setting state to 12
,09-15 12:59:25.703  5706  5718 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 12:59:25.704  3134  3310 D BluetoothPan: onBluetoothStateChange on: true
09-15 12:59:25.704  5706  5722 D BluetoothAdapterProperties: Scan Mode:21
09-15 12:59:25.704  5706  5722 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 12:59:25.706  5706  5718 I BluetoothAdapterState: Entering OnState
09-15 12:59:25.707  3523  3551 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:25.707   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:25.708  3134  3148 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 12:59:25.709  3134  3134 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 12:59:25.709  3134  3134 D PanProfile: Bluetooth service connected
,09-15 12:59:25.711  3134  3674 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:25.712  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:25.713  3134  3134 D BluetoothA2dp: Proxy object connected
,09-15 12:59:25.713  5532  5542 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 12:59:25.715  3134  3134 D BluetoothMap: Proxy object connected
09-15 12:59:25.715  3134  3134 D MapProfile: Bluetooth service connected
09-15 12:59:25.715  3134  3134 D BluetoothMap: getConnectedDevices()
09-15 12:59:25.715  5532  5543 D BluetoothPan: onBluetoothStateChange on: true
09-15 12:59:25.717  5532  5542 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 12:59:25.719   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:25.719  5706  5706 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 12:59:25.719  3134  3148 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:25.720  5532  5543 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 12:59:25.720  5706  5706 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-15 12:59:25.720  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:25.721  5706  5706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 12:59:25.721  5532  5532 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 12:59:25.721  5532  5532 D PanProfile: Bluetooth service connected
09-15 12:59:25.721  5532  5532 D BluetoothA2dp: Proxy object connected
09-15 12:59:25.722  3134  3146 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 12:59:25.723  5706  5706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 12:59:25.723  3134  3674 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 12:59:25.724  5706  5706 D ObexServerSockets: Succeed to create listening sockets 
09-15 12:59:25.724  5706  5706 D ObexServerSockets0: startAccept()
09-15 12:59:25.724  5706  5706 D ObexServerSockets0: prepareForNewConnect()
09-15 12:59:25.724   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 12:59:25.725   926   926 D BluetoothA2dp: Proxy object connected
09-15 12:59:25.725  5532  5701 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 12:59:25.726  5706  5706 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-15 12:59:25.726  5706  5706 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 12:59:25.726   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:25.726  5706  5744 D ObexServerSockets0: Accepting socket connection...
09-15 12:59:25.727  5532  5543 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 12:59:25.727  5706  5745 D ObexServerSockets0: Accepting socket connection...
,09-15 12:59:25.727  3134  3134 D BluetoothInputDevice: Proxy object connected
,09-15 12:59:25.727  3134  3134 D HidProfile: Bluetooth service connected
09-15 12:59:25.730  5532  5532 D BluetoothMap: Proxy object connected
09-15 12:59:25.730   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 12:59:25.730  5532  5532 D MapProfile: Bluetooth service connected
,09-15 12:59:25.730  5532  5532 D BluetoothMap: getConnectedDevices()
09-15 12:59:25.730  5706  5706 D BluetoothMapService: onReceive
09-15 12:59:25.730  5706  5706 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 12:59:25.730  5706  5706 D BluetoothMapService: STATE_ON
,09-15 12:59:25.732  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:25.732  5532  5532 D BluetoothInputDevice: Proxy object connected
09-15 12:59:25.732  5532  5532 D HidProfile: Bluetooth service connected
09-15 12:59:25.734  5706  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 12:59:25.735  5706  5747 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 12:59:25.735  5706  5747 D BluetoothSdpJni: SDP Create record success - handle: 1
09-15 12:59:25.738  5532  5532 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 12:59:25.745  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 12:59:25.747  5532  5532 D DockEventReceiver: finishStartingService: stopping service
,09-15 12:59:25.753  5532  5532 D BluetoothPbap: Proxy object connected
,09-15 12:59:25.753  5532  5532 D PbapServerProfile: Bluetooth service connected
,09-15 12:59:25.756  5706  5706 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 12:59:25.757  5706  5706 D ObexServerSockets0: prepareForNewConnect()
,09-15 12:59:25.761  5706  5751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 12:59:25.763  3134  3134 D BluetoothPbap: Proxy object connected
09-15 12:59:25.763  3134  3134 D PbapServerProfile: Bluetooth service connected
,09-15 12:59:25.777  5706  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 12:59:25.778  5706  5755 I BtOppRfcommListener: Accept thread started.
,09-15 12:59:25.809   926   926 D BluetoothHeadset: Proxy object connected
,09-15 12:59:25.809   926   926 D BluetoothHeadset: Proxy object connected
09-15 12:59:25.810  3523  3546 D BluetoothHeadset: Proxy object connected
,09-15 12:59:25.810  3134  3310 D BluetoothHeadset: Proxy object connected
09-15 12:59:25.810  3134  3134 D HeadsetProfile: Bluetooth service connected
,09-15 12:59:25.810   926   926 D BluetoothHeadset: Proxy object connected
09-15 12:59:25.811  5532  5701 D BluetoothHeadset: Proxy object connected
,09-15 12:59:25.813  5532  5532 D HeadsetProfile: Bluetooth service connected
,09-15 12:59:25.819   926   943 D BluetoothHeadset: Proxy object connected
09-15 12:59:25.820  3134  3148 D BluetoothHeadset: Proxy object connected
09-15 12:59:25.820  3134  3134 D HeadsetProfile: Bluetooth service connected
,09-15 12:59:25.827   926   943 D BluetoothHeadset: Proxy object connected
,09-15 12:59:25.827  5532  5542 D BluetoothHeadset: Proxy object connected
09-15 12:59:25.828  5532  5532 D HeadsetProfile: Bluetooth service connected
,09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:26.683  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:26.688  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:26.691  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:26.692  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22eecae added. We now have 8 listener(s)
09-15 12:59:26.692  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:59:26.698   926  3566 D WifiService: setWifiEnabled: false pid=5479, uid=10077
,09-15 12:59:26.698   926  3566 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 12:59:26.707  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:26.707   926  3945 D WifiService: setWifiEnabled: true pid=5479, uid=10077
,09-15 12:59:26.708   926  3945 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 12:59:26.714   505   920 D SoftapController: Softap fwReload - Ok
,09-15 12:59:26.718   505   920 D CommandListener: Setting iface cfg
,09-15 12:59:26.719   505   920 D CommandListener: Trying to bring down wlan0
09-15 12:59:26.721   505   920 D CommandListener: Clearing all IP addresses on wlan0
,09-15 12:59:26.726   926  2943 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 12:59:27.337   926  2943 D wifi    : set interface wlan0 flags (UP)
,09-15 12:59:27.342   926  2943 I WifiHAL : Initializing wifi
,09-15 12:59:27.342   926  2943 I WifiHAL : Creating socket
09-15 12:59:27.346   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 12:59:27.349   926  2943 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-15 12:59:27.349   926  2943 D wifi    : Did set static halHandle = 0x7f8cd38440
09-15 12:59:27.349   926  2943 D wifi    : halHandle = 0x7f8cd38440, mVM = 0x7fa848d140, mCls = 0x183e
,09-15 12:59:27.349   926  2943 D wifi    : array field set
09-15 12:59:27.350   926  2943 I WifiNative-HAL: interface[0] = wlan0
09-15 12:59:27.351   926  5760 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547823518784
09-15 12:59:27.352   926  5760 D wifi    : waitForHalEvents called, vm = 0x7fa848d140, obj = 0x183e, env = 0x7f89c885c0
,09-15 12:59:27.418  5761  5761 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 12:59:27.440  5761  5761 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 12:59:27.451  5761  5761 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 12:59:27.451  5761  5761 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 12:59:27.453   926  2943 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 12:59:27.461  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:27.470   926  2943 D WifiConfigStore: Loading config and enabling all networks 
,09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:27.475  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:27.477  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:27.483   926  2943 D WifiConfigStore: loaded 0 passpoint configs
,09-15 12:59:27.483   926  2943 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 12:59:27.484   926  2943 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 12:59:27.485   926  2943 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 12:59:27.486   926  2943 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 12:59:27.486   926  2943 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 12:59:27.486   926  2943 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-15 12:59:27.486   926  2943 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 12:59:27.490  4294  4294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 12:59:27.490   926  2943 D WifiNative-HAL: Setting external_sim to 1
09-15 12:59:27.491   926  2943 D wifi    : setting dfs flag to true, 0x7f8d72a220
09-15 12:59:27.491   926  2943 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 12:59:27.491   926  2943 D wifi    : setting scan oui 0x7f8d72a220
09-15 12:59:27.491   926  2943 D WifiHAL : Sending mac address OUI
,09-15 12:59:27.506   926  2943 E native  : do suspend true
,09-15 12:59:27.512   926  2943 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-15 12:59:27.512   926   926 D RttService: SCAN_AVAILABLE : 3
09-15 12:59:27.512   505   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 12:59:27.512   926  3052 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 12:59:27.513   505   920 D CommandListener: Setting iface cfg
,09-15 12:59:27.516   926  2942 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,09-15 12:59:27.517   926  2942 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 12:59:27.522   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=249830 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 12:59:27.523   926  2942 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 12:59:27.524   926  2942 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:27.727  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:27.733  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:27.739  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 12:59:27.740  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-15 12:59:27.744  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@93c396d Bundle[{}]
,09-15 12:59:27.745  5479  5525 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 12:59:27.745  5479  5525 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-15 12:59:27.746  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 12:59:27.747  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 12:59:27.748  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-15 12:59:27.750  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 12:59:27.757  5479  5525 I System.out: Running OutgoingSocketThread
,09-15 12:59:27.758  5479  5763 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-15 12:59:27.760  5479  5763 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42235
09-15 12:59:27.760  5479  5763 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 12:59:28.760  5479  5525 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-15 12:59:28.760  5479  5525 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-15 12:59:28.766  5479  5525 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-15 12:59:28.768  5479  5525 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-15 12:59:28.768  5479  5525 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-15 12:59:28.774  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 12:59:28.774  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6abfa4f added. We now have 2 listener(s)
09-15 12:59:28.777  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:28.777  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.778  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 12:59:28.778  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.778  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@597d5dc added. We now have 9 listener(s)
09-15 12:59:28.778  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.779  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 12:59:28.783  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:28.787  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:28.790  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:28.791  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 12:59:28.791  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.791  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30125ba added. We now have 3 listener(s)
09-15 12:59:28.793  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.793  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 12:59:28.793  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 12:59:28.794  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.794  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.794  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d7ec6b added. We now have 10 listener(s)
09-15 12:59:28.794  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:59:28.795  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:28.795  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:28.795  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:28.795  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:28.795  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.795  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.795  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 12:59:28.795  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.795  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6abfa4f removed from the list
09-15 12:59:28.796  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.796  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@597d5dc removed from the list
09-15 12:59:28.796  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:28.796  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.797  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 12:59:28.797  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.801  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.801  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.801  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.801  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@597d5dc not in the list
,09-15 12:59:28.801  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.801  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.803  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.803  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.803  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 12:59:28.803  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d7ec6b removed from the list
09-15 12:59:28.803  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.803  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.803  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.803  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.803  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30125ba removed from the list
,09-15 12:59:28.804  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 12:59:28.804  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba73c8 added. We now have 2 listener(s)
09-15 12:59:28.805  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:28.805  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.805  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.806  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.806  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5a6c61 added. We now have 9 listener(s)
09-15 12:59:28.806  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:59:28.807  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 12:59:28.809  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:28.813  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:28.814  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:28.815  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:59:28.815  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.815  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f86e447 added. We now have 3 listener(s)
,09-15 12:59:28.816  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.816  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:28.816  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 12:59:28.817  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.817  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.817  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be70474 added. We now have 10 listener(s)
09-15 12:59:28.817  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.817  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:28.817  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 12:59:28.817  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 12:59:28.817  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:28.817  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 12:59:28.818  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 12:59:28.821  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 12:59:28.821  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 12:59:28.825  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 12:59:28.826  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 12:59:28.826  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 12:59:28.830  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 12:59:28.830  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 12:59:28.830  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 12:59:28.830  5479  5525 D BluetoothAdapter: STATE_ON
,09-15 12:59:28.834  5706  5716 D BtGatt.GattService: registerClient() - UUID=283f94fb-a8ad-4af7-8d5c-0d90276e9195
,09-15 12:59:28.835  5706  5722 D BtGatt.GattService: onClientRegistered() - UUID=283f94fb-a8ad-4af7-8d5c-0d90276e9195, clientIf=5
,09-15 12:59:28.836  5479  5490 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 12:59:28.837  5706  5717 D BtGatt.GattService: start scan with filters
09-15 12:59:28.841  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 12:59:28.841  5706  5725 D BtGatt.ScanManager: handling starting scan
09-15 12:59:28.841  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 12:59:28.841  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 12:59:28.841  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 12:59:28.842  5706  5725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e4b216
,09-15 12:59:28.843  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 12:59:28.843  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 12:59:28.843  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:28.844  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 12:59:28.847  5479  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-15 12:59:28.847  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:28.847  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 12:59:28.847  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.848  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 12:59:28.848  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 12:59:28.848  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:28.848  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 12:59:28.848  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 12:59:28.848  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 12:59:28.848  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 12:59:28.848  5706  5722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 12:59:28.848  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.848  5479  5525 D BluetoothAdapter: STATE_ON
09-15 12:59:28.849  5706  5725 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 12:59:28.849  5706  5742 D BtGatt.GattService: stopScan() - queue size =1
09-15 12:59:28.850  5706  5716 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 12:59:28.850  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 12:59:28.850  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 12:59:28.850  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 12:59:28.850  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 12:59:28.850  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 12:59:28.851  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:28.851  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 12:59:28.851  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 12:59:28.851  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 12:59:28.852  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 12:59:28.853  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 12:59:28.853  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:28.853  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:28.854  5706  5722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 12:59:28.854  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.855  5706  5725 D BtGatt.ScanManager: Starting BLE batch scan
09-15 12:59:28.855  5706  5725 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 12:59:28.855  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 12:59:28.855  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:28.855  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:28.855  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.855  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.855  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:28.855  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.855  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ba73c8 removed from the list
09-15 12:59:28.855  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.855  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5a6c61 removed from the list
09-15 12:59:28.855  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:28.855  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 12:59:28.856  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.856  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.858  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.858  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.858  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.858  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5a6c61 not in the list
09-15 12:59:28.858  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 12:59:28.858  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.860  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.860  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.860  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.860  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be70474 removed from the list
09-15 12:59:28.860  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 12:59:28.860  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.860  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.860  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.860  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f86e447 removed from the list
09-15 12:59:28.861  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.861  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea9f3e0 added. We now have 2 listener(s)
09-15 12:59:28.862  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 12:59:28.863  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.863  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.863  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.863  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb4699 added. We now have 9 listener(s)
09-15 12:59:28.863  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.864  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 12:59:28.865  5706  5722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 12:59:28.865  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.867  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:28.871  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:28.871  5706  5722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 12:59:28.872  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:28.873  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:28.873  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 12:59:28.873  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.873  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a6153f added. We now have 3 listener(s)
09-15 12:59:28.874  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.874  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:28.875  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.875  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.875  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.875  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ea6e0c added. We now have 10 listener(s)
09-15 12:59:28.875  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.875  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:28.875  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.876  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:28.876  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 12:59:28.876  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 12:59:28.876  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:28.876  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 12:59:28.878  5706  5722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 12:59:28.878  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.878  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 12:59:28.878  5706  5725 D BtGatt.ScanManager: stopping BLe Batch
09-15 12:59:28.878  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 12:59:28.881  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 12:59:28.881  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 12:59:28.881  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 12:59:28.883  5706  5722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 12:59:28.883  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.883  5706  5725 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 12:59:28.885  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 12:59:28.885  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 12:59:28.885  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 12:59:28.885  5479  5525 D BluetoothAdapter: STATE_ON
,09-15 12:59:28.887  5706  5722 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 12:59:28.887  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:28.889  5706  5742 D BtGatt.GattService: registerClient() - UUID=d367bb4b-9a59-44e5-b810-dbbe16c24b7b
,09-15 12:59:28.889  5706  5722 D BtGatt.GattService: onClientRegistered() - UUID=d367bb4b-9a59-44e5-b810-dbbe16c24b7b, clientIf=5
09-15 12:59:28.890  5479  5489 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 12:59:28.890  5706  5717 D BtGatt.GattService: start scan with filters
,09-15 12:59:28.892  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 12:59:28.892  5706  5725 D BtGatt.ScanManager: handling starting scan
09-15 12:59:28.892  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 12:59:28.892  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 12:59:28.892  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 12:59:28.894  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 12:59:28.894  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 12:59:28.894  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:28.895  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 12:59:28.896  5706  5722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 12:59:28.896  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.897  5706  5725 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 12:59:28.898  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 12:59:28.898  5479  5525 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 12:59:28.898  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:28.898  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:28.898  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:28.898  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.898  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.898  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 12:59:28.898  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.898  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea9f3e0 removed from the list
09-15 12:59:28.898  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.898  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb4699 removed from the list
09-15 12:59:28.898  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:28.898  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 12:59:28.899  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.899  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 12:59:28.899  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.899  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:28.900  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.900  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.900  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.900  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb4699 not in the list
09-15 12:59:28.900  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:28.900  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 12:59:28.900  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 12:59:28.900  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 12:59:28.900  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 12:59:28.900  5479  5525 D BluetoothAdapter: STATE_ON
09-15 12:59:28.901  5706  5742 D BtGatt.GattService: stopScan() - queue size =1
09-15 12:59:28.901  5706  5722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 12:59:28.901  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.901  5706  5725 D BtGatt.ScanManager: Starting BLE batch scan
09-15 12:59:28.902  5706  5725 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 12:59:28.902  5706  5717 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 12:59:28.902  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 12:59:28.902  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 12:59:28.902  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 12:59:28.902  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 12:59:28.902  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 12:59:28.903  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 12:59:28.903  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 12:59:28.903  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 12:59:28.903  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 12:59:28.904  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.905  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.905  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.905  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.905  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ea6e0c removed from the list
,09-15 12:59:28.905  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 12:59:28.905  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.905  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.905  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.905  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:28.905  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a6153f removed from the list
09-15 12:59:28.905  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:28.905  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:28.906  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.906  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d65ef8 added. We now have 2 listener(s)
09-15 12:59:28.907  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 12:59:28.907  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.907  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.907  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.907  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c062fd1 added. We now have 9 listener(s)
09-15 12:59:28.907  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.907  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 12:59:28.909  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:28.910  5706  5722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 12:59:28.910  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:28.912  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 12:59:28.913  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 12:59:28.914  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:59:28.914  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.914  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6b6d37 added. We now have 3 listener(s)
09-15 12:59:28.915  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:28.915  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.915  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.915  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.915  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8e72a4 added. We now have 10 listener(s)
09-15 12:59:28.915  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.915  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.915  5706  5722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 12:59:28.915  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:28.915  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.915  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 12:59:28.915  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 12:59:28.916  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 12:59:28.916  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 12:59:28.917  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.918  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
0,9-15 12:59:28.918  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 12:59:28.921  5706  5722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 12:59:28.921  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.921  5706  5725 D BtGatt.ScanManager: stopping BLe Batch
,09-15 12:59:28.922  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 12:59:28.923  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 12:59:28.923  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 12:59:28.925  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 12:59:28.925  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 12:59:28.926  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 12:59:28.926  5706  5722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 12:59:28.926  5479  5525 D BluetoothAdapter: STATE_ON
09-15 12:59:28.926  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.926  5706  5725 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 12:59:28.928  5706  5717 D BtGatt.GattService: registerClient() - UUID=92d0f568-b4f8-4b20-96e2-77240c7556e9
,09-15 12:59:28.928  5706  5722 D BtGatt.GattService: onClientRegistered() - UUID=92d0f568-b4f8-4b20-96e2-77240c7556e9, clientIf=5
09-15 12:59:28.928  5479  5489 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 12:59:28.929  5706  5746 D BtGatt.GattService: start scan with filters
,09-15 12:59:28.930  5706  5722 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 12:59:28.931  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.931  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 12:59:28.932  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 12:59:28.932  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 12:59:28.932  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 12:59:28.932  5706  5725 D BtGatt.ScanManager: handling starting scan
,09-15 12:59:28.933  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 12:59:28.934  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 12:59:28.934  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 12:59:28.935  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 12:59:28.937  5706  5722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 12:59:28.937  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.937  5706  5725 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 12:59:28.939  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 12:59:28.939  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:28.939  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:28.939  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.939  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.939  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 12:59:28.939  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.939  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d65ef8 removed from the list
09-15 12:59:28.939  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 12:59:28.939  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c062fd1 removed from the list
09-15 12:59:28.939  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:28.939  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:28.940  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.940  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 12:59:28.940  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.940  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:28.941  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.941  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.941  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.941  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c062fd1 not in the list
09-15 12:59:28.941  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 12:59:28.941  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 12:59:28.941  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 12:59:28.941  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 12:59:28.941  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 12:59:28.942  5479  5525 D BluetoothAdapter: STATE_ON
09-15 12:59:28.942  5706  5722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 12:59:28.942  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.942  5706  5725 D BtGatt.ScanManager: Starting BLE batch scan
09-15 12:59:28.942  5706  5725 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 12:59:28.942  5706  5716 D BtGatt.GattService: stopScan() - queue size =1
,09-15 12:59:28.943  5706  5742 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 12:59:28.943  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 12:59:28.943  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-15 12:59:28.943  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 12:59:28.943  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 12:59:28.943  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 12:59:28.949  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 12:59:28.949  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 12:59:28.949  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 12:59:28.949  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 12:59:28.950  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 12:59:28.951  5706  5722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 12:59:28.950  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.951  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.951  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8e72a4 removed from the list
09-15 12:59:28.951  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:28.951  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 12:59:28.951  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 12:59:28.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.951  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.951  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.951  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6b6d37 removed from the list
09-15 12:59:28.952  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.952  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d921510 added. We now have 2 listener(s)
,09-15 12:59:28.954  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 12:59:28.954  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.954  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.954  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.954  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe0809 added. We now have 9 listener(s)
09-15 12:59:28.954  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 12:59:28.955  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 12:59:28.955  5706  5722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 12:59:28.956  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 12:59:28.957  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 12:59:28.962  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 12:59:28.963  5706  5722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 12:59:28.963  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.963  5706  5725 D BtGatt.ScanManager: stopping BLe Batch
,09-15 12:59:28.964  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 12:59:28.964  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 12:59:28.964  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 12:59:28.964  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f94cc2f added. We now have 3 listener(s)
09-15 12:59:28.965  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.966  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 12:59:28.966  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 12:59:28.966  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 12:59:28.966  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 12:59:28.966  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb723c added. We now have 10 listener(s)
09-15 12:59:28.966  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 12:59:28.966  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 12:59:28.966  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 12:59:28.966  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 12:59:28.966  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.966  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 12:59:28.966  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 12:59:28.966  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 12:59:28.966  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.967  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d921510 removed from the list
09-15 12:59:28.967  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.967  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe0809 removed from the list
09-15 12:59:28.967  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-15 12:59:28.967  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.967  5706  5722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 12:59:28.967  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.967  5706  5725 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 12:59:28.968  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 12:59:28.968  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.969  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.969  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.969  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.969  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe0809 not in the list
09-15 12:59:28.969  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.969  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.970  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 12:59:28.970  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 12:59:28.970  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 12:59:28.970  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb723c removed from the list
,09-15 12:59:28.970  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 12:59:28.970  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 12:59:28.970  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 12:59:28.970  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 12:59:28.970  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f94cc2f removed from the list
09-15 12:59:28.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-15 12:59:28.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 12:59:28.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 12:59:28.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 12:59:28.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 12:59:28.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 12:59:28.972  5706  5722 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 12:59:28.972  5706  5722 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 12:59:28.975  5479  5764 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
09-15 12:59:28.975  5479  5764 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-15 12:59:28.975  5479  5764 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-15 12:59:28.977  5479  5765 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
09-15 12:59:28.977  5479  5765 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-15 12:59:28.977  5479  5765 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 12:59:28.978  5479  5525 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-15 12:59:28.979  5479  5525 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-15 12:59:28.979  5479  5525 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 12:59:28.979  5479  5525 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 12:59:28.979  5479  5525 D com.test.thalitest.ThaliTestRunner: Total duration: 22588 ms
09-15 12:59:28.980  5479  5525 I jxcore-log: *Native tests were executed*
09-15 12:59:28.980  5479  5525 I jxcore-log: 
09-15 12:59:28.980  5479  5525 I jxcore-log: Total number of executed tests:  80
09-15 12:59:28.980  5479  5525 I jxcore-log: 
09-15 12:59:28.980  5479  5525 I jxcore-log: Number of passed tests:  80
09-15 12:59:28.980  5479  5525 I jxcore-log: 
09-15 12:59:28.981  5479  5525 I jxcore-log: Number of failed tests:  0
09-15 12:59:28.981  5479  5525 I jxcore-log: 
09-15 12:59:28.981  5479  5525 I jxcore-log: Number of ignored tests:  0
09-15 12:59:28.981  5479  5525 I jxcore-log: 
09-15 12:59:28.981  5479  5525 I jxcore-log: Total duration:  22588
09-15 12:59:28.981  5479  5525 I jxcore-log: 
09-15 12:59:28.981  5479  5525 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 12:59:28.981  5479  5525 I jxcore-log: 
,09-15 12:59:28.984  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.984  5479  5525 I jxcore-log: 
09-15 12:59:28.986  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.986  5479  5525 I jxcore-log: 
09-15 12:59:28.987  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.987  5479  5525 I jxcore-log: 
09-15 12:59:28.988  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.988  5479  5525 I jxcore-log: 
09-15 12:59:28.989  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.989  5479  5525 I jxcore-log: 
09-15 12:59:28.991  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.991  5479  5525 I jxcore-log: 
09-15 12:59:28.992  5479  5479 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-15 12:59:28.994  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 12:59:28.994  5479  5525 I jxcore-log: 
09-15 12:59:28.996  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 12:59:28.996  5479  5525 I jxcore-log: 
09-15 12:59:28.997  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 12:59:28.997  5479  5525 I jxcore-log: 
09-15 12:59:28.997  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 12:59:28.997  5479  5525 I jxcore-log: 
09-15 12:59:28.998  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 12:59:28.998  5479  5525 I jxcore-log: 
09-15 12:59:28.999  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 12:59:28.999  5479  5525 I jxcore-log: 
09-15 12:59:29.000  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.000  5479  5525 I jxcore-log: 
,09-15 12:59:29.001  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.001  5479  5525 I jxcore-log: 
,09-15 12:59:29.002  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.002  5479  5525 I jxcore-log: 
,09-15 12:59:29.002  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.002  5479  5525 I jxcore-log: 
09-15 12:59:29.003  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.003  5479  5525 I jxcore-log: 
,09-15 12:59:29.004  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.004  5479  5525 I jxcore-log: 
,09-15 12:59:29.004  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.004  5479  5525 I jxcore-log: 
09-15 12:59:29.005  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.005  5479  5525 I jxcore-log: 
,09-15 12:59:29.006  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.006  5479  5525 I jxcore-log: 
,09-15 12:59:29.006  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 12:59:29.006  5479  5525 I jxcore-log: 
09-15 12:59:29.007  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.007  5479  5525 I jxcore-log: 
,09-15 12:59:29.008  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.008  5479  5525 I jxcore-log: 
09-15 12:59:29.008  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.008  5479  5525 I jxcore-log: 
,09-15 12:59:29.009  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.009  5479  5525 I jxcore-log: 
,09-15 12:59:29.010  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.010  5479  5525 I jxcore-log: 
09-15 12:59:29.011  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.011  5479  5525 I jxcore-log: 
,09-15 12:59:29.011  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 12:59:29.011  5479  5525 I jxcore-log: 
,09-15 12:59:29.355  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 12:59:29.361  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 12:59:29.361  5479  5525 I jxcore-log: 
,09-15 12:59:29.406  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 12:59:29.410  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 12:59:29.410  5479  5525 I jxcore-log: 
,09-15 12:59:29.451  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 12:59:29.455  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 12:59:29.455  5479  5525 I jxcore-log: 
,09-15 12:59:29.462  5766  5766 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 12:59:29.468  5766  5766 D AndroidRuntime: CheckJNI is OFF
,09-15 12:59:29.493  5766  5766 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 12:59:29.522  5766  5766 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 12:59:29.537  5766  5766 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 12:59:29.546   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-15 12:59:29.547   926   939 I ActivityManager: Killing 5479:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 12:59:29.628   926  3531 I WindowState: WIN DEATH: Window{40da03c u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-15 12:59:29.628   926  3932 D GraphicsStats: Buffer count: 2
,09-15 12:59:29.629   926  2944 D WifiService: Client connection lost with reason: 4
,09-15 12:59:29.692   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-15 12:59:29.692   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-15 12:59:29.693   926   939 E ActivityManager: Failure starting process com.test.thalitest
09-15 12:59:29.693   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 12:59:29.693   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:29.693   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:29.693   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 12:59:29.693   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 12:59:29.693   926   939 I ActivityManager:   Force finishing activity ActivityRecord{13c6261 u0 com.test.thalitest/.MainActivity t2}
09-15 12:59:29.695   926   949 I art     : Starting a blocking GC Explicit
,09-15 12:59:29.701   926  3149 W ActivityManager: Spurious death for ProcessRecord{ae3399 0:com.test.thalitest/u0a77}, curProc for 5479: null
,09-15 12:59:29.775   926   949 I art     : Explicit concurrent mark sweep GC freed 23819(1503KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.489ms total 79.477ms
,09-15 12:59:29.795   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-15 12:59:29.798  5766  5766 I art     : System.exit called, status: 0
,09-15 12:59:29.798  5766  5766 I AndroidRuntime: VM exiting with result code 0.
,09-15 12:59:29.803   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 12:59:29.812   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-15 12:59:29.814  3398  3398 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 12:59:29.816  5706  5706 D BluetoothMapAppObserver: onReceive
09-15 12:59:29.816  5706  5706 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-15 12:59:29.818  3465  3960 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 12:59:29.824   926  2924 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-15 12:59:29.853  3398  5777 I Keyboard.Facilitator.DecoderInitializer: run()
,09-15 12:59:29.855  3412  5778 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 12:59:29.877  3398  5777 I Decoder : createOrResetDecoder
09-15 12:59:29.878  3523  3523 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 12:59:29.886   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 12:59:29.886    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 12:59:29.889    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 12:59:29.897  3562  3660 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-15 12:59:29.901  3597  3597 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-15 12:59:29.902  3597  3597 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-15 12:59:29.903  3597  3597 E AndroidRuntime: FATAL EXCEPTION: main
09-15 12:59:29.903  3597  3597 E AndroidRuntime: Process: com.google.process.gapps, PID: 3597
09-15 12:59:29.903  3597  3597 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-15 12:59:29.903  3597  3597 E AndroidRuntime: 	... 8 more
,09-15 12:59:29.906    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 12:59:29.912   926   936 I ActivityManager: Start proc 5783:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-15 12:59:29.913  3562  3660 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 12:59:29.913  3562  3660 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3562
09-15 12:59:29.913  3562  3660 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 12:59:29.913  3562  3660 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 12:59:29.919  3597  3597 I Process : Sending signal. PID: 3597 SIG: 9
,09-15 12:59:29.922   926  3531 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-15 12:59:29.923   926  5795 E DropBoxManagerService: Can't write: system_app_crash
09-15 12:59:29.923   926  5795 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 12:59:29.923   926  5795 E DropBoxManagerService: 	... 5 more
,09-15 12:59:29.925   926  5792 E DropBoxManagerService: Can't write: system_app_crash
09-15 12:59:29.925   926  5792 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-15 12:59:29.925   926  5792 E DropBoxManagerService: 	... 8 more
09-15 12:59:29.925  3562  3660 I Process : Sending signal. PID: 3562 SIG: 9
,09-15 12:59:29.940   926  3507 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1868)
,09-15 12:59:29.940   926  3507 W ActivityManager: Application dead when creating service ServiceRecord{30da159 u0 com.google.android.gms/.config.ConfigService}
,09-15 12:59:29.958   926  2944 D WifiService: Client connection lost with reason: 4
,09-15 12:59:29.961   926  3507 I ActivityManager: Process com.google.process.gapps (pid 3597) has died
,09-15 12:59:29.962   926  3507 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
,09-15 12:59:29.962   926  3507 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,09-15 12:59:29.962   926  3507 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-15 12:59:29.962   926  3507 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
09-15 12:59:29.963   926  3507 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 124000ms
09-15 12:59:29.964   926  3507 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
09-15 12:59:29.964   926  3507 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-15 12:59:29.964   926  3507 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-15 12:59:29.964   926  3507 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-15 12:59:29.964   926   937 W ActivityManager: Spurious death for ProcessRecord{505af91 0:com.google.process.gapps/u0a12}, curProc for 3597: null
,09-15 12:59:29.986   926  3149 I ActivityManager: Start proc 5799:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService

```
