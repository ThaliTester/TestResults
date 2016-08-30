#### Test 82865362c4ce6b4_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-30 07:01:25.994   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:26.456  5502  5502 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 07:01:26.462  5502  5502 D AndroidRuntime: CheckJNI is OFF
08-30 07:01:26.493  5502  5502 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 07:01:26.531  5502  5502 I Radio-JNI: register_android_hardware_Radio DONE
08-30 07:01:26.546  5502  5502 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 07:01:26.554   930  3171 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 07:01:26.601   930  3171 I ActivityManager: Start proc 5511:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-30 07:01:26.606  5502  5502 D AndroidRuntime: Shutting down VM
08-30 07:01:26.702  5511  5511 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-30 07:01:26.735  5511  5511 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 07:01:26.763  5511  5511 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 9276-9296)
08-30 07:01:26.763  5511  5511 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 07:01:26.783  5511  5511 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0f169b}
08-30 07:01:26.784  5511  5511 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 07:01:26.784  5511  5511 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 07:01:26.790  5511  5511 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 07:01:26.792  5511  5511 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 07:01:26.830  5511  5511 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 07:01:26.843  5511  5511 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 07:01:26.843  5511  5511 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 07:01:26.843  5511  5511 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-30 07:01:26.843  5511  5511 I Adreno  : Build Date                       : 10/21/15
08-30 07:01:26.843  5511  5511 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 07:01:26.843  5511  5511 I Adreno  : Local Branch                     : 
08-30 07:01:26.843  5511  5511 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-30 07:01:26.843  5511  5511 I Adreno  : Remote Branch                    : NONE
08-30 07:01:26.843  5511  5511 I Adreno  : Reconstruct Branch               : NOTHING
,08-30 07:01:26.904   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5c3e0d7:true
,08-30 07:01:26.956  5511  5511 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 07:01:26.965  5511  5511 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-30 07:01:26.995   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:26.997  5511  5548 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 07:01:27.006  5511  5535 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 07:01:27.040  5511  5548 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 07:01:27.135   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +486ms (total +559ms)
,08-30 07:01:27.162  5511  5511 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5511
,08-30 07:01:27.257  5511  5511 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 07:01:27.463  5511  5551 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -581695184
,08-30 07:01:27.470  5511  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 07:01:27.470  5511  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 07:01:27.470  5511  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 07:01:27.470  5511  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 07:01:27.470  5511  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 07:01:27.470  5511  5551 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58c1809 added. We now have 1 listener(s)
,08-30 07:01:27.475  5511  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
08-30 07:01:27.475  5511  5551 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-30 07:01:27.476  5511  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 07:01:27.477  5511  5551 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 07:01:27.481  5511  5551 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11cc23c added. We now have 1 listener(s)
08-30 07:01:27.482  5511  5551 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:01:27.485   930  2962 D WifiService: New client listening to asynchronous messages
,08-30 07:01:27.486  5511  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 07:01:27.486  5511  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 07:01:27.486  5511  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 07:01:27.486  5511  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 07:01:27.486  5511  5551 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 07:01:27.490  5511  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:01:27.491  5511  5551 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-30 07:01:27.498  5511  5551 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:27.499  5511  5551 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:01:27.499  5511  5551 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 07:01:27.499  5511  5551 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 07:01:27.500  5511  5551 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 07:01:27.502  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:01:27.506  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:01:27.525  5511  5511 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 07:01:27.810  5511  5557 W jxcore-log: Initializing JXcore engine
08-30 07:01:27.810  5511  5557 W jxcore-log: JXcore engine is ready
,08-30 07:01:27.816  5557  5557 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13876 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 07:01:27.826  5557  5557 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[14375]" dev="sockfs" ino=14375 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 07:01:27.826  5557  5557 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 07:01:27.826  5557  5557 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[31883]" dev="sockfs" ino=31883 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 07:01:27.843  5511  5557 W jxcore-log: Starting JXcore engine
,08-30 07:01:27.892  5511  5557 W jxcore-log: Platform android
08-30 07:01:27.892  5511  5557 W jxcore-log: 
08-30 07:01:27.892  5511  5557 W jxcore-log: Process ARCH arm
08-30 07:01:27.892  5511  5557 W jxcore-log: 
,08-30 07:01:27.990  5511  5557 I jxcore-log: JXcore Cordova bridge is ready!
08-30 07:01:27.990  5511  5557 I jxcore-log: 
,08-30 07:01:27.990  5511  5557 W jxcore-log: JXcore engine is started
,08-30 07:01:27.995  5511  5551 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 07:01:27.995   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-30 07:01:27.998  5511  5511 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 07:01:33.848   930  5211 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286380, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 07:01:37.663  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 07:01:37.663  5511  5557 I jxcore-log: 
,08-30 07:01:37.665  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 07:01:37.665  5511  5557 I jxcore-log: 
,08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:37.669  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:01:37.671  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:01:37.672  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 07:01:37.672  5511  5557 I jxcore-log: 
,08-30 07:01:37.674  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 07:01:37.674  5511  5557 I jxcore-log: 
,08-30 07:01:37.921  5511  5557 I jxcore-log: Running unit tests
08-30 07:01:37.921  5511  5557 I jxcore-log: 
,08-30 07:01:37.922  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 07:01:37.922  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5318abc added. We now have 2 listener(s)
08-30 07:01:37.923  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:01:37.923  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 07:01:37.923  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 07:01:37.923  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:01:37.923  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c58a45 added. We now have 2 listener(s)
08-30 07:01:37.923  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 07:01:37.924  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 07:01:37.925  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:37.928  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:01:37.929  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.930  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:01:37.930  5511  5557 D executeNativeTests: Running unit tests
,08-30 07:01:37.936  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:01:37.942  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:01:37.966  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 07:01:37.966  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb added. We now have 3 listener(s)
08-30 07:01:37.966  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:01:37.966  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 07:01:37.966  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 07:01:37.967  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:01:37.967  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 added. We now have 3 listener(s)
08-30 07:01:37.967  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 07:01:37.967  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 07:01:37.968  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:37.971  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:01:37.971  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.972  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:01:37.973  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 07:01:37.973  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:37.973  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:37.973  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:37.974  5511  5557 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 07:01:37.974  5511  5557 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 07:01:37.974  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 07:01:37.974  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 07:01:37.974  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 07:01:37.974  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 07:01:37.974  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:37.974  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:37.974  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:37.975  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:37.975  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.975  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:01:37.975  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 07:01:37.975  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb removed from the list
08-30 07:01:37.975  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:37.975  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 removed from the list
08-30 07:01:37.975  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:01:37.976  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:37.976  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.976  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.976  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.977  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:37.977  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:37.977  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:37.977  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:37.978  5511  5557 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 07:01:37.978  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:37.978  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:37.978  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:37.978  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:37.978  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.978  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.978  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:37.978  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:37.978  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:37.980  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:01:37.980  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:37.981  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.981  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.981  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.981  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.981  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:37.981  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:37.981  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:37.981  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:37.983  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 07:01:37.984  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 07:01:37.984  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:37.984  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:37.984  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:37.985  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:37.985  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.985  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.985  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:37.985  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:37.985  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:37.985  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:37.985  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.985  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.985  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:37.985  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:37.985  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:37.985  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:37.985  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:37.985  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:37.986  5511  5557 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 07:01:37.987  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:37.989  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:01:37.990  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:37.990  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:01:37.990  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 07:01:37.990  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 07:01:37.990  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 07:01:37.990  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:01:37.990  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 07:01:37.992  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 07:01:37.992  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 07:01:37.992  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:01:37.994  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 07:01:37.995  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:01:37.995  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 07:01:37.996  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 07:01:37.997  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 07:01:37.998  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 07:01:37.998  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 07:01:37.998  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 07:01:37.999  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 07:01:37.999  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:01:38.001  4321  4338 D BtGatt.GattService: registerClient() - UUID=530e4d84-29d1-4700-9110-6f8b53b59e87
08-30 07:01:38.002  4321  4398 D BtGatt.GattService: onClientRegistered() - UUID=530e4d84-29d1-4700-9110-6f8b53b59e87, clientIf=5
08-30 07:01:38.003  5511  5521 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 07:01:38.003  4321  4336 D BtGatt.GattService: start scan with filters
08-30 07:01:38.005  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 07:01:38.005  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 07:01:38.005  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 07:01:38.006  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 07:01:38.006  4321  4412 D BtGatt.ScanManager: handling starting scan
08-30 07:01:38.008  4321  4412 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:01:38.009  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 07:01:38.009  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 07:01:38.009  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 07:01:38.009  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 07:01:38.010  5511  5557 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 07:01:38.014  4321  4398 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 07:01:38.015  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:38.015  4321  4412 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 07:01:38.020  4321  4398 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-30 07:01:38.020  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:38.021  4321  4412 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 07:01:38.021  4321  4412 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 07:01:38.030  4321  4398 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 07:01:38.030  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:38.035  4321  4398 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 07:01:38.035  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:38.511  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-30 07:01:38.512  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 07:01:38.512  5511  5511 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 07:01:43.014  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:01:43.015  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:43.015  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 07:01:43.015  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:01:43.015  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 07:01:43.015  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 07:01:43.015  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 07:01:43.015  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:01:43.015  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 07:01:43.016  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 07:01:43.016  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 07:01:43.017  5511  5557 D BluetoothAdapter: STATE_ON
,08-30 07:01:43.018  4321  4336 D BtGatt.GattService: stopScan() - queue size =1
08-30 07:01:43.020  4321  4542 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 07:01:43.022  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 07:01:43.022  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 07:01:43.022  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 07:01:43.022  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 07:01:43.023  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 07:01:43.025  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 07:01:43.026  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 07:01:43.026  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 07:01:43.027  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 07:01:43.027  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 07:01:43.029  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 07:01:43.029  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:01:43.029  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:01:43.029  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:01:43.029  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:43.029  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:43.029  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:43.029  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:01:43.029  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:43.029  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:43.029  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:01:43.031  4321  4321 D BtGatt.ScanManager: awakened up at time 295564
,08-30 07:01:43.040  4321  4398 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-30 07:01:43.041  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:43.041  4321  4412 D BtGatt.ScanManager: stopping BLe Batch
,08-30 07:01:43.051  4321  4398 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 07:01:43.051  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:43.051  4321  4412 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 07:01:43.074  4321  4398 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 07:01:43.074  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:43.075  4321  4398 D BtGatt.GattService: current time is 295608251239
,08-30 07:01:43.075  4321  4398 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -78, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -79, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -77, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 07:01:43.076  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 07:01:43.077  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 07:01:43.078  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 07:01:43.078  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 07:01:43.079  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 07:01:43.079  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 07:01:43.531  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 07:01:47.997   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:48.032  5511  5557 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 07:01:48.037  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:48.048  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:01:48.050  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:48.050  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:01:48.051  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 07:01:48.051  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 07:01:48.051  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 07:01:48.051  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:01:48.051  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 07:01:48.054  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 07:01:48.054  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 07:01:48.055  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:01:48.059  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:01:48.059  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 07:01:48.059  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 07:01:48.060  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 07:01:48.063  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 07:01:48.063  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 07:01:48.063  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 07:01:48.064  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:01:48.066  4321  4550 D BtGatt.GattService: registerClient() - UUID=09751ae6-c60f-4908-94e9-2d2da955e222
08-30 07:01:48.067  4321  4398 D BtGatt.GattService: onClientRegistered() - UUID=09751ae6-c60f-4908-94e9-2d2da955e222, clientIf=5
,08-30 07:01:48.068  5511  5522 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 07:01:48.068  4321  4542 D BtGatt.GattService: start scan with filters
,08-30 07:01:48.071  4321  4412 D BtGatt.ScanManager: handling starting scan
,08-30 07:01:48.071  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 07:01:48.071  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 07:01:48.071  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 07:01:48.071  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 07:01:48.073  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 07:01:48.074  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 07:01:48.074  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 07:01:48.075  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 07:01:48.077  5511  5557 I io.jxcore.node.ConnectionHelper: start: OK
08-30 07:01:48.078  4321  4398 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 07:01:48.078  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:48.079  4321  4412 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 07:01:48.081  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:48.081  5511  5557 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 07:01:48.081  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:48.081  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 07:01:48.081  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:48.081  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 07:01:48.081  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 07:01:48.081  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 07:01:48.081  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:01:48.081  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 07:01:48.081  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 07:01:48.081  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 07:01:48.082  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:01:48.083  4321  4542 D BtGatt.GattService: stopScan() - queue size =1
08-30 07:01:48.083  4321  4336 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 07:01:48.084  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 07:01:48.084  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 07:01:48.084  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 07:01:48.084  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 07:01:48.084  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 07:01:48.084  4321  4398 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-30 07:01:48.084  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:48.085  4321  4412 D BtGatt.ScanManager: Starting BLE batch scan
08-30 07:01:48.085  4321  4412 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 07:01:48.085  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:01:48.085  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 07:01:48.085  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 07:01:48.085  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 07:01:48.086  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:01:48.087  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:01:48.087  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:48.087  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:01:48.087  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:01:48.087  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:01:48.087  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:01:48.087  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:48.087  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:48.087  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:48.087  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:48.087  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:48.088  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:48.088  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:48.089  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:48.089  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:01:48.089  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:48.089  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:48.089  5511  5557 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 07:01:48.091  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:01:48.095  4321  4398 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 07:01:48.095  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:01:48.096  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:01:48.100  4321  4398 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 07:01:48.100  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:48.101  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:01:48.101  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:01:48.102  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 07:01:48.102  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 07:01:48.102  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 07:01:48.102  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:01:48.102  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 07:01:48.104  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:01:48.106  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 07:01:48.106  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 07:01:48.107  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:01:48.108  4321  4398 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-30 07:01:48.108  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:48.108  4321  4412 D BtGatt.ScanManager: stopping BLe Batch
,08-30 07:01:48.111  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 07:01:48.111  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 07:01:48.112  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 07:01:48.114  4321  4398 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 07:01:48.114  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:48.114  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 07:01:48.115  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 07:01:48.115  4321  4412 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 07:01:48.115  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 07:01:48.115  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:01:48.118  4321  4338 D BtGatt.GattService: registerClient() - UUID=0c185dad-59a3-4401-80f9-e8f8aa9c3346
08-30 07:01:48.118  4321  4398 D BtGatt.GattService: onClientRegistered() - UUID=0c185dad-59a3-4401-80f9-e8f8aa9c3346, clientIf=5
,08-30 07:01:48.118  5511  5522 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 07:01:48.119  4321  4542 D BtGatt.GattService: start scan with filters
08-30 07:01:48.119  4321  4398 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 07:01:48.119  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:48.121  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 07:01:48.121  4321  4412 D BtGatt.ScanManager: handling starting scan
08-30 07:01:48.121  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 07:01:48.121  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 07:01:48.121  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 07:01:48.123  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 07:01:48.123  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 07:01:48.124  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 07:01:48.124  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 07:01:48.126  4321  4398 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 07:01:48.126  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:48.126  4321  4412 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 07:01:48.127  5511  5557 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 07:01:48.131  4321  4398 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-30 07:01:48.131  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:48.131  4321  4412 D BtGatt.ScanManager: Starting BLE batch scan
08-30 07:01:48.131  4321  4412 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 07:01:48.139  4321  4398 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 07:01:48.139  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:48.144  4321  4398 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 07:01:48.144  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:48.625  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-30 07:01:48.625  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 07:01:48.625  5511  5511 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 07:01:48.998   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:49.999   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:51.000   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:52.001   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:01:53.001   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-30 07:01:53.127  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:01:53.128  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:53.128  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 07:01:53.128  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:53.128  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 07:01:53.128  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 07:01:53.128  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 07:01:53.128  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:01:53.129  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 07:01:53.129  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 07:01:53.129  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 07:01:53.131  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:01:53.133  4321  4542 D BtGatt.GattService: stopScan() - queue size =1
,08-30 07:01:53.135  4321  4336 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 07:01:53.136  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 07:01:53.137  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 07:01:53.137  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 07:01:53.137  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 07:01:53.138  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 07:01:53.141  4321  4321 D BtGatt.ScanManager: awakened up at time 305674
08-30 07:01:53.141  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:01:53.142  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 07:01:53.142  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 07:01:53.142  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 07:01:53.146  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:01:53.150  4321  4398 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-30 07:01:53.150  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:53.151  4321  4412 D BtGatt.ScanManager: stopping BLe Batch
08-30 07:01:53.152  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:01:53.152  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:01:53.152  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 07:01:53.159  4321  4398 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 07:01:53.160  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:01:53.160  4321  4412 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 07:01:53.175  4321  4398 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-30 07:01:53.175  4321  4398 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:01:53.175  4321  4398 D BtGatt.GattService: current time is 305709118006
08-30 07:01:53.176  4321  4398 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -79, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -76, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 07:01:53.176  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 07:01:53.176  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 07:01:53.176  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 07:01:53.176  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 07:01:53.177  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 07:01:53.177  4321  4398 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-30 07:01:53.653  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 07:01:53.653  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:53.653  5511  5511 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 07:01:58.153  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:01:58.153  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.153  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.154  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.154  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.154  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:01:58.154  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
,08-30 07:01:58.154  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.155  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.155  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 07:01:58.155  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.156  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.156  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.159  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 07:01:58.159  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.159  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.159  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.161  5511  5557 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 07:01:58.163  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.163  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.163  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.163  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 07:01:58.163  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.164  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.164  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.164  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.164  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.164  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.164  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.164  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:01:58.165  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.165  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.168  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.168  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.168  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.168  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.170  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 07:01:58.170  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.170  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.170  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 07:01:58.170  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.170  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.171  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.171  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.171  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.171  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.171  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.171  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:01:58.171  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.171  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.171  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.173  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.173  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.173  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:01:58.173  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.174  5511  5557 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 07:01:58.174  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.174  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.174  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.175  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.175  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.175  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.175  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
,08-30 07:01:58.175  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.175  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.175  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.175  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.175  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.175  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.175  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:01:58.177  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.177  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:01:58.177  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.177  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.178  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 07:01:58.179  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.179  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.179  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.179  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.179  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.179  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.179  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.179  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.179  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.179  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.179  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.179  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.180  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.180  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.182  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.182  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.182  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.182  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
,08-30 07:01:58.183  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 07:01:58.183  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:58.183  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:58.183  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 07:01:58.183  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 07:01:58.183  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 07:01:58.184  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 07:01:58.184  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:58.184  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 07:01:58.184  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:01:58.184  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.184  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.184  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.184  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.184  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:01:58.184  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.185  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.185  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.185  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.185  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.185  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.185  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.186  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:01:58.187  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.187  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.188  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.188  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
,08-30 07:01:58.191  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 07:01:58.191  5511  5557 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 07:01:58.191  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 07:01:58.195  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 07:01:58.195  5511  5557 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 07:01:58.195  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 07:01:58.195  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 07:01:58.195  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 07:01:58.195  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-30 07:01:58.196  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 07:01:58.198  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 07:01:58.198  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 07:01:58.199  5511  5557 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 07:01:58.199  5511  5557 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 07:01:58.199  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 07:01:58.199  5511  5557 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 07:01:58.199  5511  5557 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 07:01:58.199  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 07:01:58.199  5511  5557 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 07:01:58.199  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 07:01:58.203  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 07:01:58.204  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 07:01:58.204  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 07:01:58.204  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 07:01:58.205  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 07:01:58.205  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 07:01:58.205  5511  5557 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 07:01:58.205  5511  5557 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 07:01:58.205  5511  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
08-30 07:01:58.206  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.206  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.206  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.206  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.206  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.206  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.207  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 07:01:58.207  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.207  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.208  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.208  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 07:01:58.208  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.208  5511  5560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 07:01:58.208  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.208  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.208  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.208  5511  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
08-30 07:01:58.208  5511  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
08-30 07:01:58.208  5511  5561 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,08-30 07:01:58.209  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.209  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.209  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:01:58.209  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.210  5511  5557 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 07:01:58.211  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.211  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.211  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.211  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.211  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.211  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.211  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.211  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.211  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.211  5511  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
08-30 07:01:58.211  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.211  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:01:58.212  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.212  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.212  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.213  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.213  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.213  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.213  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.214  5511  5557 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 07:01:58.214  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.214  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.214  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.214  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.214  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.214  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.214  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.214  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.214  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.214  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.214  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.214  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:01:58.215  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.215  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.216  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.216  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.216  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.216  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.217  5511  5557 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 07:01:58.217  5511  5557 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 07:01:58.217  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 07:01:58.217  5511  5557 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 07:01:58.217  5511  5557 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 07:01:58.217  5511  5557 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 07:01:58.217  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 07:01:58.217  5511  5557 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 07:01:58.217  5511  5557 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 07:01:58.217  5511  5557 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 07:01:58.218  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 07:01:58.218  5511  5557 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 07:01:58.218  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:01:58.218  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:01:58.218  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:01:58.218  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.218  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.218  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.218  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.218  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.218  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.218  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.218  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:01:58.218  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.218  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.218  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.219  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:01:58.219  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:01:58.219  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:01:58.219  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.220  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:01:58.220  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.220  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:01:58.220  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:01:58.220  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:01:58.220  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:01:58.220  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:01:58.220  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:01:58.220  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:03.221  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:02:03.222  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.222  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.222  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.222  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.222  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:02:03.223  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:02:03.223  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:02:03.223  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:02:03.223  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.223  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:02:03.223  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.224  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:02:03.224  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.224  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.224  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:03.224  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.224  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.224  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:02:03.225  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.227  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:02:03.228  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:02:03.228  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:02:03.228  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.232  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 07:02:03.232  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:02:03.234  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 07:02:03.236  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 07:02:03.237  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 07:02:03.238  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 07:02:03.238  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 07:02:03.238  5511  5511 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 07:02:03.238  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.238  5511  5562 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:02:03.238  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 07:02:03.238  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 07:02:03.239  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 07:02:03.239  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.239  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 07:02:03.239  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
,08-30 07:02:03.239  5511  5511 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 07:02:03.239  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.239  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 07:02:03.239  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:02:03.239  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 07:02:03.240  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.240  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.241  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 07:02:03.241  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.241  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:02:03.242  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:02:03.242  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:02:03.242  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:02:03.242  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 07:02:03.242  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:02:03.242  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.242  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.243  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.243  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
,08-30 07:02:03.243  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.243  5511  5562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 07:02:03.243  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.243  5511  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 07:02:03.243  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:03.243  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.243  5511  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 07:02:03.243  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:03.243  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.243  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.244  5511  5511 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 07:02:03.245  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 07:02:03.245  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:02:03.245  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.245  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.247  5511  5557 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 07:02:03.248  5511  5557 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 07:02:03.248  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 07:02:03.248  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 07:02:03.248  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 07:02:03.248  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:02:03.248  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:02:03.249  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:02:03.249  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.249  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.249  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.249  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:02:03.249  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:02:03.249  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.249  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:03.249  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.250  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.250  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.250  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.251  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:02:03.252  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:02:03.252  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.252  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.260  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:02:03.260  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:02:03.260  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:02:03.260  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.260  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:02:03.260  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.260  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
08-30 07:02:03.260  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.260  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.260  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:03.260  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.261  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.261  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:02:03.261  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:03.262  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:02:03.262  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:02:03.262  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.262  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.263  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:02:03.263  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:02:03.263  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:02:03.263  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:02:03.264  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.264  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.264  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91f80bb not in the list
,08-30 07:02:03.264  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.264  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.264  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:03.264  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.264  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.264  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:03.264  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:03.265  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:02:03.265  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:02:03.265  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:03.266  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@744f9d8 not in the list
08-30 07:02:03.267  5511  5557 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 07:02:03.267  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 07:02:03.267  5511  5557 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 07:02:03.267  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 07:02:03.267  5511  5557 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 07:02:03.267  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 07:02:03.270  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 07:02:03.270  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 07:02:03.271  5511  5557 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 07:02:03.271  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 07:02:03.271  5511  5557 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 07:02:03.271  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 07:02:03.271  5511  5557 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 07:02:03.271  5511  5557 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-30 07:02:03.272  5511  5557 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 07:02:03.272  5511  5557 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 07:02:03.273  5511  5557 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 07:02:03.273  5511  5557 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 07:02:03.273  5511  5557 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-30 07:02:03.273  5511  5557 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-30 07:02:03.275  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:02:03.275  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ad68fa added. We now have 3 listener(s)
08-30 07:02:03.275  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:02:03.277  5511  5557 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 07:02:03.277   930   940 D WifiService: setWifiEnabled: true pid=5511, uid=10077
08-30 07:02:03.277   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 07:02:03.338  4321  4526 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-30 07:02:03.339  4321  4540 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,08-30 07:02:03.742  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 07:02:08.283  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 07:02:08.283  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2e0eab added. We now have 4 listener(s)
,08-30 07:02:08.283  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:02:08.296  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:02:08.296  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2e0eab removed from the list
08-30 07:02:08.296  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:08.297  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:08.297  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:08.299  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:02:08.299  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2568908 added. We now have 4 listener(s)
08-30 07:02:08.299  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:02:08.304  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:02:08.304  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2568908 removed from the list
08-30 07:02:08.304  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:08.304  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:02:08.305  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:08.306  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:02:08.307  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c8f8a1 added. We now have 4 listener(s)
08-30 07:02:08.307  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:02:08.312   930  3413 D WifiService: setWifiEnabled: false pid=5511, uid=10077
,08-30 07:02:08.312   930  3413 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 07:02:08.320   930  2961 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 07:02:08.320   930  2961 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 07:02:08.320   930  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 07:02:08.321   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 07:02:08.322  4321  4392 D BluetoothAdapterState: Current state: ON, message: 23
08-30 07:02:08.322  4321  4392 D BluetoothAdapterProperties: Setting state to 13
08-30 07:02:08.322  4321  4392 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 07:02:08.323  4321  4392 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 07:02:08.325  4321  4392 I BluetoothAdapterState: Entering PendingCommandState
,08-30 07:02:08.327  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:02:08.334  4321  4398 D BluetoothAdapterProperties: Scan Mode:20
08-30 07:02:08.334  4321  4392 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 07:02:08.336  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:08.336  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:02:08.337  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.337  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:08.338  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:02:08.339  4321  4321 D HeadsetService: Received stop request...Stopping profile...
,08-30 07:02:08.343  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.346  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:08.347   930  2961 E native  : do suspend true
,08-30 07:02:08.352  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:08.352  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:02:08.353  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.353  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:08.357  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:08.357  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:02:08.358  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.358  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:02:08.359   930   943 I ActivityManager: Start proc 5566:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 07:02:08.362   930   930 D BluetoothHeadset: Proxy object disconnected
,08-30 07:02:08.362   930   930 D BluetoothHeadset: Proxy object disconnected
,08-30 07:02:08.362  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.362  3090  3755 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:08.362  3090  3090 D HeadsetProfile: Bluetooth service disconnected
08-30 07:02:08.363   930   930 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:08.363  4321  4321 D A2dpService: Received stop request...Stopping profile...
08-30 07:02:08.363  3514  3537 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:08.363  4321  4545 D A2dpStateMachine: Exit Disconnected: -1
08-30 07:02:08.364   930  5212 D DhcpClient: Clearing IP address
08-30 07:02:08.364   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 07:02:08.366  3090  3090 D BluetoothA2dp: Proxy object disconnected
08-30 07:02:08.367  4321  4321 D BluetoothMapService: onReceive
08-30 07:02:08.367  4321  4321 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 07:02:08.367  4321  4321 D BluetoothMapService: STATE_TURNING_OFF
08-30 07:02:08.367   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:08.367   930   930 D BluetoothA2dp: Proxy object disconnected
08-30 07:02:08.368  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.369  4321  4321 D HidService: Received stop request...Stopping profile...
08-30 07:02:08.369  4321  4321 D HidService: Stopping Bluetooth HidService
08-30 07:02:08.370  4321  4321 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:08.370  4321  4321 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:08.370  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.370  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 07:02:08.370  3090  3090 D BluetoothInputDevice: Proxy object disconnected
08-30 07:02:08.370  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.370  3090  3090 D HidProfile: Bluetooth service disconnected
08-30 07:02:08.370  4321  4321 D HealthService: Received stop request...Stopping profile...
08-30 07:02:08.370   930  5213 D DhcpClient: Receive thread stopped
08-30 07:02:08.372  4321  4321 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 07:02:08.373  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.373  4321  4398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 07:02:08.373  4321  4321 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 07:02:08.373  4321  4526 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:08.373  4321  4526 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:08.373  4321  4526 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:08.373  4321  4398 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 07:02:08.373  4321  4321 D PanService: Received stop request...Stopping profile...
,08-30 07:02:08.374  3090  3090 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 07:02:08.374  3090  3090 D PanProfile: Bluetooth service disconnected
08-30 07:02:08.374  4321  4321 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:08.374  4321  4321 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:08.374  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.375  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:08.375  3573  5273 V NativeCrypto: Read error: ssl=0x7f8ef8df80: I/O error during system call, Connection timed out
08-30 07:02:08.376  4321  4321 D BluetoothMapService: Received stop request...Stopping profile...
08-30 07:02:08.376  4321  4321 D BluetoothMapService: stop()
08-30 07:02:08.378  3573  5273 V NativeCrypto: SSL shutdown failed: ssl=0x7f8ef8df80: I/O error during system call, Broken pipe
08-30 07:02:08.380   930  3413 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-30 07:02:08.380   930  5210 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-30 07:02:08.380  4321  4321 D BluetoothMapAppObserver: deinitObservers()
08-30 07:02:08.380  4321  4321 D BluetoothMapAppObserver: removeReceiver()
08-30 07:02:08.381  3090  3090 D BluetoothMap: Proxy object disconnected
08-30 07:02:08.382  3090  3090 D MapProfile: Bluetooth service disconnected
08-30 07:02:08.382   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 07:02:08.382   930  5210 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-30 07:02:08.383   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-30 07:02:08.388   534   534 E Parcel  : Reading a NULL string not supported here.
,08-30 07:02:08.389   930   930 D RttService: SCAN_AVAILABLE : 1
08-30 07:02:08.390   930  3014 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 07:02:08.391  4321  4526 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:08.391   930  2963 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 07:02:08.391  4321  4321 I BtOppRfcommListener: stopping Accept Thread
08-30 07:02:08.391  4321  4526 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:08.391  4321  5133 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 07:02:08.392  4321  4398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 07:02:08.392  4321  4526 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 07:02:08.392  4321  4526 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 07:02:08.392  4321  4526 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 07:02:08.392  4321  4526 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 07:02:08.392  4321  5133 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 07:02:08.393  3466  3723 W QCNEJ   : |CORE| network lost: 100
,08-30 07:02:08.393  3466  3723 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-30 07:02:08.394  4321  4321 D SapService: Received stop request...Stopping profile...
08-30 07:02:08.394  4321  4321 V SapService: stop()
08-30 07:02:08.395  4321  4321 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:08.395  4321  4321 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:08.395  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.395  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:08.396  4321  4321 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 07:02:08.396  4321  4321 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 07:02:08.396  4321  4398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 07:02:08.396  4321  4321 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:08.396  4321  4321 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:08.396  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 07:02:08.396  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:08.397  4321  4321 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 07:02:08.397  4321  4398 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 07:02:08.397   930  2961 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 07:02:08.397  4321  4321 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 07:02:08.397  4321  4321 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:08.397  4321  4321 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:08.397  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.397  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:08.398  4321  4321 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 07:02:08.398  4321  4321 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 07:02:08.399  4321  4321 D BluetoothMapService: MAP Service closeService in
,08-30 07:02:08.399  4321  4321 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 07:02:08.399  4321  4321 D ObexServerSockets0: shutdown(block = true)
08-30 07:02:08.400  4321  4321 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 07:02:08.400  4321  4553 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 07:02:08.400  4321  4321 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 07:02:08.400  4321  4540 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 07:02:08.400  4321  4554 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 07:02:08.400  4321  4321 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:08.401  4321  4321 V BluetoothAdapterState: isTurningOn()=false
,08-30 07:02:08.401  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.401  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:08.401  4321  4321 D BluetoothMapService: cleanup()
08-30 07:02:08.401  4321  4321 D BluetoothMapService: MAP Service closeService in
,08-30 07:02:08.403   930  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 07:02:08.403   930  2961 E native  : do suspend true
,08-30 07:02:08.405  4321  4321 V BluetoothAdapterState: isTurningOff()=true
,08-30 07:02:08.405  4321  4321 V BluetoothAdapterState: isTurningOn()=false
,08-30 07:02:08.406  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.406  4321  4321 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 07:02:08.406  4321  4392 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 07:02:08.406  4321  4392 D BluetoothAdapterProperties: Setting state to 15
,08-30 07:02:08.406  4321  4392 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 07:02:08.406   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:08.407   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:08.407  4321  4392 I BluetoothAdapterState: Entering BleOnState
08-30 07:02:08.407  3090  3102 D BluetoothPan: onBluetoothStateChange on: false
08-30 07:02:08.407  3090  3755 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:08.408  3090  3101 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 07:02:08.409  3514  3539 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:08.409   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 07:02:08.409  3090  3102 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 07:02:08.409  3090  3755 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 07:02:08.410  3090  3101 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 07:02:08.410   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 07:02:08.411  4321  4392 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 07:02:08.411  4321  4392 D BluetoothAdapterProperties: Setting state to 16
08-30 07:02:08.411  4321  4392 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 07:02:08.412  4321  4392 D BluetoothAdapterProperties: onBleDisable
08-30 07:02:08.412  4321  4392 I BluetoothAdapterState: Entering PendingCommandState
08-30 07:02:08.412  4321  4393 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 07:02:08.413  4321  4398 D BluetoothAdapterProperties: Scan Mode:20
08-30 07:02:08.414  4321  4526 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 07:02:08.414  4321  4526 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:08.415  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:08.415  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:08.416  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.416  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:08.418  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.418   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:08.418  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 07:02:08.419  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.419  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:08.422  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:08.422  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:08.423  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.423  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 07:02:08.424  5566  5566 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,08-30 07:02:08.424  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:08.426  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.427  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:08.437   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:08.437   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 07:02:08.438   507   923 D TetherController: Setting IP forward enable = 0
08-30 07:02:08.438  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 07:02:08.439   930  2963 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 07:02:08.439   930  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 07:02:08.441   930   947 D Tethering: MasterInitialState.processMessage what=3
08-30 07:02:08.442   930  2961 D DhcpClient: doQuit
08-30 07:02:08.442   930  2961 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-30 07:02:08.442  5088  5088 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ad7a27 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-30 07:02:08.443  3625  3625 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-30 07:02:08.443   930  5212 D DhcpClient: onQuitting
08-30 07:02:08.446  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 07:02:08.447  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:08.447  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:08.447  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.448  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:08.450  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:08.450  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 07:02:08.451  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:08.451  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:08.453  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:08.453  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:08.454  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:08.454  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:08.456  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.457  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.459  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:08.460  4760  4793 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-30 07:02:08.460  4760  4793 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 07:02:08.461  4760  4793 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-30 07:02:08.461  4760  4793 E SarControlService: no key has been found,reset the power
08-30 07:02:08.461  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 07:02:08.461  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 07:02:08.461  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 07:02:08.462  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:08.462  4799  4799 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 07:02:08.464  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-30 07:02:08.464  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-30 07:02:08.464  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 07:02:08.464   930   941 I ActivityManager: Start proc 5593:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-30 07:02:08.464  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:08.464  4799  4799 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 07:02:08.467  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000ea03000000000000ffffffff]
08-30 07:02:08.468  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:08.468  4799  4815 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-30 07:02:08.468  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:08.468  4760  4770 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 07:02:08.472  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000eb03000000000000ffffffff]
,08-30 07:02:08.472  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:08.472  4799  4815 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-30 07:02:08.473  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:08.473  4760  4771 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-30 07:02:08.476   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ffa923e:true
,08-30 07:02:08.486   507   923 E Netd    : netlink response contains error (No such file or directory)
,08-30 07:02:08.487   507   923 D TetherController: Setting IP forward enable = 0
08-30 07:02:08.489  3625  3625 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
08-30 07:02:08.489   930  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 07:02:08.493  3625  3625 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 07:02:08.502  5593  5593 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-30 07:02:08.506  5566  5566 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 07:02:08.508  5566  5566 D BluetoothMap: Create BluetoothMap proxy object
,08-30 07:02:08.526  5566  5566 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 07:02:08.543  5566  5566 D DockEventReceiver: finishStartingService: stopping service
,08-30 07:02:08.548   930  3548 I ActivityManager: Killing 5245:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-30 07:02:08.577  3625  3625 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-30 07:02:08.597  3625  3625 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 07:02:08.603  4181  4181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 07:02:08.604   930  2961 D wifi    : In wifi stop Hal
08-30 07:02:08.604   930  2961 D wifi    : halHandle = 0x7f748cee00, mVM = 0x7f9080d140, mCls = 0x100b4e
08-30 07:02:08.604   930  3597 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-30 07:02:08.604   930  3597 D WifiHAL : Got a signal to exit!!!
08-30 07:02:08.604   930  3597 I WifiHAL : Exit wifi_event_loop
,08-30 07:02:08.607   930  2961 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-30 07:02:08.607   930  2961 E WifiHAL : Event processing terminated
08-30 07:02:08.607   930  2961 D wifi    : In wifi cleaned up handler
08-30 07:02:08.607   930  2961 I WifiHAL : Internal cleanup completed
08-30 07:02:08.608  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:08.610  3446  3932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 07:02:08.610  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:08.611  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:08.621  4321  4398 I bt_hci  : shut_down
,08-30 07:02:08.623  4321  4415 D bt_hwcfg: hw_epilog_process
,08-30 07:02:08.623  4321  4415 I bt_vendor: low_power_mode_cb
,08-30 07:02:08.626  4321  4415 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 07:02:08.626  4321  4415 I bt_vendor: epilog_cb
08-30 07:02:08.626  4321  4415 I bt_hci  : epilog_finished_callback
,08-30 07:02:08.628  4321  4398 I bt_hci_h4: hal_close
08-30 07:02:08.629  4321  4398 I bt_userial_vendor: device fd = 51 close
08-30 07:02:08.629   930  3597 D wifi    : set interface wlan0 flags (DOWN)
08-30 07:02:08.629   930  2961 D WifiNative-HAL: HAL event thread stopped successfully
,08-30 07:02:08.724  5593  5593 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 07:02:08.724  5593  5593 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.724  5593  5593 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.724  5593  5593 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.724  5593  5593 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.724  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.725  5593  5593 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.725  5593  5593 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.725  5593  5593 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 07:02:08.725  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 07:02:08.731  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 07:02:08.737  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 07:02:08.742  5566  5566 D DockEventReceiver: finishStartingService: stopping service
08-30 07:02:08.744   930  3126 I ActivityManager: Killing 5260:com.android.chrome/u0a39 (adj 15): empty #17
,08-30 07:02:08.784  4321  4393 D bt_stack_manager: event_shut_down_stack finished.
08-30 07:02:08.784  4321  4392 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 07:02:08.786  4321  4392 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 07:02:08.787  4321  4321 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 07:02:08.787  3836  3836 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 07:02:08.787  4321  4321 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 07:02:08.787  4321  4321 D BtGatt.GattService: stop()
08-30 07:02:08.787  4321  4321 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 07:02:08.789  4321  4321 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:08.790  4321  4321 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:08.790  4321  4321 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:08.790  4321  4321 V BluetoothAdapterState: isBleTurningOff()=true
08-30 07:02:08.790  4321  4392 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 07:02:08.790  4321  4392 D BluetoothAdapterProperties: Setting state to 10
08-30 07:02:08.790  3836  3836 D SystemUpdateService: onCreate
08-30 07:02:08.790  4321  4392 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 07:02:08.790  4321  4392 I BluetoothAdapterState: Entering OffState
08-30 07:02:08.792   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 07:02:08.799  4321  4321 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 07:02:08.799  4321  4321 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 07:02:08.800  4321  4393 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 07:02:08.800  4321  4321 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 07:02:08.802  4321  4393 D bt_stack_manager: event_clean_up_stack finished.
08-30 07:02:08.802  3836  3836 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 07:02:08.811  3836  3836 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 07:02:08.815  3836  5239 I iu.UploadsManager: num queued entries: 0
,08-30 07:02:08.816  3836  5239 I iu.UploadsManager: num updated entries: 0
,08-30 07:02:08.817  4321  4321 I art     : System.exit called, status: 0
,08-30 07:02:08.817  4321  4321 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 07:02:08.828  3836  5631 I SystemUpdateService: active receiver: enabled
,08-30 07:02:08.832   930   947 D Tethering: InitialState.processMessage what=4
,08-30 07:02:08.834   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 07:02:08.838  3836  3836 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 07:02:08.839  3836  3836 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-30 07:02:08.850  3836  5239 I iu.SyncManager: NEXT; no task
,08-30 07:02:08.852   930  3404 I ActivityManager: Start proc 5633:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 07:02:08.869  3836  5631 I SystemUpdateService: showing system update notification
,08-30 07:02:08.883  5633  5633 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-30 07:02:08.887  5633  5633 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-30 07:02:08.888   930  3413 I ActivityManager: Process com.android.bluetooth (pid 4321) has died
,08-30 07:02:08.894  5633  5633 D SprintDMHelper: simOperator: 
,08-30 07:02:08.894  5633  5633 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 07:02:08.906   930  3548 I ActivityManager: Start proc 5645:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 07:02:08.908  3836  5631 V SystemUpdateService: retry (wakeup: false) in 3599921 ms
,08-30 07:02:08.910  3836  3836 D SystemUpdateService: onDestroy
,08-30 07:02:08.912   930  3413 I ActivityManager: Killing 5088:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-30 07:02:09.010  5593  5622 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 07:02:09.020   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@54fa4dd:true
,08-30 07:02:09.129  4181  5661 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 07:02:09.143   930  3541 I ActivityManager: Start proc 5662:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 07:02:09.146   930  3171 I ActivityManager: Killing 4404:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-30 07:02:09.176  5662  5662 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-30 07:02:09.215  5662  5662 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 07:02:09.220   930  3404 I ActivityManager: Killing 5374:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-30 07:02:13.341   930  3126 D WifiService: setWifiEnabled: true pid=5511, uid=10077
,08-30 07:02:13.341   930  3126 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 07:02:13.349   507   923 D SoftapController: Softap fwReload - Ok
,08-30 07:02:13.352   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:13.352   507   923 D CommandListener: Trying to bring down wlan0
,08-30 07:02:13.353   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-30 07:02:13.356   930  2961 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-30 07:02:13.936   930  2961 D wifi    : set interface wlan0 flags (UP)
,08-30 07:02:13.939   930  2961 I WifiHAL : Initializing wifi
08-30 07:02:13.939   930  2961 I WifiHAL : Creating socket
,08-30 07:02:13.942   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 07:02:13.943   930  2961 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-30 07:02:13.943   930  2961 D wifi    : Did set static halHandle = 0x7f748cee00
08-30 07:02:13.943   930  2961 D wifi    : halHandle = 0x7f748cee00, mVM = 0x7f9080d140, mCls = 0x201806
08-30 07:02:13.943   930  2961 D wifi    : array field set
08-30 07:02:13.943   930  2961 I WifiNative-HAL: interface[0] = wlan0
08-30 07:02:13.945   930  5687 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547416239616
08-30 07:02:13.945   930  5687 D wifi    : waitForHalEvents called, vm = 0x7f9080d140, obj = 0x201806, env = 0x7f75a44900
,08-30 07:02:13.984  5688  5688 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 07:02:14.008  5688  5688 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 07:02:14.016  5688  5688 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 07:02:14.016  5688  5688 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-30 07:02:14.047   930  2961 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 07:02:14.054  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:14.058  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:14.058  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:14.058  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:14.058  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:14.062  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:14.062  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:14.062  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:14.062  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:14.066   930  2961 D WifiConfigStore: Loading config and enabling all networks 
,08-30 07:02:14.067  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:14.067  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:14.067  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:14.067  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:14.068  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:14.069  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:14.072   930  2961 D WifiConfigStore: loaded 0 passpoint configs
08-30 07:02:14.072   930  2961 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 07:02:14.073   930  2961 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 07:02:14.074   930  2961 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 07:02:14.075   930  2961 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-30 07:02:14.075   930  2961 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 07:02:14.079   930  2961 D WifiNative-HAL: Setting external_sim to 1
,08-30 07:02:14.079  4181  4181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 07:02:14.079   930  2961 D wifi    : setting dfs flag to true, 0x7f760a6c80
08-30 07:02:14.080   930  2961 D WifiStateMachine: Setting OUI to DA-A1-19
,08-30 07:02:14.080   930  2961 D wifi    : setting scan oui 0x7f760a6c80
08-30 07:02:14.080   930  2961 D WifiHAL : Sending mac address OUI
,08-30 07:02:14.096   930  2961 E native  : do suspend true
,08-30 07:02:14.101   930  2961 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-30 07:02:14.101   930   930 D RttService: SCAN_AVAILABLE : 3
08-30 07:02:14.101   930  3014 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 07:02:14.101   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 07:02:14.102   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:14.106   930  2949 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,08-30 07:02:14.107   930  2949 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 07:02:14.113   930  2949 D WifiNative-HAL: p2pGetDeviceAddress
08-30 07:02:14.113   930  2949 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-30 07:02:14.119   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=326652 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,08-30 07:02:17.324  5688  5688 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 07:02:17.358   930  2961 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-30 07:02:17.367   930  2961 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-30 07:02:17.367   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:17.382   930  2961 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-30 07:02:17.419   930  2961 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-30 07:02:17.766  5688  5688 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 07:02:17.803  5688  5688 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 07:02:17.804  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 07:02:17.818   930  2961 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 07:02:17.818   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:17.818   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 07:02:17.833   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:17.844   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:17.850   930  2961 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 07:02:17.857   930  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 07:02:17.868   930  5694 D DhcpClient: Receive thread started
,08-30 07:02:17.951   930  2961 E native  : do suspend false
,08-30 07:02:17.965   930  5693 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 07:02:17.979   930  5694 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172511, domain null
,08-30 07:02:17.980   930  5693 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172511 seconds
,08-30 07:02:17.982   930  5693 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-30 07:02:17.994   930  5694 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 07:02:17.994   930  5693 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-30 07:02:17.997   507   923 D CommandListener: Setting iface cfg
08-30 07:02:18.002   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 07:02:18.002   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 07:02:18.007   930  5693 D DhcpClient: Scheduling renewal in 86399s
,08-30 07:02:18.007   930  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 07:02:18.011   930  2961 E native  : do suspend true
,08-30 07:02:18.027   930  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 07:02:18.030   930  2961 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 07:02:18.032   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 07:02:18.034   930  2963 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 07:02:18.041   930  2961 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 07:02:18.083   930  2963 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 07:02:18.084   930  2963 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 07:02:18.086   930  2963 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 07:02:18.088   930  2963 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 07:02:18.090   930  2963 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 07:02:18.100   930  2963 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 07:02:18.105   930  2963 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 07:02:18.105   930  2963 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 07:02:18.105   930  2963 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 07:02:18.105   930  2961 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 07:02:18.105   930  2963 D ConnectivityService:    accepting network in place of null
08-30 07:02:18.106   930  2963 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 07:02:18.107   930  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 07:02:18.124   930  5692 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330657, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 07:02:18.137   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:18.161   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:18.166   930  2963 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 07:02:18.166   930  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 07:02:18.166  3466  3723 W QCNEJ   : |CORE| network available: 101
,08-30 07:02:18.168   930  2963 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 07:02:18.169   930   947 D Tethering: MasterInitialState.processMessage what=3
,08-30 07:02:18.172  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:18.172  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:02:18.172  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.172  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:18.172  3466  3723 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-30 07:02:18.173  3466  3723 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-30 07:02:18.174  3466  3723 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-30 07:02:18.176  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:18.176  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:02:18.176  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.176  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:02:18.179  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:18.179  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:02:18.179  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.179  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:02:18.184  4760  4793 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-30 07:02:18.185  4760  4793 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 07:02:18.185  4760  4793 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-30 07:02:18.185  4760  4793 E SarControlService: no key has been found,reset the power
,08-30 07:02:18.185  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 07:02:18.185  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 07:02:18.185  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 07:02:18.186  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:18.186  4799  4799 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 07:02:18.189  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-30 07:02:18.189  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-30 07:02:18.189  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 07:02:18.190  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:18.190  4799  4799 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-30 07:02:18.192  3836  3836 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 07:02:18.193   930  5691 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
08-30 07:02:18.195  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000ec03000000000000ffffffff]
08-30 07:02:18.195  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:18.195  4799  4815 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
08-30 07:02:18.195  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000ed03000000000000ffffffff]
08-30 07:02:18.196  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-30 07:02:18.196  4799  4815 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
08-30 07:02:18.197  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-30 07:02:18.197  4760  4770 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-30 07:02:18.197  3836  3836 D SystemUpdateService: onCreate
08-30 07:02:18.198  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:18.198  4760  4771 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-30 07:02:18.202  3836  3836 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 07:02:18.212  3836  3836 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 07:02:18.219  3836  5239 I iu.UploadsManager: num queued entries: 0
,08-30 07:02:18.219  3836  5239 I iu.UploadsManager: num updated entries: 0
08-30 07:02:18.220  3836  5239 I iu.SyncManager: NEXT; no task
,08-30 07:02:18.221  3836  5704 I SystemUpdateService: active receiver: enabled
,08-30 07:02:18.223  3836  3836 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 07:02:18.224  3836  3836 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
08-30 07:02:18.225  5633  5633 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 07:02:18.229  5633  5633 D SprintDMHelper: simOperator: 
08-30 07:02:18.229  5633  5633 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 07:02:18.241   930  5691 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 11:02:18 GMT], X-Android-Received-Millis=[1472554938240], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472554938217]}
,08-30 07:02:18.241   930  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 07:02:18.241   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 07:02:18.242   930  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 07:02:18.243   930  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 07:02:18.260  3836  5704 I SystemUpdateService: showing system update notification
,08-30 07:02:18.266  3836  5704 V SystemUpdateService: retry (wakeup: false) in 3599956 ms
,08-30 07:02:18.268  3836  3836 D SystemUpdateService: onDestroy
,08-30 07:02:18.337  4181  5709 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 07:02:18.344   930  4909 D WifiService: setWifiEnabled: false pid=5511, uid=10077
08-30 07:02:18.344   930  4909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 07:02:18.348   930  2961 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 07:02:18.348   930  2961 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 07:02:18.348   930  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 07:02:18.348   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:18.354   930  2961 E native  : do suspend true
,08-30 07:02:18.360   930  5693 D DhcpClient: Clearing IP address
08-30 07:02:18.360   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-30 07:02:18.362  3573  5715 V NativeCrypto: Read error: ssl=0x7f8ef8ce00: I/O error during system call, Connection timed out
,08-30 07:02:18.362  3573  5715 V NativeCrypto: SSL shutdown failed: ssl=0x7f8ef8ce00: I/O error during system call, Broken pipe
,08-30 07:02:18.369   930  4909 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,08-30 07:02:18.370   930  5691 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
08-30 07:02:18.370   930  5691 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
08-30 07:02:18.371   507   923 D CommandListener: Setting iface cfg
08-30 07:02:18.374   930  5694 D DhcpClient: Receive thread stopped
08-30 07:02:18.375   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 07:02:18.375   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 07:02:18.378   930  5691 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-30 07:02:18.379   534   534 E Parcel  : Reading a NULL string not supported here.
,08-30 07:02:18.381   930   930 D RttService: SCAN_AVAILABLE : 1
,08-30 07:02:18.382   930  2963 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 07:02:18.382   930  3014 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 07:02:18.384  3466  3723 W QCNEJ   : |CORE| network lost: 101
08-30 07:02:18.384  3466  3723 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-30 07:02:18.386   930  2961 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 07:02:18.389   930  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 07:02:18.389   930  2961 E native  : do suspend true
,08-30 07:02:18.403   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:18.422   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:18.422   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 07:02:18.422   930  2963 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 07:02:18.422   930  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 07:02:18.423   930   947 D Tethering: MasterInitialState.processMessage what=3
,08-30 07:02:18.425   930  2961 D DhcpClient: doQuit
08-30 07:02:18.425   930  2961 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-30 07:02:18.426   930  5693 D DhcpClient: onQuitting
08-30 07:02:18.426  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.426  5688  5688 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:18.426  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:18.426  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.426  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:18.427  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:18.427  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:18.427  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.427  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:18.428  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:18.428  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:18.428  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.428  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:18.430  4760  4793 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-30 07:02:18.430  4760  4793 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 07:02:18.430  4760  4793 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-30 07:02:18.431  4760  4793 E SarControlService: no key has been found,reset the power
08-30 07:02:18.431  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 07:02:18.431  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.431  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:18.431  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:18.431  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 07:02:18.431  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:18.431  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 07:02:18.431  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:18.432  4799  4799 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 07:02:18.432  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:18.433  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:18.434  3836  3836 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 07:02:18.435  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-30 07:02:18.435  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-30 07:02:18.435  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 07:02:18.436  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:18.436  4799  4799 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 07:02:18.439  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000ee03000000000000ffffffff]
08-30 07:02:18.439  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:18.439  4799  4815 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
08-30 07:02:18.440  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:18.440  4760  4771 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 07:02:18.441  3836  3836 D SystemUpdateService: onCreate
08-30 07:02:18.442  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000ef03000000000000ffffffff]
08-30 07:02:18.442  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:18.442  4799  4815 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
08-30 07:02:18.443  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:18.443  4760  4770 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-30 07:02:18.445  3836  3836 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 07:02:18.449  3836  5724 I SystemUpdateService: active receiver: enabled
,08-30 07:02:18.455  3836  3836 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 07:02:18.460  3836  5239 I iu.UploadsManager: num queued entries: 0
,08-30 07:02:18.460  3836  5239 I iu.UploadsManager: num updated entries: 0
08-30 07:02:18.461  3836  5239 I iu.SyncManager: NEXT; no task
08-30 07:02:18.463  3836  3836 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 07:02:18.464  3836  3836 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-30 07:02:18.466  5633  5633 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 07:02:18.469  5633  5633 D SprintDMHelper: simOperator: 
08-30 07:02:18.469  5633  5633 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 07:02:18.472   507   923 E Netd    : netlink response contains error (No such file or directory)
,08-30 07:02:18.473   930  2963 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 07:02:18.473   930  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 07:02:18.473  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-30 07:02:18.476  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 07:02:18.481  4181  5728 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 07:02:18.484  3836  5724 I SystemUpdateService: showing system update notification
,08-30 07:02:18.504  3836  5724 V SystemUpdateService: retry (wakeup: false) in 3599946 ms
,08-30 07:02:18.506  3836  3836 D SystemUpdateService: onDestroy
,08-30 07:02:18.517  5688  5688 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-30 07:02:18.537  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 07:02:18.640   930  2961 D wifi    : In wifi stop Hal
,08-30 07:02:18.640   930  2961 D wifi    : halHandle = 0x7f748cee00, mVM = 0x7f9080d140, mCls = 0x201806
,08-30 07:02:18.640   930  5687 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-30 07:02:18.640   930  5687 D WifiHAL : Got a signal to exit!!!
08-30 07:02:18.641   930  5687 I WifiHAL : Exit wifi_event_loop
08-30 07:02:18.642  4181  4181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 07:02:18.643  3446  3932 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 07:02:18.643   930  2961 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-30 07:02:18.643   930  2961 E WifiHAL : Event processing terminated
08-30 07:02:18.643   930  2961 D wifi    : In wifi cleaned up handler
08-30 07:02:18.643  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:18.643   930  2961 I WifiHAL : Internal cleanup completed
,08-30 07:02:18.644  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:18.645  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:18.659   930  5687 D wifi    : set interface wlan0 flags (DOWN)
,08-30 07:02:18.659   930  2961 D WifiNative-HAL: HAL event thread stopped successfully
,08-30 07:02:18.869   930   947 D Tethering: InitialState.processMessage what=4
,08-30 07:02:18.874   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 07:02:19.167   930  2963 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 07:02:23.383   930   947 I ActivityManager: Start proc 5732:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 07:02:23.479  5732  5732 D AdapterServiceConfig: Adding HeadsetService
,08-30 07:02:23.479  5732  5732 D AdapterServiceConfig: Adding A2dpService
08-30 07:02:23.480  5732  5732 D AdapterServiceConfig: Adding HidService
08-30 07:02:23.480  5732  5732 D AdapterServiceConfig: Adding HealthService
08-30 07:02:23.480  5732  5732 D AdapterServiceConfig: Adding PanService
08-30 07:02:23.480  5732  5732 D AdapterServiceConfig: Adding GattService
08-30 07:02:23.480  5732  5732 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 07:02:23.481  5732  5732 D AdapterServiceConfig: Adding SapService
,08-30 07:02:23.493   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d97f36:true
,08-30 07:02:23.494  5732  5732 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 07:02:23.496  5732  5732 I bt_bluedroid: init
,08-30 07:02:23.496  5732  5744 I BluetoothAdapterState: Entering OffState
,08-30 07:02:23.498  5732  5745 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 07:02:23.498  5732  5745 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 07:02:23.499  5732  5745 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 07:02:23.499  5732  5745 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 07:02:23.499  5732  5732 I bt_bluedroid: get_profile_interface socket
,08-30 07:02:23.501  5732  5748 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-30 07:02:23.501  5732  5732 I bt_bluedroid: get_profile_interface sdp
,08-30 07:02:23.503  5732  5748 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 07:02:23.504  5732  5743 I bt_bluedroid: config_hci_snoop_log
,08-30 07:02:23.505   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 07:02:23.509  5732  5744 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 07:02:23.509  5732  5744 D BluetoothAdapterProperties: Setting state to 14
08-30 07:02:23.509  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-30 07:02:23.511  5732  5744 D BluetoothBondStateMachine: make
,08-30 07:02:23.512  5732  5749 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 07:02:23.515  5732  5744 I BluetoothAdapterState: Entering PendingCommandState
,08-30 07:02:23.516  5732  5732 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 07:02:23.518  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:23.518  5732  5732 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 07:02:23.519  5732  5732 D BtGatt.GattService: Received start request. Starting profile...
08-30 07:02:23.520  5732  5732 D BtGatt.GattService: start()
08-30 07:02:23.520  5732  5732 I bt_bluedroid: get_profile_interface gatt
,08-30 07:02:23.521  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:23.521  5732  5732 D BtGatt.AdvertiseManager: advertise manager created
,08-30 07:02:23.525  5732  5732 V BluetoothAdapterState: isTurningOff()=false
,08-30 07:02:23.525  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:23.525  5732  5732 V BluetoothAdapterState: isBleTurningOn()=true
08-30 07:02:23.525  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:23.526  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 07:02:23.526  5732  5744 I bt_bluedroid: enable
08-30 07:02:23.526  5732  5745 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 07:02:23.526  5732  5745 I bt_hci  : start_up
,08-30 07:02:23.531  5732  5745 I bt_vendor: alloc value 0xf413304d
08-30 07:02:23.531  5732  5745 I bt_vendor: init
08-30 07:02:23.531  5732  5745 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 07:02:23.531  5732  5745 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 07:02:23.647  5732  5745 D bt_hci  : start_up starting async portion
08-30 07:02:23.649  5732  5752 I bt_hci  : event_finish_startup
08-30 07:02:23.649  5732  5752 I bt_hci_h4: hal_open
,08-30 07:02:23.649  5732  5752 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 07:02:23.652  5732  5752 I bt_userial_vendor: device fd = 51 open
,08-30 07:02:23.636  5753  5753 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 07:02:23.666  5732  5752 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 07:02:23.669  5732  5752 D bt_hwcfg: Chipset BCM4358A3
,08-30 07:02:23.670  5732  5752 D bt_hwcfg: Target name = [BCM4358A3]
08-30 07:02:23.670  5732  5752 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-30 07:02:24.070  5732  5752 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-30 07:02:24.071  5732  5752 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 07:02:24.071  5732  5752 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 07:02:24.205  5732  5752 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 07:02:24.206  5732  5752 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-30 07:02:24.207  5732  5752 I bt_hwcfg: vendor lib fwcfg completed
08-30 07:02:24.207  5732  5752 I bt_vendor: firmware callback
08-30 07:02:24.207  5732  5752 I bt_hci  : firmware_config_callback
08-30 07:02:24.215  5732  5755 I bt_btu  : btu_task pending for preload complete event
,08-30 07:02:24.216  5732  5755 I bt_btu_task: Bluetooth chip preload is complete
08-30 07:02:24.216  5732  5755 I bt_btu  : btu_task received preload complete event
,08-30 07:02:24.222  5732  5755 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 07:02:24.223  5732  5755 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 07:02:24.224  5732  5755 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 07:02:24.224  5732  5755 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 07:02:24.224  5732  5755 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 07:02:24.224  5732  5755 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 07:02:24.224  5732  5755 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 07:02:24.224  5732  5755 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 07:02:24.308  5732  5755 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40b0c99
08-30 07:02:24.309  5732  5755 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40b0c99 
,08-30 07:02:24.320  5732  5748 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 07:02:24.322  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 07:02:24.322  5732  5748 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-30 07:02:24.325  5732  5748 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 07:02:24.328  5732  5748 D BluetoothAdapterProperties: Scan Mode:20
,08-30 07:02:24.329  5732  5748 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 07:02:24.329  5732  5748 D bt_hci  : do_postload posting postload work item
,08-30 07:02:24.329  5732  5752 I bt_hci  : event_postload
08-30 07:02:24.329  5732  5752 I bt_vendor: sco_config_cb
,08-30 07:02:24.329  5732  5752 I bt_hci  : sco_config_callback postload finished.
,08-30 07:02:24.334  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:24.339  5732  5752 I bt_vendor: low_power_mode_cb
08-30 07:02:24.338  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:24.341  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:24.342  5732  5748 D bt_bte_conf: Device ID record 1 : primary
08-30 07:02:24.342  5732  5748 D bt_bte_conf:   vendorId            = 000f
08-30 07:02:24.342  5732  5748 D bt_bte_conf:   vendorIdSource      = 0001
08-30 07:02:24.342  5732  5748 D bt_bte_conf:   product             = 1200
08-30 07:02:24.342  5732  5748 D bt_bte_conf:   version             = 1436
08-30 07:02:24.343  5732  5748 D bt_bte_conf:   clientExecutableURL = 
08-30 07:02:24.343  5732  5748 D bt_bte_conf:   serviceDescription  = 
08-30 07:02:24.343  5732  5748 D bt_bte_conf:   documentationURL    = 
08-30 07:02:24.343  5732  5748 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 07:02:24.343  5732  5745 D bt_stack_manager: event_start_up_stack finished
08-30 07:02:24.344  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 07:02:24.344  5732  5744 D BluetoothAdapterProperties: Setting state to 15
08-30 07:02:24.344  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 07:02:24.345  5732  5744 I BluetoothAdapterState: Entering BleOnState
,08-30 07:02:24.350  5732  5744 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 07:02:24.350  5732  5744 D BluetoothAdapterProperties: Setting state to 11
08-30 07:02:24.350  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 07:02:24.360  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:24.363  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:24.363  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:24.365  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:24.367  5732  5732 D HeadsetService: Received start request. Starting profile...
08-30 07:02:24.369  5732  5732 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 07:02:24.370  5732  5732 D HeadsetStateMachine: make
,08-30 07:02:24.375  5732  5744 I BluetoothAdapterState: Entering PendingCommandState
,08-30 07:02:24.379  5732  5732 D HeadsetStateMachine: max_hf_connections = 1
,08-30 07:02:24.379  5732  5732 I bt_bluedroid: get_profile_interface handsfree
08-30 07:02:24.380  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 07:02:24.380  5732  5748 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-30 07:02:24.384  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:24.385  5732  5732 D A2dpService: Received start request. Starting profile...
,08-30 07:02:24.386  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 07:02:24.386  5732  5732 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 07:02:24.387  5732  5732 I bt_bluedroid: get_profile_interface avrcp
,08-30 07:02:24.393  5732  5732 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 07:02:24.393  5732  5732 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 07:02:24.393  5732  5732 D A2dpStateMachine: make
,08-30 07:02:24.395  5732  5732 I bt_bluedroid: get_profile_interface a2dp
,08-30 07:02:24.395  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 07:02:24.397  5732  5763 D A2dpStateMachine: Enter Disconnected: -2
,08-30 07:02:24.397  5732  5732 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 07:02:24.400  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:24.401  5566  5566 D BluetoothInputDevice: Proxy object connected
,08-30 07:02:24.401  5732  5732 D HidService: Received start request. Starting profile...
08-30 07:02:24.402  5732  5732 I bt_bluedroid: get_profile_interface hidhost
08-30 07:02:24.402  5732  5732 D HidService: setHidService(): set to: null
08-30 07:02:24.402  5732  5748 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40922d9
08-30 07:02:24.402  5566  5566 D HidProfile: Bluetooth service connected
08-30 07:02:24.402  5732  5732 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 07:02:24.402  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 07:02:24.403  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:24.404  5732  5732 D HealthService: Received start request. Starting profile...
,08-30 07:02:24.405  5732  5732 I bt_bluedroid: get_profile_interface health
,08-30 07:02:24.406  5732  5732 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 07:02:24.407  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:24.409  5732  5732 D PanService: Received start request. Starting profile...
,08-30 07:02:24.409  5732  5732 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 07:02:24.409  5732  5732 I bt_bluedroid: get_profile_interface pan
08-30 07:02:24.410  5732  5748 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 07:02:24.412  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:24.413  5566  5566 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 07:02:24.413  5732  5732 D BluetoothMapService: Received start request. Starting profile...
08-30 07:02:24.413  5732  5732 D BluetoothMapService: start()
08-30 07:02:24.413  5566  5566 D PanProfile: Bluetooth service connected
,08-30 07:02:24.414  5566  5566 D BluetoothMap: Proxy object connected
08-30 07:02:24.414  5566  5566 D MapProfile: Bluetooth service connected
08-30 07:02:24.414  5566  5566 D BluetoothMap: getConnectedDevices()
08-30 07:02:24.415  5566  5566 D BluetoothMap: Bluetooth is Not enabled
08-30 07:02:24.416  5732  5732 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 07:02:24.417  5732  5732 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 07:02:24.417  5732  5732 D BluetoothMapAppObserver: createReceiver()
,08-30 07:02:24.419  5732  5732 D BluetoothMapAppObserver: initObservers()
,08-30 07:02:24.419  5732  5732 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 07:02:24.426  5732  5732 V SapService: SapBinder()
,08-30 07:02:24.426  5732  5732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:24.427  5732  5732 D SapService: Received start request. Starting profile...
08-30 07:02:24.427  5732  5732 V SapService: start()
,08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.430  5732  5761 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:24.430  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOn()=true
,08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.431  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:24.432  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:24.432  5732  5732 V BluetoothAdapterState: isTurningOn()=true
,08-30 07:02:24.432  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:24.432  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:24.432  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 07:02:24.433  5732  5744 D BluetoothAdapterProperties: ScanMode =  20
08-30 07:02:24.433  5732  5744 D BluetoothAdapterProperties: State =  11
08-30 07:02:24.433  5732  5744 D BluetoothAdapterProperties: Setting state to 12
08-30 07:02:24.433  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 07:02:24.434  5732  5744 I BluetoothAdapterState: Entering OnState
,08-30 07:02:24.434  5566  5580 D BluetoothPan: onBluetoothStateChange on: true
,08-30 07:02:24.435  5566  5577 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 07:02:24.435   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 07:02:24.435   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:24.435  5566  5579 D BluetoothMap: onBluetoothStateChange: up=true
08-30 07:02:24.436  3090  3101 D BluetoothPan: onBluetoothStateChange on: true
08-30 07:02:24.436  5732  5748 D BluetoothAdapterProperties: Scan Mode:21
08-30 07:02:24.436  5732  5748 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 07:02:24.438  3090  3755 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:24.438  3090  3090 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 07:02:24.438  3090  3090 D PanProfile: Bluetooth service connected
08-30 07:02:24.438  3090  3101 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 07:02:24.440  3514  3792 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:24.440  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 07:02:24.440   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 07:02:24.441  3090  3102 D BluetoothMap: onBluetoothStateChange: up=true
08-30 07:02:24.442   930   930 D BluetoothA2dp: Proxy object connected
08-30 07:02:24.442  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:24.443  3090  3102 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 07:02:24.443  3090  3090 D BluetoothMap: Proxy object connected
08-30 07:02:24.443  3090  3090 D MapProfile: Bluetooth service connected
08-30 07:02:24.443  3090  3090 D BluetoothMap: getConnectedDevices()
08-30 07:02:24.445  3090  3101 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 07:02:24.445  3090  3090 D BluetoothA2dp: Proxy object connected
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:24.446  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:24.447  5732  5732 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 07:02:24.447   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:24.448  5732  5732 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 07:02:24.448  5566  5580 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 07:02:24.449  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:24.449  5732  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 07:02:24.450  3090  3090 D BluetoothInputDevice: Proxy object connected
08-30 07:02:24.450  3090  3090 D HidProfile: Bluetooth service connected
08-30 07:02:24.450   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:24.452  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:24.453  5566  5566 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 07:02:24.454  5732  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:02:24.457  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:24.457  5732  5732 D ObexServerSockets: Succeed to create listening sockets 
08-30 07:02:24.458  5732  5732 D ObexServerSockets0: startAccept()
08-30 07:02:24.458  5732  5732 D ObexServerSockets0: prepareForNewConnect()
08-30 07:02:24.459  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:24.459  5732  5732 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 07:02:24.460  5732  5732 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 07:02:24.460  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:24.460  5732  5770 D ObexServerSockets0: Accepting socket connection...
08-30 07:02:24.460  5732  5732 D BluetoothMapService: onReceive
08-30 07:02:24.460  5732  5732 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 07:02:24.460  5732  5732 D BluetoothMapService: STATE_ON
08-30 07:02:24.460  5732  5771 D ObexServerSockets0: Accepting socket connection...
08-30 07:02:24.461  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:24.462  5566  5566 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 07:02:24.462  5732  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 07:02:24.463  5732  5772 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-30 07:02:24.463  5732  5772 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-30 07:02:24.467  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 07:02:24.469  5566  5566 D BluetoothA2dp: Proxy object connected
,08-30 07:02:24.472  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 07:02:24.477  5566  5566 D DockEventReceiver: finishStartingService: stopping service
,08-30 07:02:24.480  5566  5566 D BluetoothPbap: Proxy object connected
,08-30 07:02:24.481  5566  5566 D PbapServerProfile: Bluetooth service connected
,08-30 07:02:24.483  3090  3090 D BluetoothPbap: Proxy object connected
,08-30 07:02:24.483  3090  3090 D PbapServerProfile: Bluetooth service connected
,08-30 07:02:24.486  5732  5732 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 07:02:24.486  5732  5732 D ObexServerSockets0: prepareForNewConnect()
08-30 07:02:24.487  5732  5776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:02:24.501  5732  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:02:24.503  5732  5780 I BtOppRfcommListener: Accept thread started.
,08-30 07:02:24.536   930   930 D BluetoothHeadset: Proxy object connected
08-30 07:02:24.536   930   930 D BluetoothHeadset: Proxy object connected
,08-30 07:02:24.536  3090  3101 D BluetoothHeadset: Proxy object connected
08-30 07:02:24.537  3090  3090 D HeadsetProfile: Bluetooth service connected
08-30 07:02:24.537   930   930 D BluetoothHeadset: Proxy object connected
,08-30 07:02:24.538  3514  3539 D BluetoothHeadset: Proxy object connected
,08-30 07:02:24.539  3090  3102 D BluetoothHeadset: Proxy object connected
08-30 07:02:24.540  3090  3090 D HeadsetProfile: Bluetooth service connected
08-30 07:02:24.540  3514  3537 D BluetoothHeadset: Proxy object connected
,08-30 07:02:24.547   930   947 D BluetoothHeadset: Proxy object connected
,08-30 07:02:24.564  5566  5579 D BluetoothHeadset: Proxy object connected
,08-30 07:02:24.565  5566  5566 D HeadsetProfile: Bluetooth service connected
,08-30 07:02:26.112   930  2963 D ConnectivityService: handlePromptUnvalidated 101
,08-30 07:02:28.363  5732  5744 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 07:02:28.363  5732  5744 D BluetoothAdapterProperties: Setting state to 13
08-30 07:02:28.363  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 07:02:28.365  5732  5744 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 07:02:28.368  5732  5732 D BluetoothMapService: onReceive
,08-30 07:02:28.368  5732  5732 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 07:02:28.369  5732  5732 D BluetoothMapService: STATE_TURNING_OFF
08-30 07:02:28.369  5732  5732 D BluetoothMapService: MAP Service closeService in
08-30 07:02:28.369  5732  5732 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 07:02:28.369  5732  5732 D ObexServerSockets0: shutdown(block = true)
08-30 07:02:28.370  5732  5732 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 07:02:28.370  5732  5770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 07:02:28.370  5732  5732 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 07:02:28.371  5732  5771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 07:02:28.372  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 07:02:28.372  5732  5744 I BluetoothAdapterState: Entering PendingCommandState
08-30 07:02:28.372  5732  5732 I BtOppRfcommListener: stopping Accept Thread
,08-30 07:02:28.372  5732  5757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 07:02:28.372  5732  5780 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 07:02:28.373  5732  5780 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 07:02:28.374  5732  5748 D BluetoothAdapterProperties: Scan Mode:20
08-30 07:02:28.375  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:28.375  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:28.376  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:28.377  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:28.381  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 07:02:28.382  5566  5566 D DockEventReceiver: finishStartingService: stopping service
08-30 07:02:28.382  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 07:02:28.384  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:28.385  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:28.385  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:28.385  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 07:02:28.388  5732  5732 D HeadsetService: Received stop request...Stopping profile...
08-30 07:02:28.388  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:28.388  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:28.388  5566  5566 D BluetoothPbap: Proxy object disconnected
08-30 07:02:28.389  5566  5566 D PbapServerProfile: Bluetooth service disconnected
08-30 07:02:28.389  5511  5511 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 07:02:28.389  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:28.391  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:28.392   930   930 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:28.392   930   930 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:28.392  3090  3090 D BluetoothPbap: Proxy object disconnected
08-30 07:02:28.392  3090  3090 D PbapServerProfile: Bluetooth service disconnected
08-30 07:02:28.393  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:28.393  5566  5577 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:28.393  3090  3755 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:28.393   930   930 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:28.394  3514  3792 D BluetoothHeadset: Proxy object disconnected
08-30 07:02:28.394  5732  5732 D A2dpService: Received stop request...Stopping profile...
08-30 07:02:28.394  5732  5763 D A2dpStateMachine: Exit Disconnected: -1
08-30 07:02:28.395  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:28.395  5566  5566 D HeadsetProfile: Bluetooth service disconnected
,08-30 07:02:28.396  3090  3090 D HeadsetProfile: Bluetooth service disconnected
08-30 07:02:28.397   930   930 D BluetoothA2dp: Proxy object disconnected
,08-30 07:02:28.398  5566  5566 D BluetoothA2dp: Proxy object disconnected
08-30 07:02:28.398  3090  3090 D BluetoothA2dp: Proxy object disconnected
08-30 07:02:28.398  5732  5732 V BluetoothAdapterState: isTurningOff()=true
,08-30 07:02:28.398  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.398  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.398  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.399  5732  5732 D HidService: Received stop request...Stopping profile...
08-30 07:02:28.399  5732  5732 D HidService: Stopping Bluetooth HidService
08-30 07:02:28.399  3090  3090 D BluetoothInputDevice: Proxy object disconnected
08-30 07:02:28.399  5566  5566 D BluetoothInputDevice: Proxy object disconnected
,08-30 07:02:28.400  3090  3090 D HidProfile: Bluetooth service disconnected
,08-30 07:02:28.400  5566  5566 D HidProfile: Bluetooth service disconnected
08-30 07:02:28.400  5732  5732 D HealthService: Received stop request...Stopping profile...
08-30 07:02:28.402  5732  5732 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 07:02:28.402  5732  5732 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 07:02:28.402  5732  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:28.402  5732  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:28.402  5732  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:28.403  5732  5732 D PanService: Received stop request...Stopping profile...
,08-30 07:02:28.403  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 07:02:28.403  5732  5748 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 07:02:28.404  3090  3090 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 07:02:28.404  3090  3090 D PanProfile: Bluetooth service disconnected
08-30 07:02:28.404  5566  5566 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 07:02:28.404  5566  5566 D PanProfile: Bluetooth service disconnected
,08-30 07:02:28.407  5732  5732 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 07:02:28.407  5732  5732 D BluetoothMapService: stop()
08-30 07:02:28.407  5732  5732 D BluetoothMapAppObserver: deinitObservers()
08-30 07:02:28.407  5732  5732 D BluetoothMapAppObserver: removeReceiver()
08-30 07:02:28.408  3090  3090 D BluetoothMap: Proxy object disconnected
08-30 07:02:28.408  3090  3090 D MapProfile: Bluetooth service disconnected
08-30 07:02:28.408  5732  5732 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:28.408  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.409  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.409  5566  5566 D BluetoothMap: Proxy object disconnected
08-30 07:02:28.409  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.409  5566  5566 D MapProfile: Bluetooth service disconnected
,08-30 07:02:28.409  5732  5732 D SapService: Received stop request...Stopping profile...
08-30 07:02:28.409  5732  5732 V SapService: stop()
08-30 07:02:28.411  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 07:02:28.411  5732  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:28.411  5732  5732 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:28.411  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.411  5732  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:28.411  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.411  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.411  5732  5755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 07:02:28.411  5732  5755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 07:02:28.411  5732  5732 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 07:02:28.411  5732  5755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 07:02:28.411  5732  5732 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 07:02:28.411  5732  5755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 07:02:28.411  5732  5748 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 07:02:28.411  5732  5732 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.412  5732  5732 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 07:02:28.412  5732  5748 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 07:02:28.412  5732  5732 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.412  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.413  5732  5732 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 07:02:28.413  5732  5732 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 07:02:28.414  5732  5732 D BluetoothMapService: MAP Service closeService in
08-30 07:02:28.414  5732  5732 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:28.414  5732  5732 V BluetoothAdapterState: isTurningOn()=false
,08-30 07:02:28.414  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.415  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.415  5732  5732 D BluetoothMapService: cleanup()
08-30 07:02:28.415  5732  5732 D BluetoothMapService: MAP Service closeService in
08-30 07:02:28.415  5732  5732 V BluetoothAdapterState: isTurningOff()=true
08-30 07:02:28.415  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.415  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.415  5732  5732 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:28.415  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 07:02:28.415  5732  5744 D BluetoothAdapterProperties: Setting state to 15
08-30 07:02:28.415  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 07:02:28.416  5732  5744 I BluetoothAdapterState: Entering BleOnState
,08-30 07:02:28.416  5566  5577 D BluetoothPan: onBluetoothStateChange on: false
08-30 07:02:28.417  5566  5579 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 07:02:28.417  5566  5580 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 07:02:28.418   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 07:02:28.418   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 07:02:28.418  5566  5577 D BluetoothMap: onBluetoothStateChange: up=false
08-30 07:02:28.418  3090  3755 D BluetoothPan: onBluetoothStateChange on: false
08-30 07:02:28.419  3090  3101 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:28.419  3090  3102 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 07:02:28.420  3514  3539 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:28.420   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 07:02:28.420  3090  3755 D BluetoothMap: onBluetoothStateChange: up=false
08-30 07:02:28.420  3090  3101 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 07:02:28.421  3090  3102 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 07:02:28.421   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:28.421  5566  5579 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 07:02:28.422  5566  5580 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 07:02:28.422  5732  5744 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 07:02:28.422  5732  5744 D BluetoothAdapterProperties: Setting state to 16
08-30 07:02:28.422  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 07:02:28.423  5732  5744 D BluetoothAdapterProperties: onBleDisable
08-30 07:02:28.423  5732  5744 I BluetoothAdapterState: Entering PendingCommandState
08-30 07:02:28.423  5732  5745 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 07:02:28.425  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:28.425  5732  5755 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 07:02:28.425  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 07:02:28.425  5732  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 07:02:28.427  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:28.427  5732  5748 D BluetoothAdapterProperties: Scan Mode:20
,08-30 07:02:28.428  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 07:02:28.430  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:28.431  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:28.432  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 07:02:28.432  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:28.432  5566  5566 D DockEventReceiver: finishStartingService: stopping service
,08-30 07:02:28.638  5732  5748 I bt_hci  : shut_down
,08-30 07:02:28.647  5732  5752 D bt_hwcfg: hw_epilog_process
,08-30 07:02:28.648  5732  5752 I bt_vendor: low_power_mode_cb
,08-30 07:02:28.651  5732  5752 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-30 07:02:28.651  5732  5752 I bt_vendor: epilog_cb
08-30 07:02:28.651  5732  5752 I bt_hci  : epilog_finished_callback
,08-30 07:02:28.655  5732  5748 I bt_hci_h4: hal_close
,08-30 07:02:28.657  5732  5748 I bt_userial_vendor: device fd = 51 close
,08-30 07:02:28.781  5732  5745 D bt_stack_manager: event_shut_down_stack finished.
,08-30 07:02:28.782  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 07:02:28.786  5732  5744 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 07:02:28.787  5732  5732 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 07:02:28.788  5732  5732 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 07:02:28.788  5732  5732 D BtGatt.GattService: stop()
,08-30 07:02:28.788  5732  5732 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 07:02:28.792  5732  5732 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:28.792  5732  5732 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:28.792  5732  5732 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:28.792  5732  5732 V BluetoothAdapterState: isBleTurningOff()=true
08-30 07:02:28.793  5732  5744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 07:02:28.793  5732  5744 D BluetoothAdapterProperties: Setting state to 10
08-30 07:02:28.793  5732  5744 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 07:02:28.795  5732  5744 I BluetoothAdapterState: Entering OffState
,08-30 07:02:28.796   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 07:02:28.810  5732  5732 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 07:02:28.810  5732  5732 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 07:02:28.810  5732  5732 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 07:02:28.813  5732  5745 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 07:02:28.817  5732  5745 D bt_stack_manager: event_clean_up_stack finished.
08-30 07:02:28.819  5732  5732 I art     : System.exit called, status: 0
,08-30 07:02:28.819  5732  5732 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 07:02:28.858   930  4908 I ActivityManager: Process com.android.bluetooth (pid 5732) has died
,08-30 07:02:33.003   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:33.361  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 07:02:33.362  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:33.365  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:33.366  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c8f8a1 removed from the list
08-30 07:02:33.366  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:33.366  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:33.367  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:33.370  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:02:33.370  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bcea87 added. We now have 4 listener(s)
,08-30 07:02:33.370  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 07:02:33.373  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:02:33.373  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bcea87 removed from the list
,08-30 07:02:33.374  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:33.374  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:33.374  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:33.376  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:02:33.377  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24f2db4 added. We now have 4 listener(s)
08-30 07:02:33.377  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:02:34.004   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:35.005   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:36.006   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:37.007   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:38.008   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 07:02:38.385  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:38.422   930   947 I ActivityManager: Start proc 5788:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 07:02:38.501  5788  5788 D AdapterServiceConfig: Adding HeadsetService
08-30 07:02:38.501  5788  5788 D AdapterServiceConfig: Adding A2dpService
08-30 07:02:38.501  5788  5788 D AdapterServiceConfig: Adding HidService
08-30 07:02:38.501  5788  5788 D AdapterServiceConfig: Adding HealthService
08-30 07:02:38.501  5788  5788 D AdapterServiceConfig: Adding PanService
08-30 07:02:38.502  5788  5788 D AdapterServiceConfig: Adding GattService
08-30 07:02:38.502  5788  5788 D AdapterServiceConfig: Adding BluetoothMapService
08-30 07:02:38.502  5788  5788 D AdapterServiceConfig: Adding SapService
,08-30 07:02:38.512   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ec09f7:true
,08-30 07:02:38.513  5788  5788 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 07:02:38.516  5788  5788 I bt_bluedroid: init
08-30 07:02:38.516  5788  5800 I BluetoothAdapterState: Entering OffState
,08-30 07:02:38.518  5788  5801 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 07:02:38.518  5788  5801 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 07:02:38.518  5788  5801 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 07:02:38.518  5788  5801 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 07:02:38.519  5788  5788 I bt_bluedroid: get_profile_interface socket
,08-30 07:02:38.521  5788  5804 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-30 07:02:38.522  5788  5788 I bt_bluedroid: get_profile_interface sdp
08-30 07:02:38.523  5788  5804 D BluetoothAdapterProperties: Name is: Nexus 6P
08-30 07:02:38.525  5788  5799 I bt_bluedroid: config_hci_snoop_log
,08-30 07:02:38.526   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 07:02:38.530  5788  5800 D BluetoothAdapterState: Current state: OFF, message: 0
08-30 07:02:38.530  5788  5800 D BluetoothAdapterProperties: Setting state to 14
08-30 07:02:38.530  5788  5800 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 07:02:38.532  5788  5800 D BluetoothBondStateMachine: make
,08-30 07:02:38.534  5788  5805 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 07:02:38.536  5788  5800 I BluetoothAdapterState: Entering PendingCommandState
,08-30 07:02:38.538  5788  5788 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 07:02:38.540  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:38.540  5788  5788 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 07:02:38.541  5788  5788 D BtGatt.GattService: Received start request. Starting profile...
08-30 07:02:38.541  5788  5788 D BtGatt.GattService: start()
08-30 07:02:38.541  5788  5788 I bt_bluedroid: get_profile_interface gatt
08-30 07:02:38.542  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:38.542  5788  5788 D BtGatt.AdvertiseManager: advertise manager created
,08-30 07:02:38.548  5788  5788 V BluetoothAdapterState: isTurningOff()=false
,08-30 07:02:38.549  5788  5788 V BluetoothAdapterState: isTurningOn()=false
08-30 07:02:38.549  5788  5788 V BluetoothAdapterState: isBleTurningOn()=true
08-30 07:02:38.549  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:38.549  5788  5800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 07:02:38.549  5788  5800 I bt_bluedroid: enable
08-30 07:02:38.550  5788  5801 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 07:02:38.550  5788  5801 I bt_hci  : start_up
,08-30 07:02:38.556  5788  5801 I bt_vendor: alloc value 0xf413304d
,08-30 07:02:38.556  5788  5801 I bt_vendor: init
08-30 07:02:38.556  5788  5801 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 07:02:38.556  5788  5801 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 07:02:38.681  5788  5801 D bt_hci  : start_up starting async portion
,08-30 07:02:38.682  5788  5808 I bt_hci  : event_finish_startup
08-30 07:02:38.682  5788  5808 I bt_hci_h4: hal_open
08-30 07:02:38.682  5788  5808 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-30 07:02:38.685  5788  5808 I bt_userial_vendor: device fd = 51 open
,08-30 07:02:38.676  5809  5809 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 07:02:38.701  5788  5808 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 07:02:38.705  5788  5808 D bt_hwcfg: Chipset BCM4358A3
08-30 07:02:38.705  5788  5808 D bt_hwcfg: Target name = [BCM4358A3]
,08-30 07:02:38.706  5788  5808 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-30 07:02:39.098  5788  5808 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 07:02:39.098  5788  5808 D bt_hwcfg: Settlement delay -- 100 ms
08-30 07:02:39.099  5788  5808 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 07:02:39.232  5788  5808 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 07:02:39.232  5788  5808 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-30 07:02:39.234  5788  5808 I bt_hwcfg: vendor lib fwcfg completed
08-30 07:02:39.234  5788  5808 I bt_vendor: firmware callback
,08-30 07:02:39.234  5788  5808 I bt_hci  : firmware_config_callback
,08-30 07:02:39.242  5788  5811 I bt_btu  : btu_task pending for preload complete event
,08-30 07:02:39.242  5788  5811 I bt_btu_task: Bluetooth chip preload is complete
,08-30 07:02:39.242  5788  5811 I bt_btu  : btu_task received preload complete event
,08-30 07:02:39.250  5788  5811 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 07:02:39.250  5788  5811 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 07:02:39.250  5788  5811 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 07:02:39.250  5788  5811 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 07:02:39.250  5788  5811 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 07:02:39.250  5788  5811 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 07:02:39.251  5788  5811 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 07:02:39.334  5788  5811 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40b0c99
,08-30 07:02:39.334  5788  5811 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40b0c99 
,08-30 07:02:39.363  5788  5804 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 07:02:39.365  5788  5804 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 07:02:39.365  5788  5804 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-30 07:02:39.369  5788  5804 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-30 07:02:39.371  5788  5804 D BluetoothAdapterProperties: Scan Mode:20
08-30 07:02:39.371  5788  5804 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 07:02:39.372  5788  5804 D bt_hci  : do_postload posting postload work item
08-30 07:02:39.372  5788  5808 I bt_hci  : event_postload
08-30 07:02:39.372  5788  5808 I bt_vendor: sco_config_cb
08-30 07:02:39.372  5788  5808 I bt_hci  : sco_config_callback postload finished.
,08-30 07:02:39.375  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:39.375  5788  5804 D bt_bte_conf: Device ID record 1 : primary
08-30 07:02:39.375  5788  5804 D bt_bte_conf:   vendorId            = 000f
08-30 07:02:39.375  5788  5804 D bt_bte_conf:   vendorIdSource      = 0001
,08-30 07:02:39.375  5788  5804 D bt_bte_conf:   product             = 1200
08-30 07:02:39.376  5788  5804 D bt_bte_conf:   version             = 1436
08-30 07:02:39.376  5788  5804 D bt_bte_conf:   clientExecutableURL = 
08-30 07:02:39.376  5788  5804 D bt_bte_conf:   serviceDescription  = 
08-30 07:02:39.376  5788  5804 D bt_bte_conf:   documentationURL    = 
08-30 07:02:39.376  5788  5804 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 07:02:39.376  5788  5801 D bt_stack_manager: event_start_up_stack finished
08-30 07:02:39.377  5788  5800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 07:02:39.377  5788  5800 D BluetoothAdapterProperties: Setting state to 15
08-30 07:02:39.377  5788  5800 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 07:02:39.378  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:39.379  5788  5800 I BluetoothAdapterState: Entering BleOnState
,08-30 07:02:39.383  5788  5800 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 07:02:39.383  5788  5800 D BluetoothAdapterProperties: Setting state to 11
08-30 07:02:39.383  5788  5800 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 07:02:39.385  5788  5808 I bt_vendor: low_power_mode_cb
,08-30 07:02:39.391  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:39.396  5788  5788 D HeadsetService: Received start request. Starting profile...
,08-30 07:02:39.400  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:39.402  5788  5788 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 07:02:39.403  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:39.406  5788  5788 D HeadsetStateMachine: make
,08-30 07:02:39.409  5788  5800 I BluetoothAdapterState: Entering PendingCommandState
,08-30 07:02:39.416  5788  5788 D HeadsetStateMachine: max_hf_connections = 1
,08-30 07:02:39.416  5788  5788 I bt_bluedroid: get_profile_interface handsfree
08-30 07:02:39.420  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:39.421  5788  5788 D A2dpService: Received start request. Starting profile...
08-30 07:02:39.422  5788  5788 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 07:02:39.422  5788  5788 I bt_bluedroid: get_profile_interface avrcp
,08-30 07:02:39.427  5788  5804 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 07:02:39.427  5788  5804 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-30 07:02:39.428  5788  5788 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 07:02:39.428  5788  5788 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 07:02:39.428  5788  5788 D A2dpStateMachine: make
08-30 07:02:39.429  5788  5788 I bt_bluedroid: get_profile_interface a2dp
,08-30 07:02:39.430  5788  5804 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 07:02:39.431  5788  5819 D A2dpStateMachine: Enter Disconnected: -2
08-30 07:02:39.432  5788  5788 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 07:02:39.433  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:39.433  5788  5788 D HidService: Received start request. Starting profile...
08-30 07:02:39.434  5788  5788 I bt_bluedroid: get_profile_interface hidhost
08-30 07:02:39.434  5788  5788 D HidService: setHidService(): set to: null
08-30 07:02:39.434  5788  5804 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40922d9
08-30 07:02:39.434  5788  5804 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 07:02:39.435  5788  5788 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 07:02:39.436  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:39.437  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 07:02:39.438  5788  5788 D HealthService: Received start request. Starting profile...
,08-30 07:02:39.440  5788  5788 I bt_bluedroid: get_profile_interface health
,08-30 07:02:39.441  5788  5788 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 07:02:39.441  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
08-30 07:02:39.442  5788  5788 D PanService: Received start request. Starting profile...
08-30 07:02:39.442  5788  5788 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 07:02:39.442  5788  5788 I bt_bluedroid: get_profile_interface pan
08-30 07:02:39.443  5788  5804 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 07:02:39.445  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:39.446  5788  5788 D BluetoothMapService: Received start request. Starting profile...
08-30 07:02:39.446  5788  5788 D BluetoothMapService: start()
,08-30 07:02:39.448  5788  5788 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 07:02:39.449  5788  5788 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 07:02:39.449  5788  5788 D BluetoothMapAppObserver: createReceiver()
08-30 07:02:39.450  5788  5788 D BluetoothMapAppObserver: initObservers()
08-30 07:02:39.451  5788  5788 D BluetoothMapAppObserver: getEnabledAccountItems()
08-30 07:02:39.456  5788  5788 V SapService: SapBinder()
08-30 07:02:39.456  5788  5788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:02:39.456  5788  5788 D SapService: Received start request. Starting profile...
,08-30 07:02:39.456  5788  5788 V SapService: start()
08-30 07:02:39.459  5788  5788 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:39.459  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.459  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.459  5788  5817 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 07:02:39.459  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.460  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isTurningOff()=false
,08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.461  5788  5788 V BluetoothAdapterState: isTurningOff()=false
08-30 07:02:39.462  5788  5788 V BluetoothAdapterState: isTurningOn()=true
08-30 07:02:39.462  5788  5788 V BluetoothAdapterState: isBleTurningOn()=false
08-30 07:02:39.462  5788  5788 V BluetoothAdapterState: isBleTurningOff()=false
08-30 07:02:39.462  5788  5800 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 07:02:39.462  5788  5800 D BluetoothAdapterProperties: ScanMode =  20
08-30 07:02:39.462  5788  5800 D BluetoothAdapterProperties: State =  11
08-30 07:02:39.462  5788  5800 D BluetoothAdapterProperties: Setting state to 12
08-30 07:02:39.462  5788  5800 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 07:02:39.463  5788  5800 I BluetoothAdapterState: Entering OnState
08-30 07:02:39.463  5566  5580 D BluetoothPan: onBluetoothStateChange on: true
08-30 07:02:39.463  5788  5804 D BluetoothAdapterProperties: Scan Mode:21
,08-30 07:02:39.464  5788  5804 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 07:02:39.466  5566  5577 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 07:02:39.468  5566  5566 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 07:02:39.468  5566  5566 D PanProfile: Bluetooth service connected
,08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:39.471  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 07:02:39.471  5566  5580 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 07:02:39.473   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:39.473   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:39.473  5566  5577 D BluetoothMap: onBluetoothStateChange: up=true
08-30 07:02:39.473  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 07:02:39.475  5788  5788 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 07:02:39.475  3090  3102 D BluetoothPan: onBluetoothStateChange on: true
08-30 07:02:39.476  5788  5788 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 07:02:39.477  3090  3090 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 07:02:39.477  3090  3101 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:39.477  3090  3090 D PanProfile: Bluetooth service connected
,08-30 07:02:39.478  5566  5566 D BluetoothInputDevice: Proxy object connected
,08-30 07:02:39.478  5566  5566 D HidProfile: Bluetooth service connected
08-30 07:02:39.478  5788  5788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:39.479  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:39.479  3090  3102 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 07:02:39.480  3514  3537 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:39.481  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:39.481   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 07:02:39.482   930   930 D BluetoothA2dp: Proxy object connected
08-30 07:02:39.482  3090  3755 D BluetoothMap: onBluetoothStateChange: up=true
08-30 07:02:39.484  3090  3101 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 07:02:39.484  5788  5788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 07:02:39.485  5788  5788 D ObexServerSockets: Succeed to create listening sockets 
08-30 07:02:39.485  5788  5788 D ObexServerSockets0: startAccept()
08-30 07:02:39.485  5788  5788 D ObexServerSockets0: prepareForNewConnect()
08-30 07:02:39.485  3090  3090 D BluetoothA2dp: Proxy object connected
08-30 07:02:39.485  3090  3755 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 07:02:39.487   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:39.487  3090  3090 D BluetoothInputDevice: Proxy object connected
08-30 07:02:39.487  3090  3090 D HidProfile: Bluetooth service connected
08-30 07:02:39.487  5566  5577 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 07:02:39.487  5788  5788 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 07:02:39.487  5788  5788 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 07:02:39.488  5788  5824 D ObexServerSockets0: Accepting socket connection...
,08-30 07:02:39.488  5788  5825 D ObexServerSockets0: Accepting socket connection...
08-30 07:02:39.488  3090  3090 D BluetoothMap: Proxy object connected
08-30 07:02:39.489  3090  3090 D MapProfile: Bluetooth service connected
08-30 07:02:39.489  3090  3090 D BluetoothMap: getConnectedDevices()
08-30 07:02:39.489  5566  5579 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 07:02:39.490  5566  5566 D BluetoothA2dp: Proxy object connected
08-30 07:02:39.490   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 07:02:39.491  5788  5788 D BluetoothMapService: onReceive
08-30 07:02:39.491  5788  5788 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 07:02:39.491  5788  5788 D BluetoothMapService: STATE_ON
08-30 07:02:39.493  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:39.493  5566  5566 D BluetoothMap: Proxy object connected
08-30 07:02:39.493  5566  5566 D MapProfile: Bluetooth service connected
,08-30 07:02:39.493  5566  5566 D BluetoothMap: getConnectedDevices()
08-30 07:02:39.494  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:02:39.494  5788  5828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 07:02:39.495  5788  5828 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-30 07:02:39.495  5788  5828 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-30 07:02:39.499  5566  5566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 07:02:39.505  3573  3573 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 07:02:39.506  5566  5566 D DockEventReceiver: finishStartingService: stopping service
,08-30 07:02:39.512  5566  5566 D BluetoothPbap: Proxy object connected
,08-30 07:02:39.512  5566  5566 D PbapServerProfile: Bluetooth service connected
,08-30 07:02:39.516  3090  3090 D BluetoothPbap: Proxy object connected
08-30 07:02:39.516  3090  3090 D PbapServerProfile: Bluetooth service connected
,08-30 07:02:39.517  5788  5788 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 07:02:39.517  5788  5788 D ObexServerSockets0: prepareForNewConnect()
,08-30 07:02:39.519  5788  5832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:02:39.531  5788  5836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:02:39.532  5788  5836 I BtOppRfcommListener: Accept thread started.
,08-30 07:02:39.574   930   930 D BluetoothHeadset: Proxy object connected
,08-30 07:02:39.574   930   930 D BluetoothHeadset: Proxy object connected
08-30 07:02:39.575  5566  5580 D BluetoothHeadset: Proxy object connected
08-30 07:02:39.575  3090  3101 D BluetoothHeadset: Proxy object connected
08-30 07:02:39.575  3090  3090 D HeadsetProfile: Bluetooth service connected
08-30 07:02:39.575   930   930 D BluetoothHeadset: Proxy object connected
08-30 07:02:39.576  3514  3792 D BluetoothHeadset: Proxy object connected
,08-30 07:02:39.577  5566  5566 D HeadsetProfile: Bluetooth service connected
,08-30 07:02:39.578  3090  3755 D BluetoothHeadset: Proxy object connected
08-30 07:02:39.578  3090  3090 D HeadsetProfile: Bluetooth service connected
,08-30 07:02:39.581  3514  3539 D BluetoothHeadset: Proxy object connected
,08-30 07:02:39.587   930   947 D BluetoothHeadset: Proxy object connected
,08-30 07:02:39.589  5566  5577 D BluetoothHeadset: Proxy object connected
,08-30 07:02:39.590  5566  5566 D HeadsetProfile: Bluetooth service connected
,08-30 07:02:43.009   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:43.401  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 07:02:43.409  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 07:02:43.409  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:43.409  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24f2db4 removed from the list
08-30 07:02:43.409  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 07:02:43.410  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:43.410  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:02:43.411  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:02:43.411  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8db7ddd added. We now have 4 listener(s)
08-30 07:02:43.411  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:02:43.413   930  4909 D WifiService: setWifiEnabled: false pid=5511, uid=10077
08-30 07:02:43.413   930  4909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 07:02:44.010   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:45.011   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:46.012   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:47.013   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:48.013   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 07:02:48.422  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:48.423   930  3404 D WifiService: setWifiEnabled: true pid=5511, uid=10077
,08-30 07:02:48.423   930  3404 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 07:02:48.430   507   923 D SoftapController: Softap fwReload - Ok
08-30 07:02:48.435   507   923 D CommandListener: Setting iface cfg
08-30 07:02:48.436   507   923 D CommandListener: Trying to bring down wlan0
08-30 07:02:48.438   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-30 07:02:48.442   930  2961 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-30 07:02:49.098   930  2961 D wifi    : set interface wlan0 flags (UP)
,08-30 07:02:49.103   930  2961 I WifiHAL : Initializing wifi
08-30 07:02:49.103   930  2961 I WifiHAL : Creating socket
,08-30 07:02:49.109   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 07:02:49.109   930  2961 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-30 07:02:49.109   930  2961 D wifi    : Did set static halHandle = 0x7f748cee00
08-30 07:02:49.110   930  2961 D wifi    : halHandle = 0x7f748cee00, mVM = 0x7f9080d140, mCls = 0x101512
,08-30 07:02:49.110   930  2961 D wifi    : array field set
08-30 07:02:49.110   930  2961 I WifiNative-HAL: interface[0] = wlan0
,08-30 07:02:49.114   930  5841 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547416239616
,08-30 07:02:49.114   930  5841 D wifi    : waitForHalEvents called, vm = 0x7f9080d140, obj = 0x101512, env = 0x7f75a461c0
,08-30 07:02:49.154  5842  5842 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 07:02:49.177  5842  5842 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 07:02:49.213   930  2961 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 07:02:49.222  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:49.224  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:02:49.309  5842  5842 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 07:02:49.309  5842  5842 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-30 07:02:49.331   930  2961 D WifiConfigStore: Loading config and enabling all networks 
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:49.336  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:49.338   930  2961 D WifiConfigStore: loaded 0 passpoint configs
08-30 07:02:49.339   930  2961 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 07:02:49.339  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 07:02:49.339   930  2961 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 07:02:49.340   930  2961 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 07:02:49.340   930  2961 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-30 07:02:49.340   930  2961 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 07:02:49.342  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 07:02:49.344  4181  4181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 07:02:49.344   930  2961 D WifiNative-HAL: Setting external_sim to 1
08-30 07:02:49.344  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 07:02:49.344   930  2961 D wifi    : setting dfs flag to true, 0x7f75a7ef80
08-30 07:02:49.345   930  2961 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 07:02:49.345   930  2961 D wifi    : setting scan oui 0x7f75a7ef80
08-30 07:02:49.345   930  2961 D WifiHAL : Sending mac address OUI
,08-30 07:02:49.365   930  2961 E native  : do suspend true
,08-30 07:02:49.374   930  2961 D wifi    : android_net_wifi_setLinkLayerStats: 1
,08-30 07:02:49.375   930   930 D RttService: SCAN_AVAILABLE : 3
08-30 07:02:49.375   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 07:02:49.375   930  3014 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 07:02:49.376   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:49.383   930  2949 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,08-30 07:02:49.383   930  2949 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 07:02:49.385   930  2949 D WifiNative-HAL: p2pGetDeviceAddress
08-30 07:02:49.385   930  2949 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-30 07:02:49.418   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=361951 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=25 mControllerEnergyUsed=95 }
,08-30 07:02:52.581  5842  5842 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 07:02:52.625   930  2961 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-30 07:02:52.636   930  2961 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-30 07:02:52.636   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:52.652   930  2961 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-30 07:02:52.697   930  2961 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-30 07:02:53.037  5842  5842 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 07:02:53.073  5842  5842 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 07:02:53.074  5842  5842 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 07:02:53.083   930  2961 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 07:02:53.084   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:53.084   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 07:02:53.099   930  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 07:02:53.110   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:53.115   930  2961 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 07:02:53.123   930  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 07:02:53.129   930  5847 D DhcpClient: Receive thread started
,08-30 07:02:53.223   930  2961 E native  : do suspend false
,08-30 07:02:53.243   930  5846 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 07:02:53.300   930  5847 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-30 07:02:53.301   930  5846 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-30 07:02:53.303   930  5846 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-30 07:02:53.318   930  5847 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 07:02:53.319   930  5846 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-30 07:02:53.322   507   923 D CommandListener: Setting iface cfg
,08-30 07:02:53.332   930  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 07:02:53.333   930  5846 D DhcpClient: Scheduling renewal in 86399s
08-30 07:02:53.334   930  2961 E native  : do suspend true
,08-30 07:02:53.359   930  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 07:02:53.363   930  2961 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 07:02:53.364   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 07:02:53.366   930  2961 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 07:02:53.373   930  2963 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 07:02:53.409   930  2963 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 07:02:53.409   930  2963 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 07:02:53.411   930  2963 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 07:02:53.412   930  2963 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 07:02:53.413   930  2963 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 07:02:53.419   930  2963 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 07:02:53.423   930  2963 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 07:02:53.423   930  2963 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 07:02:53.424   930  2963 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 07:02:53.424   930  2963 D ConnectivityService:    accepting network in place of null
08-30 07:02:53.424   930  2961 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 07:02:53.424   930  2963 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 07:02:53.424   930  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:53.437  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:02:53.439  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:02:53.439  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:02:53.439  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8db7ddd removed from the list
08-30 07:02:53.439  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:02:53.439  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:02:53.439  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:02:53.443  5511  5853 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-30 07:02:53.443  5511  5853 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 07:02:53.448   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:53.455   930  5845 D NetlinkSocketObserver: NeighborEvent{elapsedMs=365988, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 07:02:53.468   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 07:02:53.472   930  2963 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 07:02:53.473   930  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 07:02:53.473  3466  3723 W QCNEJ   : |CORE| network available: 102
,08-30 07:02:53.474   930  2963 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 07:02:53.474   930   947 D Tethering: MasterInitialState.processMessage what=3
08-30 07:02:53.480  3466  3723 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-30 07:02:53.481  3466  3723 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-30 07:02:53.482  3466  3723 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:53.483  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:02:53.485  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:02:53.488  3836  3836 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:02:53.490  5511  5511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:02:53.492  5511  5511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:02:53.494  4760  4793 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-30 07:02:53.494  4760  4793 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-30 07:02:53.494  4760  4793 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-30 07:02:53.494  4760  4793 E SarControlService: no key has been found,reset the power
08-30 07:02:53.494  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-30 07:02:53.495  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-30 07:02:53.495  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-30 07:02:53.495  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:53.495  4799  4799 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-30 07:02:53.497  4760  4808 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,08-30 07:02:53.497  4760  4808 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-30 07:02:53.497  4760  4808 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-30 07:02:53.497  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-30 07:02:53.498  4799  4799 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-30 07:02:53.499  3836  3836 D SystemUpdateService: onCreate
08-30 07:02:53.502  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000f003000000000000ffffffff]
08-30 07:02:53.502  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:53.502  4799  4815 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
08-30 07:02:53.503  3836  3836 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 07:02:53.503  4799  4815 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f8b0a05 HexData = [00000000f103000000000000ffffffff]
08-30 07:02:53.503  4799  4815 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-30 07:02:53.504  4799  4815 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
08-30 07:02:53.504  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:53.504  4760  4771 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-30 07:02:53.504  4799  4799 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-30 07:02:53.505  4760  4770 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-30 07:02:53.516  3836  3836 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 07:02:53.523  3836  5239 I iu.UploadsManager: num queued entries: 0
08-30 07:02:53.523  3836  5239 I iu.UploadsManager: num updated entries: 0
08-30 07:02:53.524  3836  5239 I iu.SyncManager: NEXT; no task
,08-30 07:02:53.524  3836  5858 I SystemUpdateService: active receiver: enabled
,08-30 07:02:53.527  3836  3836 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 07:02:53.528  3836  3836 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-30 07:02:53.531  5633  5633 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 07:02:53.535  5633  5633 D SprintDMHelper: simOperator: 
08-30 07:02:53.535  5633  5633 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 07:02:53.546   930  5844 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 07:02:53.561  3836  5858 I SystemUpdateService: showing system update notification
,08-30 07:02:53.572  3836  5858 V SystemUpdateService: retry (wakeup: false) in 3599953 ms
,08-30 07:02:53.574  3836  3836 D SystemUpdateService: onDestroy
,08-30 07:02:53.619   930  5844 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 11:02:53 GMT], X-Android-Received-Millis=[1472554973618], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472554973591]}
,08-30 07:02:53.619   930  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 07:02:53.620   930  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 07:02:53.620   930  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 07:02:53.621   930  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 07:02:53.658  4181  5863 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 07:02:56.453  5511  5853 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 07:02:56.453  5511  5870 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 07:02:56.455  5511  5870 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 07:02:56.455  5511  5853 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 07:02:56.455  5511  5870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 07:02:56.455  5511  5853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 07:02:56.457  5511  5870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 07:02:56.457  5511  5853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 07:02:56.458  5511  5870 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 07:02:56.459  5511  5853 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 07:02:56.462  5511  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: IncomingSocketThread/Sender)
,08-30 07:02:56.463  5511  5873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender)
,08-30 07:02:56.465  5511  5875 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
08-30 07:02:56.466  5511  5875 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
08-30 07:02:56.467  5511  5875 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 07:02:56.467  5511  5875 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 07:02:56.464  5511  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Receiver)
,08-30 07:02:56.491  5511  5874 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: IncomingSocketThread/Receiver)
,08-30 07:02:56.491  5511  5874 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 07:02:56.491  5511  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 07:02:58.014   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:59.015   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:02:59.450  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 07:02:59.452  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 07:02:59.457  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@62e7a49 Bundle[{}]
08-30 07:02:59.459  5511  5557 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 07:02:59.459  5511  5557 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 07:02:59.460  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 07:02:59.461  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 07:02:59.462  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 07:02:59.463  5511  5557 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 07:02:59.470  5511  5557 I System.out: Running OutgoingSocketThread
,08-30 07:02:59.473  5511  5876 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 07:02:59.473  5511  5876 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 07:03:00.017   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:01.018   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:01.432   930  2963 D ConnectivityService: handlePromptUnvalidated 102
,08-30 07:03:02.019   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:02.483  5511  5876 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-30 07:03:02.483  5511  5876 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 07:03:02.483  5511  5876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 07:03:02.484  5511  5876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 07:03:02.487  5511  5877 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 07:03:02.487  5511  5876 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 07:03:02.487  5511  5877 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 07:03:02.489  5511  5877 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 07:03:02.490  5511  5880 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Receiver)
,08-30 07:03:02.491  5511  5879 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
08-30 07:03:02.491  5511  5880 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Receiver)
08-30 07:03:02.491  5511  5877 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 07:03:02.492  5511  5880 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 07:03:02.492  5511  5880 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 07:03:02.493  5511  5877 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 07:03:02.495  5511  5881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
08-30 07:03:02.496  5511  5882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,08-30 07:03:02.498  5511  5882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
08-30 07:03:02.498  5511  5882 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 07:03:02.499  5511  5882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 07:03:03.020   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-30 07:03:05.482  5511  5557 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,08-30 07:03:05.483  5511  5557 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 07:03:05.483  5511  5557 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
08-30 07:03:05.489  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 07:03:05.489  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbc1d52 added. We now have 3 listener(s)
,08-30 07:03:05.492  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-30 07:03:05.492  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 07:03:05.492  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 07:03:05.493  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:03:05.493  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73a823 added. We now have 4 listener(s)
08-30 07:03:05.493  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:03:05.494  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 07:03:05.499  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:03:05.506  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:03:05.509  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:03:05.509  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:03:05.510  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:03:05.510  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:03:05.510  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:03:05.510  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:05.510  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:05.510  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:03:05.510  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 07:03:05.510  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbc1d52 removed from the list
08-30 07:03:05.510  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:05.510  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73a823 removed from the list
08-30 07:03:05.512  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:03:05.516  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:03:05.516  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 07:03:05.516  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:05.517  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:05.517  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:03:05.519  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:05.519  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:03:05.519  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:05.519  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73a823 not in the list
08-30 07:03:05.519  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:05.519  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:05.521  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:03:05.521  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:05.521  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:03:05.521  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73a823 not in the list
08-30 07:03:05.521  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:05.521  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:05.521  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:05.521  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbc1d52 not in the list
,08-30 07:03:05.523  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 07:03:05.523  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9971ad9 added. We now have 3 listener(s)
,08-30 07:03:05.525  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:03:05.525  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 07:03:05.525  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 07:03:05.526  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:03:05.526  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5abc9e added. We now have 4 listener(s)
08-30 07:03:05.526  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 07:03:05.527  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 07:03:05.530  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:03:05.536  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:03:05.538  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:05.539  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 07:03:05.539  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 07:03:05.539  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 07:03:05.539  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 07:03:05.539  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:03:05.539  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 07:03:05.543  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 07:03:05.543  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 07:03:05.543  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:03:05.548  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:03:05.548  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 07:03:05.549  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 07:03:05.549  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 07:03:05.553  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 07:03:05.553  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 07:03:05.554  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 07:03:05.554  5511  5557 D BluetoothAdapter: STATE_ON
,08-30 07:03:05.558  5788  5827 D BtGatt.GattService: registerClient() - UUID=235d13ed-584a-4914-848b-11bb0fefafe9
08-30 07:03:05.560  5788  5804 D BtGatt.GattService: onClientRegistered() - UUID=235d13ed-584a-4914-848b-11bb0fefafe9, clientIf=5
,08-30 07:03:05.561  5511  5522 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 07:03:05.562  5788  5826 D BtGatt.GattService: start scan with filters
,08-30 07:03:05.565  5788  5807 D BtGatt.ScanManager: handling starting scan
08-30 07:03:05.565  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 07:03:05.565  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 07:03:05.565  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 07:03:05.565  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 07:03:05.567  5788  5807 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aec64d
,08-30 07:03:05.568  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 07:03:05.568  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 07:03:05.569  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 07:03:05.569  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 07:03:05.572  5511  5557 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 07:03:05.572  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 07:03:05.572  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 07:03:05.572  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:05.572  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 07:03:05.572  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 07:03:05.572  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 07:03:05.572  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:03:05.572  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 07:03:05.572  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 07:03:05.572  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 07:03:05.574  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:03:05.574  5788  5804 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 07:03:05.574  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:05.575  5788  5827 D BtGatt.GattService: stopScan() - queue size =1
08-30 07:03:05.575  5788  5807 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 07:03:05.576  5788  5826 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 07:03:05.576  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 07:03:05.576  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 07:03:05.577  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 07:03:05.577  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 07:03:05.577  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 07:03:05.578  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:03:05.578  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 07:03:05.578  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 07:03:05.578  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 07:03:05.579  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 07:03:05.581  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:03:05.581  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:03:05.581  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:03:05.581  5788  5804 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-30 07:03:05.581  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:05.582  5788  5807 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 07:03:05.582  5788  5807 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 07:03:05.593  5788  5804 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 07:03:05.594  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:03:05.599  5788  5804 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 07:03:05.599  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:03:05.607  5788  5804 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-30 07:03:05.607  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:05.607  5788  5807 D BtGatt.ScanManager: stopping BLe Batch
,08-30 07:03:05.612  5788  5804 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 07:03:05.612  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:05.613  5788  5807 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 07:03:05.619  5788  5804 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 07:03:05.619  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:03:06.082  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 07:03:06.082  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:03:06.082  5511  5511 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 07:03:08.581  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:03:08.582  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 07:03:08.582  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:03:08.582  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:08.582  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:08.582  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:03:08.582  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 07:03:08.583  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9971ad9 removed from the list
08-30 07:03:08.583  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:08.583  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5abc9e removed from the list
08-30 07:03:08.583  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:03:08.583  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:08.585  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:08.585  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:08.588  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:08.588  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:03:08.588  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:08.589  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5abc9e not in the list
08-30 07:03:08.589  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:03:08.589  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:08.592  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:03:08.592  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:08.592  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:08.592  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5abc9e not in the list
08-30 07:03:08.593  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 07:03:08.593  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:08.593  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:08.593  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9971ad9 not in the list
,08-30 07:03:08.594  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 07:03:08.595  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db3f89b added. We now have 3 listener(s)
08-30 07:03:08.599  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:03:08.599  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 07:03:08.599  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 07:03:08.599  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 07:03:08.599  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e424438 added. We now have 4 listener(s)
08-30 07:03:08.599  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 07:03:08.600  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 07:03:08.603  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:03:08.608  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:03:08.610  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:08.610  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:03:08.610  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 07:03:08.611  5511  5557 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 07:03:08.611  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 07:03:08.611  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 07:03:08.611  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 07:03:08.611  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 07:03:08.611  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:03:08.612  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 07:03:08.613  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 07:03:08.613  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 07:03:08.613  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 07:03:08.613  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:03:08.613  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 07:03:08.613  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:03:08.613  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 07:03:08.616  5511  5883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 07:03:08.618  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 07:03:08.618  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 07:03:08.619  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:03:08.619  5511  5511 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 07:03:08.620  5511  5883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 07:03:08.623  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 07:03:08.624  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 07:03:08.624  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 07:03:08.625  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-30 07:03:08.626  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:03:08.626  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
08-30 07:03:08.627  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 07:03:08.627  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 07:03:08.627  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 07:03:08.628  5511  5557 D BluetoothAdapter: STATE_ON
,08-30 07:03:08.633  5788  5816 D BtGatt.GattService: registerClient() - UUID=9e0ce8f5-52d9-479c-af5b-01d0247d5273
08-30 07:03:08.633  5788  5804 D BtGatt.GattService: onClientRegistered() - UUID=9e0ce8f5-52d9-479c-af5b-01d0247d5273, clientIf=5
,08-30 07:03:08.633  5511  5522 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 07:03:08.635  5788  5806 D BtGatt.AdvertiseManager: message : 0
,08-30 07:03:08.638  5788  5806 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 07:03:08.648  5788  5804 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 07:03:08.655  5788  5804 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 07:03:08.656  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 07:03:08.656  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 07:03:08.658  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 07:03:08.659  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 07:03:08.659  5511  5511 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 07:03:08.659  5511  5511 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-30 07:03:08.659  5511  5511 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 07:03:08.659  5511  5511 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 07:03:08.659  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-30 07:03:08.661  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 07:03:08.662  5511  5511 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 07:03:08.662  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 07:03:09.163  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 07:03:09.163  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 07:03:09.163  5511  5511 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 07:03:11.662  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:03:11.662  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-30 07:03:11.663  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 07:03:11.663  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 07:03:11.663  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 07:03:11.663  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 07:03:11.664  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 07:03:11.664  5511  5883 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 07:03:11.664  5511  5557 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 07:03:11.664  5511  5883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 07:03:11.664  5511  5883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 07:03:11.664  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 07:03:11.664  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 07:03:11.664  5511  5511 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 07:03:11.664  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:03:11.664  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 07:03:11.665  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 07:03:11.668  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:03:11.668  5511  5557 D BluetoothLeScanner: could not find callback wrapper
08-30 07:03:11.668  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 07:03:11.669  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 07:03:11.671  5788  5806 D BtGatt.AdvertiseManager: message : 1
08-30 07:03:11.672  5788  5806 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 07:03:11.683  5788  5804 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 07:03:11.684  5788  5804 D BtGatt.GattService: Client app is not null!
08-30 07:03:11.685  5788  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 07:03:11.685  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 07:03:11.686  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 07:03:11.686  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 07:03:11.686  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-30 07:03:11.686  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-30 07:03:11.688  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 07:03:11.688  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 07:03:11.688  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 07:03:11.689  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 07:03:11.691  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 07:03:11.692  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:03:11.692  5511  5511 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 07:03:11.692  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:03:11.692  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 07:03:11.692  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db3f89b removed from the list
08-30 07:03:11.692  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:11.692  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e424438 removed from the list
,08-30 07:03:11.692  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:03:11.692  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:03:11.692  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:11.693  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 07:03:11.693  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:03:11.693  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:11.693  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:11.695  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:11.695  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:03:11.695  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:11.695  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e424438 not in the list
08-30 07:03:11.696  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:11.696  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:11.698  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 07:03:11.698  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:11.698  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:11.698  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e424438 not in the list
08-30 07:03:11.698  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:11.698  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:03:11.698  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:11.698  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db3f89b not in the list
08-30 07:03:11.699  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 07:03:11.700  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dc984d added. We now have 3 listener(s)
08-30 07:03:11.702  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:03:11.702  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 07:03:11.702  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 07:03:11.703  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:03:11.703  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de27f02 added. We now have 4 listener(s)
08-30 07:03:11.703  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 07:03:11.704  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 07:03:11.708  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:03:11.713  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 07:03:11.715  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:11.715  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:03:11.715  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 07:03:11.715  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 07:03:11.715  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 07:03:11.716  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:03:11.716  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 07:03:11.718  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:03:11.720  5511  5557 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 07:03:11.720  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 07:03:11.721  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 07:03:11.725  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 07:03:11.725  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 07:03:11.726  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 07:03:11.729  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 07:03:11.729  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 07:03:11.730  5511  5557 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 07:03:11.730  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:03:11.732  5788  5799 D BtGatt.GattService: registerClient() - UUID=66b65270-03fe-4dfe-8c2d-2dd8e073054e
08-30 07:03:11.733  5788  5804 D BtGatt.GattService: onClientRegistered() - UUID=66b65270-03fe-4dfe-8c2d-2dd8e073054e, clientIf=5
,08-30 07:03:11.733  5511  5522 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 07:03:11.733  5788  5816 D BtGatt.GattService: start scan with filters
,08-30 07:03:11.736  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 07:03:11.736  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 07:03:11.737  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 07:03:11.737  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 07:03:11.737  5788  5807 D BtGatt.ScanManager: handling starting scan
,08-30 07:03:11.739  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 07:03:11.739  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 07:03:11.739  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 07:03:11.740  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 07:03:11.744  5788  5804 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 07:03:11.744  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:11.744  5788  5807 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 07:03:11.749  5788  5804 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-30 07:03:11.749  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:11.750  5788  5807 D BtGatt.ScanManager: Starting BLE batch scan
08-30 07:03:11.750  5788  5807 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 07:03:11.759  5788  5804 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 07:03:11.759  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:03:11.764  5788  5804 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 07:03:11.764  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 07:03:12.193  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 07:03:12.240  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 07:03:12.241  5511  5511 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 07:03:12.241  5511  5511 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 07:03:14.750  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 07:03:14.750  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 07:03:14.750  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 07:03:14.750  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.751  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 07:03:14.751  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 07:03:14.751  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 07:03:14.751  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 07:03:14.751  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 07:03:14.752  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 07:03:14.752  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 07:03:14.753  5511  5557 D BluetoothAdapter: STATE_ON
08-30 07:03:14.755  5788  5798 D BtGatt.GattService: stopScan() - queue size =1
,08-30 07:03:14.757  5788  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 07:03:14.758  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 07:03:14.758  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 07:03:14.758  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 07:03:14.758  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 07:03:14.758  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 07:03:14.760  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:03:14.760  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 07:03:14.760  5511  5557 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 07:03:14.760  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 07:03:14.763  5788  5788 D BtGatt.ScanManager: awakened up at time 387296
08-30 07:03:14.763  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:03:14.766  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:14.765  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:03:14.766  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.766  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:03:14.766  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 07:03:14.766  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dc984d removed from the list
08-30 07:03:14.766  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:14.766  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de27f02 removed from the list
08-30 07:03:14.766  5511  5511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 07:03:14.767  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:03:14.767  5511  5511 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 07:03:14.767  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:03:14.769  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.769  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:14.772  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 07:03:14.772  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:03:14.772  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:03:14.773  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de27f02 not in the list
,08-30 07:03:14.773  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.773  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:14.774  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:03:14.774  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:14.774  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:14.774  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de27f02 not in the list
08-30 07:03:14.774  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:14.774  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.774  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:14.774  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dc984d not in the list
08-30 07:03:14.775  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 07:03:14.775  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69d6a6f added. We now have 3 listener(s)
08-30 07:03:14.777  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-30 07:03:14.777  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 07:03:14.777  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 07:03:14.777  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 07:03:14.777  5788  5804 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-30 07:03:14.777  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:14.777  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84e537c added. We now have 4 listener(s)
08-30 07:03:14.777  5511  5557 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 07:03:14.777  5788  5807 D BtGatt.ScanManager: stopping BLe Batch
,08-30 07:03:14.778  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 07:03:14.781  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 07:03:14.784  5788  5804 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 07:03:14.784  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:14.784  5788  5807 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 07:03:14.786  5511  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 07:03:14.788  5511  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 07:03:14.788  5511  5557 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 07:03:14.789  5511  5557 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 07:03:14.789  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 07:03:14.789  5511  5557 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 07:03:14.789  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:14.789  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.789  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 07:03:14.789  5511  5557 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 07:03:14.789  5511  5557 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69d6a6f removed from the list
08-30 07:03:14.789  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 07:03:14.789  5511  5557 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84e537c removed from the list
08-30 07:03:14.791  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:03:14.791  5511  5557 D io.jxcore.node.ConnectivityMonitor: stop
08-30 07:03:14.791  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 07:03:14.792  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 07:03:14.792  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:14.795  5511  5511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 07:03:14.796  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:14.796  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:03:14.796  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:14.796  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84e537c not in the list
,08-30 07:03:14.796  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.797  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:14.797  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 07:03:14.798  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 07:03:14.798  5511  5557 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 07:03:14.798  5511  5557 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84e537c not in the list
08-30 07:03:14.798  5511  5557 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 07:03:14.798  5511  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 07:03:14.798  5511  5557 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 07:03:14.798  5511  5557 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69d6a6f not in the list
,08-30 07:03:14.799  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 07:03:14.799  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 07:03:14.799  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 07:03:14.799  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 07:03:14.799  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 07:03:14.799  5511  5557 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 07:03:14.802  5788  5804 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-30 07:03:14.802  5788  5804 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 07:03:14.802  5788  5804 D BtGatt.GattService: current time is 387335687298
,08-30 07:03:14.802  5788  5804 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -77, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -77, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 07:03:14.803  5788  5804 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 07:03:14.804  5788  5804 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 07:03:14.804  5788  5804 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-30 07:03:14.804  5788  5804 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-30 07:03:14.805  5788  5804 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 07:03:14.805  5788  5804 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-30 07:03:15.268  5511  5511 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 07:03:16.810  5511  5884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,08-30 07:03:18.021   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:18.809  5511  5557 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,08-30 07:03:18.809  5511  5557 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,08-30 07:03:18.813  5511  5885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
08-30 07:03:18.814  5511  5885 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
08-30 07:03:18.814  5511  5885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-30 07:03:18.818  5511  5557 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 07:03:18.825  5511  5886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,08-30 07:03:18.825  5511  5886 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
,08-30 07:03:18.825  5511  5886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 07:03:18.831  5511  5557 I jxcore-log: Total number of executed tests:  82
08-30 07:03:18.831  5511  5557 I jxcore-log: 
,08-30 07:03:18.832  5511  5557 I jxcore-log: Number of passed tests:  82
08-30 07:03:18.832  5511  5557 I jxcore-log: 
,08-30 07:03:18.832  5511  5557 I jxcore-log: Number of failed tests:  0
08-30 07:03:18.832  5511  5557 I jxcore-log: 
08-30 07:03:18.832  5511  5557 I jxcore-log: Number of ignored tests:  0
08-30 07:03:18.832  5511  5557 I jxcore-log: 
08-30 07:03:18.832  5511  5557 I jxcore-log: Total duration:  100863
08-30 07:03:18.832  5511  5557 I jxcore-log: 
,08-30 07:03:18.838  5511  5557 I jxcore-log: Unit Test app is loaded
08-30 07:03:18.838  5511  5557 I jxcore-log: 
,08-30 07:03:18.850  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.850  5511  5557 I jxcore-log: 
,08-30 07:03:18.857  5511  5511 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 07:03:18.857  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.857  5511  5557 I jxcore-log: 
,08-30 07:03:18.858  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.858  5511  5557 I jxcore-log: 
,08-30 07:03:18.860  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.860  5511  5557 I jxcore-log: 
08-30 07:03:18.861  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 07:03:18.861  5511  5557 I jxcore-log: 
08-30 07:03:18.863  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 07:03:18.863  5511  5557 I jxcore-log: 
08-30 07:03:18.866  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.866  5511  5557 I jxcore-log: 
,08-30 07:03:18.869  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.869  5511  5557 I jxcore-log: 
,08-30 07:03:18.870  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 07:03:18.870  5511  5557 I jxcore-log: 
,08-30 07:03:18.871  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 07:03:18.871  5511  5557 I jxcore-log: 
,08-30 07:03:18.872  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 07:03:18.872  5511  5557 I jxcore-log: 
,08-30 07:03:18.873  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.873  5511  5557 I jxcore-log: 
,08-30 07:03:18.874  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.874  5511  5557 I jxcore-log: 
,08-30 07:03:18.875  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.875  5511  5557 I jxcore-log: 
,08-30 07:03:18.876  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.876  5511  5557 I jxcore-log: 
,08-30 07:03:18.878  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.878  5511  5557 I jxcore-log: 
,08-30 07:03:18.879  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.879  5511  5557 I jxcore-log: 
08-30 07:03:18.881  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.881  5511  5557 I jxcore-log: 
08-30 07:03:18.882  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.882  5511  5557 I jxcore-log: 
08-30 07:03:18.882  5511  5884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
08-30 07:03:18.882  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.882  5511  5557 I jxcore-log: 
08-30 07:03:18.884  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.884  5511  5557 I jxcore-log: 
,08-30 07:03:18.885  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.885  5511  5557 I jxcore-log: 
,08-30 07:03:18.886  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.886  5511  5557 I jxcore-log: 
,08-30 07:03:18.887  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.887  5511  5557 I jxcore-log: 
,08-30 07:03:18.888  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.888  5511  5557 I jxcore-log: 
,08-30 07:03:18.889  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.889  5511  5557 I jxcore-log: 
,08-30 07:03:18.890  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.890  5511  5557 I jxcore-log: 
,08-30 07:03:18.891  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.891  5511  5557 I jxcore-log: 
08-30 07:03:18.891  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.891  5511  5557 I jxcore-log: 
08-30 07:03:18.892  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.892  5511  5557 I jxcore-log: 
08-30 07:03:18.893  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.893  5511  5557 I jxcore-log: 
08-30 07:03:18.893  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.893  5511  5557 I jxcore-log: 
08-30 07:03:18.894  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.894  5511  5557 I jxcore-log: 
08-30 07:03:18.894  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.894  5511  5557 I jxcore-log: 
08-30 07:03:18.895  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.895  5511  5557 I jxcore-log: 
,08-30 07:03:18.895  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.895  5511  5557 I jxcore-log: 
08-30 07:03:18.895  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.895  5511  5557 I jxcore-log: 
08-30 07:03:18.896  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.896  5511  5557 I jxcore-log: 
08-30 07:03:18.896  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 07:03:18.896  5511  5557 I jxcore-log: 
,08-30 07:03:18.897  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.897  5511  5557 I jxcore-log: 
,08-30 07:03:18.898  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 07:03:18.898  5511  5557 I jxcore-log: 
08-30 07:03:18.899  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.899  5511  5557 I jxcore-log: 
08-30 07:03:18.900  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.900  5511  5557 I jxcore-log: 
08-30 07:03:18.901  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.901  5511  5557 I jxcore-log: 
08-30 07:03:18.901  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.901  5511  5557 I jxcore-log: 
08-30 07:03:18.902  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.902  5511  5557 I jxcore-log: 
08-30 07:03:18.902  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 07:03:18.902  5511  5557 I jxcore-log: 
08-30 07:03:18.903  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.903  5511  5557 I jxcore-log: 
08-30 07:03:18.904  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 07:03:18.904  5511  5557 I jxcore-log: 
08-30 07:03:18.904  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.904  5511  5557 I jxcore-log: 
08-30 07:03:18.905  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 07:03:18.905  5511  5557 I jxcore-log: 
08-30 07:03:18.905  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 07:03:18.905  5511  5557 I jxcore-log: 
08-30 07:03:18.906  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 07:03:18.906  5511  5557 I jxcore-log: 
08-30 07:03:18.906  5511  5557 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 07:03:18.906  5511  5557 I jxcore-log: 
,08-30 07:03:18.909  5511  5557 I jxcore-log: My device name is: Huawei-Nexus 6P
08-30 07:03:18.909  5511  5557 I jxcore-log: 
08-30 07:03:18.910  5511  5557 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 07:03:18.910  5511  5557 I jxcore-log: 
,08-30 07:03:19.022   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:20.023   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:20.631  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 07:03:20.631  5511  5557 I jxcore-log: 
,08-30 07:03:20.928  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 07:03:20.928  5511  5557 I jxcore-log: 
,08-30 07:03:20.947  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 07:03:20.947  5511  5557 I jxcore-log: 
,08-30 07:03:21.024   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:21.895  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 07:03:21.895  5511  5557 I jxcore-log: 
,08-30 07:03:22.025   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 07:03:22.050  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-30 07:03:22.050  5511  5557 I jxcore-log: 
,08-30 07:03:22.053  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-30 07:03:22.053  5511  5557 I jxcore-log: 
,08-30 07:03:22.057  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
08-30 07:03:22.057  5511  5557 I jxcore-log: 
,08-30 07:03:22.101  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-30 07:03:22.101  5511  5557 I jxcore-log: 
,08-30 07:03:22.114  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-30 07:03:22.114  5511  5557 I jxcore-log: 
,08-30 07:03:22.118  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
08-30 07:03:22.118  5511  5557 I jxcore-log: 
,08-30 07:03:22.769  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
08-30 07:03:22.769  5511  5557 I jxcore-log: 
,08-30 07:03:22.880  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-30 07:03:22.880  5511  5557 I jxcore-log: 
,08-30 07:03:23.025   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-30 07:03:23.107  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-30 07:03:23.107  5511  5557 I jxcore-log: 
,08-30 07:03:23.116  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-30 07:03:23.116  5511  5557 I jxcore-log: 
,08-30 07:03:23.123  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-30 07:03:23.123  5511  5557 I jxcore-log: 
,08-30 07:03:23.127  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-30 07:03:23.127  5511  5557 I jxcore-log: 
,08-30 07:03:23.152  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-30 07:03:23.152  5511  5557 I jxcore-log: 
,08-30 07:03:23.181  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-30 07:03:23.181  5511  5557 I jxcore-log: 
,08-30 07:03:23.186  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-30 07:03:23.186  5511  5557 I jxcore-log: 
,08-30 07:03:23.192  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-30 07:03:23.192  5511  5557 I jxcore-log: 
,08-30 07:03:23.205  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-30 07:03:23.205  5511  5557 I jxcore-log: 
,08-30 07:03:23.208  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-30 07:03:23.208  5511  5557 I jxcore-log: 
,08-30 07:03:23.212  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-30 07:03:23.212  5511  5557 I jxcore-log: 
,08-30 07:03:23.222  5511  5557 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-30 07:03:23.222  5511  5557 I jxcore-log: 
,08-30 07:03:23.302  5511  5557 I jxcore-log: ERROR runTests: 
08-30 07:03:23.302  5511  5557 I jxcore-log: 
,08-30 07:03:23.305  5511  5557 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-30 07:03:23.305  5511  5557 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 07:03:23.306  5511  5557 I jxcore-log: WARN testUtils: logCallback not set!
08-30 07:03:23.306  5511  5557 I jxcore-log: 
,08-30 07:03:23.313  5511  5557 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _functionName: 'loadFile',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _lineNumber: '26',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _columnNumber: '11',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 07:03:23.313  5511  5557 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _functionName: '',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _lineNumber: '38',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _columnNumber: '7',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 07:03:23.313  5511  5557 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _functionName: '',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _lineNumber: '35',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _columnNumber: '3',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 07:03:23.313  5511  5557 I jxcore-log:   { _fileName: 'module.js',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _lineNumber: '621',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _columnNumber: '8',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 07:03:23.313  5511  5557 I jxcore-log:   { _fileName: 'module.js',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _lineNumber: '651',
08-30 07:03:23.313  5511  5557 I jxcore-log:     _columnNumber: '1',
08-30 07:03:23.313  5511  5557 I jxcore-log:    
,08-30 07:03:23.313  5511  5557 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 07:03:23.313  5511  5557 I jxcore-log: 
08-30 07:03:23.314  5511  5557 E jxcore-log: Error: 
08-30 07:03:23.314  5511  5557 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-30 07:03:23.314  5511  5557 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 07:03:23.314  5511  5557 E jxcore-log: 
,08-30 07:03:23.796  5887  5887 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 07:03:23.802  5887  5887 D AndroidRuntime: CheckJNI is OFF
,08-30 07:03:23.837  5887  5887 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 07:03:23.871  5887  5887 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 07:03:23.888  5887  5887 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 07:03:23.895   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-30 07:03:23.896   930   943 I ActivityManager: Killing 5511:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-30 07:03:23.988   930  3541 D GraphicsStats: Buffer count: 2
,08-30 07:03:23.988   930  3413 I WindowState: WIN DEATH: Window{e68adc7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 07:03:23.989   930  2962 D WifiService: Client connection lost with reason: 4
,08-30 07:03:24.034   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-30 07:03:24.034   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 07:03:24.035   930   953 I art     : Starting a blocking GC Explicit
,08-30 07:03:24.036   930   943 E ActivityManager: Failure starting process com.test.thalitest
08-30 07:03:24.036   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 07:03:24.036   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:03:24.036   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:03:24.036   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 07:03:24.036   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 07:03:24.036   930   943 I ActivityManager:   Force finishing activity ActivityRecord{386f900 u0 com.test.thalitest/.MainActivity t4}
,08-30 07:03:24.041   930   941 W ActivityManager: Spurious death for ProcessRecord{d73f667 0:com.test.thalitest/u0a77}, curProc for 5511: null
,08-30 07:03:24.115   930   953 I art     : Explicit concurrent mark sweep GC freed 49976(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 1.604ms total 80.282ms
,08-30 07:03:24.135   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 07:03:24.138  5887  5887 I art     : System.exit called, status: 0
,08-30 07:03:24.138  5887  5887 I AndroidRuntime: VM exiting with result code 0.
,08-30 07:03:24.153   930   953 I ActivityManager: Start proc 5897:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-30 07:03:24.154   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-30 07:03:24.161   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 07:03:24.165  5788  5788 D BluetoothMapAppObserver: onReceive
08-30 07:03:24.166  5788  5788 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 07:03:24.167  3446  3879 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 07:03:24.173  3375  3375 I Keyboard.Facilitator: resetDictionaries() : en_US
08-30 07:03:24.176   930  2942 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 07:03:24.198  3375  5909 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 07:03:24.201  4773  5910 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 07:03:24.208  3375  5909 I Decoder : createOrResetDecoder
,08-30 07:03:24.210  3514  3514 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 07:03:24.206    27    27 W kworker/1:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 07:03:24.216    27    27 W kworker/1:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 07:03:24.232   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 07:03:24.226    27    27 W kworker/1:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 07:03:24.242  4773  5910 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-30 07:03:24.243  4773  5910 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 07:03:24.243  4773  5910 E AndroidRuntime: Process: android.process.acore, PID: 4773
08-30 07:03:24.243  4773  5910 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:03:24.243  4773  5910 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 07:03:24.293   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 07:03:24.295   930   942 E PackageManager: Failed to write settings, restoring backup
08-30 07:03:24.295   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 07:03:24.295   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 07:03:24.295   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 07:03:24.295   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 07:03:24.295   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 07:03:24.295   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 07:03:24.295   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:03:24.295   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 07:03:24.298  3573  3573 I ConfigService: onCreate
,08-30 07:03:24.303  3540  3635 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 07:03:24.303   930   943 E DropBoxManagerService: Can't write: system_server_wtf
08-30 07:03:24.303   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 07:03:24.303   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 07:03:24.303   930   943 E DropBoxManagerService: 	... 13 more
,08-30 07:03:24.303  3573  5915 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 07:03:24.303  3573  5915 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: Can't write: system_app_crash
08-30 07:03:24.304   930  5913 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 07:03:24.304   930  5913 E DropBoxManagerService: 	... 5 more
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the data,base in read/write mode.
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 07:03:24.304  3573  5915 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 07:03:24.304  4773  5910 I Process : Sending signal. PID: 4773 SIG: 9
08-30 07:03:24.305  3573  5915 W SQLiteOpenHelper: Opened config.db in read-only mode
08-30 07:03:24.315   930  3548 I ActivityManager: Start proc 5917:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-30 07:03:24.316  3540  3635 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 07:03:24.316  3540  3635 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3540
08-30 07:03:24.316  3540  3635 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 07:03:24.316  3540  3635 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 07:03:24.318   930  4908 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 07:03:24.320   930  5922 E DropBoxManagerService: Can't write: system_app_crash
08-30 07:03:24.320   930  5922 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 07:03:24.320   930  5922 E DropBoxManagerService: 	... 5 more
08-30 07:03:24.320   379   379 E lowmemorykiller: Error writing /proc/4773/oom_score_adj; errno=22

```
