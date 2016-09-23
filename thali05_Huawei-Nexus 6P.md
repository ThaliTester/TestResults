#### Test 8326889395f7d73_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 06:58:14.607   928  5216 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 06:58:15.083  5470  5470 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 06:58:15.089  5470  5470 D AndroidRuntime: CheckJNI is OFF
09-23 06:58:15.117  5470  5470 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 06:58:15.152  5470  5470 I Radio-JNI: register_android_hardware_Radio DONE
09-23 06:58:15.170  5470  5470 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 06:58:15.175   928  3635 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 06:58:15.216   928  3635 I ActivityManager: Start proc 5479:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 06:58:15.230  5470  5470 D AndroidRuntime: Shutting down VM
,09-23 06:58:15.559   928  3242 I WindowManager: Screenshot max retries 4 of Token{5f64796 ActivityRecord{9be96b1 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{9c06ae9 u0 Starting com.test.thalitest} drawState=2
,09-23 06:58:15.625  5479  5479 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 06:58:15.661  5479  5479 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 06:58:15.684  5479  5479 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 3083-3101)
,09-23 06:58:15.684  5479  5479 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 06:58:15.704  5479  5479 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {71ce9b9}
,09-23 06:58:15.705  5479  5479 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 06:58:15.705  5479  5479 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 06:58:15.710  5479  5479 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-23 06:58:15.711  5479  5479 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 06:58:15.745  5479  5479 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 06:58:15.762  5479  5479 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 06:58:15.763  5479  5479 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 06:58:15.763  5479  5479 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 06:58:15.763  5479  5479 I Adreno  : Build Date                       : 12/06/15
09-23 06:58:15.763  5479  5479 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 06:58:15.763  5479  5479 I Adreno  : Local Branch                     : mybranch17112971
09-23 06:58:15.763  5479  5479 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 06:58:15.763  5479  5479 I Adreno  : Remote Branch                    : NONE
09-23 06:58:15.763  5479  5479 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 06:58:15.808   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8ae134:true
,09-23 06:58:15.841   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26354]" dev="sockfs" ino=26354 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:15.841   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26354]" dev="sockfs" ino=26354 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:15.852  5479  5479 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 06:58:15.861  5479  5479 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 06:58:15.881   406   406 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32080]" dev="sockfs" ino=32080 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:15.881   406   406 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32080]" dev="sockfs" ino=32080 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:15.885  5479  5516 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 06:58:15.884  3599  3599 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15247]" dev="sockfs" ino=15247 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:15.884  3599  3599 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15247]" dev="sockfs" ino=15247 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:15.892  5479  5503 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 06:58:15.912  5479  5516 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 06:58:15.988   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +427ms (total +800ms)
,09-23 06:58:16.034  5479  5479 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5479
,09-23 06:58:16.152  5479  5479 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 06:58:16.240  5479  5518 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -566494928
,09-23 06:58:16.244  5479  5518 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 06:58:16.244  5479  5518 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 06:58:16.244  5479  5518 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 06:58:16.244  5479  5518 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 06:58:16.244  5479  5518 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 06:58:16.244  5479  5518 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25bd517 added. We now have 1 listener(s)
,09-23 06:58:16.248  5479  5518 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 06:58:16.249  5479  5518 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:16.249  5479  5518 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 06:58:16.250  5479  5518 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 06:58:16.251  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 06:58:16.252  5479  5518 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea9b522 added. We now have 1 listener(s)
09-23 06:58:16.252  5479  5518 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 06:58:16.256   928  2989 D WifiService: New client listening to asynchronous messages
,09-23 06:58:16.257  5479  5518 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 06:58:16.257  5479  5518 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 06:58:16.257  5479  5518 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 06:58:16.257  5479  5518 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 06:58:16.257  5479  5518 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 06:58:16.259  5479  5518 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:16.259  5479  5518 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 06:58:16.263  5479  5518 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:16.263  5479  5518 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:58:16.263  5479  5518 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 06:58:16.263  5479  5518 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 06:58:16.263  5479  5518 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 06:58:16.359  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:16.364  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:16.368  5479  5479 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 06:58:16.539  5479  5525 W jxcore-log: Initializing JXcore engine
,09-23 06:58:16.540  5479  5525 W jxcore-log: JXcore engine is ready
,09-23 06:58:16.561  5525  5525 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13001 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 06:58:16.561  5525  5525 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14366]" dev="sockfs" ino=14366 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 06:58:16.561  5525  5525 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 06:58:16.561  5525  5525 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32058]" dev="sockfs" ino=32058 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 06:58:16.571  5479  5525 W jxcore-log: Starting JXcore engine
,09-23 06:58:16.583  5479  5488 I art     : Background sticky concurrent mark sweep GC freed 81364(8MB) AllocSpace objects, 18(1604KB) LOS objects, 22% free, 25MB/32MB, paused 931us total 100.163ms
,09-23 06:58:16.624  5479  5525 W jxcore-log: Platform android
09-23 06:58:16.624  5479  5525 W jxcore-log: 
,09-23 06:58:16.624  5479  5525 W jxcore-log: Process ARCH arm
09-23 06:58:16.624  5479  5525 W jxcore-log: 
,09-23 06:58:16.729  5479  5525 I jxcore-log: JXcore Cordova bridge is ready!
09-23 06:58:16.729  5479  5525 I jxcore-log: 
,09-23 06:58:16.729  5479  5525 W jxcore-log: JXcore engine is started
,09-23 06:58:16.735  5479  5518 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 06:58:16.738  5479  5479 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 06:58:21.127   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:58:22.128   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:58:23.129   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:58:23.301  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 06:58:23.301  5479  5525 I jxcore-log: 
,09-23 06:58:23.302  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 06:58:23.302  5479  5525 I jxcore-log: 
,09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:23.306  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:58:23.308  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:23.309  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 06:58:23.309  5479  5525 I jxcore-log: 
09-23 06:58:23.310  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 06:58:23.310  5479  5525 I jxcore-log: 
,09-23 06:58:23.655  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:58:23.656  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bef2bd3 added. We now have 2 listener(s)
09-23 06:58:23.656  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:23.657  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:58:23.657  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:58:23.657  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:58:23.657  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c622310 added. We now have 2 listener(s)
09-23 06:58:23.657  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:58:23.657  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 06:58:23.659  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:23.662  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:58:23.667  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:58:23.667  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:58:23.668  5479  5525 D ExecuteNativeTests: Running unit tests
09-23 06:58:23.671  5479  5525 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 06:58:23.672   928  3599 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-23 06:58:23.672   928  3599 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:58:23.673  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:23.679  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:24.130   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:58:25.131   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:58:26.132   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 06:58:33.681  5479  5525 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 06:58:33.746  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:58:33.746  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5052922 added. We now have 3 listener(s)
09-23 06:58:33.747  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 06:58:33.747  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 06:58:33.747  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:58:33.747  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:58:33.748  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8070fb3 added. We now have 3 listener(s)
09-23 06:58:33.748  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 06:58:33.749  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 06:58:33.752  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:33.756  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:58:33.757  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:33.758  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:58:33.766  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:33.767  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-23 06:58:33.768  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:58:33.768  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:33.768  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:33.768  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:33.769  5479  5525 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 06:58:33.770  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 06:58:33.770  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:58:33.770  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:33.770  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:33.770  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:33.770  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-23 06:58:33.771  5479  5525 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-23 06:58:33.772  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-23 06:58:33.774  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-23 06:58:33.774  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:58:33.774  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:33.775  5479  5525 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:58:33.775  5479  5525 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-23 06:58:33.775  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 06:58:33.775  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:33.775  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:58:33.775  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:58:33.775  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:58:33.776  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:58:33.777  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:58:33.777  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:58:33.777  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:58:33.777  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:58:33.777  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:33.777  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:58:33.777  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:58:33.779  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:58:33.780  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:58:33.781  5479  5527 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:33.782  5479  5527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 06:58:33.778  4705  4705 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15270]" dev="sockfs" ino=15270 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:33.785  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:58:33.778  4705  4705 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[15270]" dev="sockfs" ino=15270 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:33.787  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:58:33.787  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:58:33.788  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:58:33.788  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:33.788  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-23 06:58:33.789  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:33.789  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:33.789  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 06:58:33.789  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:33.793  4499  4697 D BtGatt.GattService: registerClient() - UUID=de19dfd9-dd93-46e7-93a5-0e03b60ab074
,09-23 06:58:33.793  4499  4561 D BtGatt.GattService: onClientRegistered() - UUID=de19dfd9-dd93-46e7-93a5-0e03b60ab074, clientIf=5
,09-23 06:58:33.794  5479  5490 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:58:33.797  4499  4563 D BtGatt.AdvertiseManager: message : 0
,09-23 06:58:33.800  4499  4563 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:58:33.816  4499  4561 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:58:33.825  4499  4561 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:58:33.826  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 06:58:33.826  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:58:33.827  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:58:33.828  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:58:33.828  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 06:58:33.828  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-23 06:58:33.828  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:58:33.829  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:58:33.829  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:58:33.829  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:58:33.832  5479  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:58:33.832  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:58:33.897   928  2988 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 06:58:34.331  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 06:58:34.331  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 06:58:34.331  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-23 06:58:34.331  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 06:58:34.332  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 06:58:34.333  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 06:58:34.334  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 06:58:34.334  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 06:58:34.334  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-23 06:58:34.334  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:58:34.336  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 06:58:34.336  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 06:58:34.336  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:58:34.336  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:58:34.336  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:58:34.337  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:58:34.337  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:58:34.337  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:58:34.337  5479  5527 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:58:34.338  5479  5527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:58:34.338  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:58:34.338  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 06:58:34.338  5479  5527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:58:34.338  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:58:34.339  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:58:34.339  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:58:34.340  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:34.340  5479  5525 D BluetoothLeScanner: could not find callback wrapper
,09-23 06:58:34.340  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:34.340  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:58:34.342  4499  4563 D BtGatt.AdvertiseManager: message : 1
09-23 06:58:34.343  4499  4563 D BtGatt.AdvertiseManager: stop advertise for client 5
09-23 06:58:34.356  4499  4561 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:58:34.356  4499  4561 D BtGatt.GattService: Client app is not null!
,09-23 06:58:34.360  4499  4697 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:58:34.360  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:58:34.361  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:58:34.361  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:58:34.361  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:58:34.361  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:58:34.366  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:34.366  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 06:58:34.366  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:58:34.368  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 06:58:34.369  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:58:34.370  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:58:34.370  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:34.370  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 06:58:34.370  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:34.370  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:34.371  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-23 06:58:34.374  4513  4513 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28363]" dev="sockfs" ino=28363 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:34.374  4513  4513 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28363]" dev="sockfs" ino=28363 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:34.371  5479  5525 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:58:34.372  5479  5525 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-23 06:58:34.372  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-23 06:58:34.373  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:34.373  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-23 06:58:34.373  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:58:34.373  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:34.374  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:58:34.375  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:58:34.375  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:58:34.375  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-23 06:58:34.375  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:58:34.375  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:58:34.375  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:34.375  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:58:34.376  5479  5530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:34.379  5479  5530 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:58:34.379  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:58:34.379  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:58:34.385  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:58:34.385  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:58:34.385  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:58:34.388  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 06:58:34.388  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:34.388  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-23 06:58:34.389  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:34.389  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:34.389  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 06:58:34.390  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:34.394  4499  4513 D BtGatt.GattService: registerClient() - UUID=d635af8f-7f13-489b-a63f-32dc770f56ff
09-23 06:58:34.395  4499  4561 D BtGatt.GattService: onClientRegistered() - UUID=d635af8f-7f13-489b-a63f-32dc770f56ff, clientIf=5
,09-23 06:58:34.395  5479  5490 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:58:34.396  4499  4563 D BtGatt.AdvertiseManager: message : 0
,09-23 06:58:34.399  4499  4563 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:58:34.411  4499  4561 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:58:34.419  4499  4561 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:58:34.420  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:58:34.420  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 06:58:34.422  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:58:34.425  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 06:58:34.425  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:34.425  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:58:34.425  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:58:34.425  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:58:34.425  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:58:34.425  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:58:34.429  5479  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:58:34.429  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:58:34.929  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-23 06:58:34.930  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:58:34.930  5479  5525 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:58:34.930  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:58:34.930  5479  5525 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 06:58:34.930  5479  5525 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-23 06:58:34.930  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 06:58:34.931  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 06:58:34.933  4499  4563 D BtGatt.AdvertiseManager: message : 1
,09-23 06:58:34.934  4499  4563 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:58:34.950  4499  4561 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:58:34.950  4499  4561 D BtGatt.GattService: Client app is not null!
,09-23 06:58:34.950  4499  4705 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:58:34.951  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:58:34.951  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 06:58:34.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:58:34.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:58:34.951  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:34.952  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-23 06:58:34.952  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:34.952  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:34.952  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 06:58:34.953  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:34.956  4499  4512 D BtGatt.GattService: registerClient() - UUID=5022769f-52aa-481e-95db-94aa1429d204
09-23 06:58:34.957  4499  4561 D BtGatt.GattService: onClientRegistered() - UUID=5022769f-52aa-481e-95db-94aa1429d204, clientIf=5
09-23 06:58:34.957  5479  5490 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:58:34.958  4499  4563 D BtGatt.AdvertiseManager: message : 0
,09-23 06:58:34.962  4499  4563 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:58:34.975  4499  4561 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:58:34.983  4499  4561 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:58:34.983  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 06:58:34.983  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:58:34.983  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:58:34.984  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:58:34.984  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 06:58:34.984  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 06:58:34.984  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:58:34.984  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:58:34.984  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:58:34.986  5479  5525 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 06:58:34.986  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 06:58:34.986  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 06:58:34.986  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 06:58:34.987  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:58:34.987  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:58:34.987  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:58:34.987  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:58:34.987  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-23 06:58:34.987  5479  5530 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:58:34.987  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:58:34.987  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:58:34.987  5479  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:58:34.987  5479  5530 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:58:34.987  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:58:34.987  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:58:34.987  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:58:34.988  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:34.988  5479  5525 D BluetoothLeScanner: could not find callback wrapper
09-23 06:58:34.989  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:34.989  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:58:34.990  4499  4563 D BtGatt.AdvertiseManager: message : 1
09-23 06:58:34.990  4499  4563 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:58:34.998  4499  4561 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:58:34.998  4499  4561 D BtGatt.GattService: Client app is not null!
,09-23 06:58:34.999  4499  4512 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:58:34.999  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:58:34.999  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:58:34.999  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:58:34.999  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:58:34.999  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 06:58:35.001  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:35.001  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:58:35.001  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:58:35.001  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 06:58:35.003  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:58:35.003  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:58:35.003  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:58:35.003  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:35.003  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:35.003  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:58:35.005  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-23 06:58:35.005  5479  5525 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-23 06:58:35.006  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-23 06:58:35.007  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 06:58:35.008  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-23 06:58:35.008  5479  5525 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 06:58:35.009  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-23 06:58:35.009  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-23 06:58:35.010  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-23 06:58:35.010  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:58:35.010  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:35.010  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:35.010  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:35.010  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:58:35.010  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:35.011  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:35.011  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:35.011  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:58:35.011  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:35.011  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:35.011  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:58:35.012  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-23 06:58:35.012  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:58:35.012  5479  5525 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 06:58:35.012  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 06:58:35.016  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:58:35.016  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-23 06:58:35.016  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 06:58:35.016  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 06:58:35.016  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 06:58:35.017  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 06:58:35.018  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 06:58:35.018  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-23 06:58:35.019  5479  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:58:35.019  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 06:58:35.019  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:58:35.019  5479  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:58:35.019  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 06:58:35.019  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:58:35.019  5479  5525 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:58:35.019  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-23 06:58:35.024  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-23 06:58:35.025  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-23 06:58:35.025  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-23 06:58:35.025  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 06:58:35.026  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-23 06:58:35.026  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-23 06:58:35.026  5479  5525 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:58:35.026  5479  5525 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 06:58:35.028  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-23 06:58:35.029  5479  5525 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 06:58:35.029  5479  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
09-23 06:58:35.028  4512  4512 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29317]" dev="sockfs" ino=29317 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:35.028  4512  4512 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29317]" dev="sockfs" ino=29317 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:35.029  5479  5534 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-23 06:58:35.029  5479  5534 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:35.031  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-23 06:58:35.032  5479  5525 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-23 06:58:35.034  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-23 06:58:35.034  5479  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 06:58:35.034  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 06:58:35.034  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:58:35.035  5479  5525 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 06:58:35.035  5479  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 06:58:35.035  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 06:58:35.035  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:58:35.035  5479  5525 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 06:58:35.035  5479  5525 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 06:58:35.035  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 06:58:35.035  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:58:35.035  5479  5525 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 06:58:35.036  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-23 06:58:35.036  5479  5525 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:58:35.036  5479  5525 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:58:35.037  5479  5525 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-23 06:58:35.037  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-23 06:58:35.037  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:35.037  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:58:35.037  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:58:35.037  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:35.038  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:58:35.040  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:58:35.040  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:58:35.040  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:58:35.040  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:58:35.040  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:58:35.040  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:35.041  4697  4697 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32110]" dev="sockfs" ino=32110 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:35.040  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:58:35.041  5479  5535 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:35.044  5479  5535 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:58:35.044  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:58:35.044  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:58:35.041  4697  4697 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32110]" dev="sockfs" ino=32110 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:35.047  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:58:35.048  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:58:35.048  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:58:35.049  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:58:35.049  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:35.050  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-23 06:58:35.050  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:35.050  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:35.050  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:58:35.050  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:35.052  4499  4697 D BtGatt.GattService: registerClient() - UUID=c488ae19-c055-4c21-865e-3d298b5b0fbd
09-23 06:58:35.052  4499  4561 D BtGatt.GattService: onClientRegistered() - UUID=c488ae19-c055-4c21-865e-3d298b5b0fbd, clientIf=5
09-23 06:58:35.053  5479  5490 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:58:35.054  4499  4563 D BtGatt.AdvertiseManager: message : 0
09-23 06:58:35.056  4499  4563 D BtGatt.AdvertiseManager: starting multi advertising
09-23 06:58:35.065  4499  4561 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-23 06:58:35.071  4499  4561 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-23 06:58:35.071  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:58:35.072  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:58:35.073  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:58:35.074  5479  5525 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:58:35.074  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 06:58:35.074  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-23 06:58:35.075  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:58:35.075  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:58:35.075  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:58:35.075  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:58:35.077  5479  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:58:35.077  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:58:35.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 06:58:35.578  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:58:35.576  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 06:58:35.590  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:58:35.590  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:58:35.590  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 06:58:35.590  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-23 06:58:35.591  5479  5535 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:58:35.591  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 06:58:35.591  5479  5535 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:58:35.591  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:58:35.591  5479  5535 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:58:35.591  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 06:58:35.591  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:58:35.594  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5052922 removed from the list
,09-23 06:58:35.594  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:58:35.594  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:58:35.594  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:58:35.594  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:58:35.595  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:58:35.595  5479  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
09-23 06:58:35.596  5479  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 129)
09-23 06:58:35.596  5479  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 129)
,09-23 06:58:35.597  5479  5534 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
09-23 06:58:35.597  4499  4695 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-23 06:58:35.599  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:35.600  5479  5525 D BluetoothLeScanner: could not find callback wrapper
09-23 06:58:35.600  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:35.600  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:58:35.601  4499  4563 D BtGatt.AdvertiseManager: message : 1
,09-23 06:58:35.603  4499  4563 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:58:35.611  4499  4561 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:58:35.611  4499  4561 D BtGatt.GattService: Client app is not null!
,09-23 06:58:35.612  4499  4512 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:58:35.613  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:58:35.613  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:58:35.613  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 06:58:35.613  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:58:35.613  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:58:35.614  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:35.615  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:58:35.615  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:58:35.615  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:58:35.617  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 06:58:35.617  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:35.617  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:35.618  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8070fb3 removed from the list
09-23 06:58:35.618  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:58:35.618  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:58:35.620  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
09-23 06:58:35.621  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:58:35.621  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:58:35.622  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:58:35.623  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:58:35.623  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:58:35.623  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
09-23 06:58:35.623  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:58:35.623  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:58:35.624  5479  5537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:35.624  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
09-23 06:58:35.624  4513  4513 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32118]" dev="sockfs" ino=32118 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:35.624  4513  4513 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32118]" dev="sockfs" ino=32118 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:35.625  5479  5525 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-23 06:58:35.625  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 06:58:35.625  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-23 06:58:35.626  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:58:35.626  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-23 06:58:35.626  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-23 06:58:35.630  5479  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:58:35.630  5479  5525 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,09-23 06:58:35.631  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:58:35.631  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:58:35.631  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:58:35.631  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:58:35.631  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 06:58:35.631  5479  5537 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:58:35.631  5479  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:58:35.631  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:58:35.631  5479  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:58:35.631  5479  5525 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5052922 not in the list
09-23 06:58:35.631  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 06:58:35.631  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:58:35.631  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:58:35.631  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:58:35.631  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:58:35.631  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 06:58:35.632  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:58:35.632  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:58:35.633  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:35.634  5479  5525 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8070fb3 not in the list
09-23 06:58:35.634  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:35.634  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:58:35.634  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 06:58:35.634  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:35.634  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:58:35.634  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:35.635  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-23 06:58:35.635  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-23 06:58:35.635  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:58:35.635  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 06:58:35.635  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-23 06:58:35.635  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-23 06:58:35.635  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:58:35.636  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-23 06:58:35.637  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
09-23 06:58:35.638  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-23 06:58:35.638  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 06:58:35.638  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-23 06:58:35.639  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,09-23 06:58:35.639  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-23 06:58:35.639  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-23 06:58:35.639  5479  5525 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-23 06:58:35.639  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 06:58:35.640  5479  5525 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-23 06:58:35.640  5479  5525 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-23 06:58:35.640  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-23 06:58:35.641  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-23 06:58:35.641  5479  5525 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 06:58:35.641  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-23 06:58:35.641  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 06:58:35.641  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-23 06:58:35.642  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 06:58:35.642  5479  5525 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-23 06:58:35.642  5479  5525 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-23 06:58:35.642  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:58:35.643  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef34ba3 added. We now have 3 listener(s)
09-23 06:58:35.644  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:35.644  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:58:35.644  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:58:35.644  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:58:35.644  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50ea0 added. We now have 3 listener(s)
09-23 06:58:35.644  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:58:35.645  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 06:58:35.647  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:35.650  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:58:35.652  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:35.652  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:58:35.653  5479  5525 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 06:58:35.653   928   939 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-23 06:58:35.654   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:58:35.655  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:35.655  5479  5525 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
09-23 06:58:35.657  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:35.657  5479  5525 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,09-23 06:58:35.658  5479  5525 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-23 06:58:35.661   928  3635 D WifiService: setWifiEnabled: false pid=5479, uid=10077
09-23 06:58:35.661   928  3635 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:58:35.663   928  2988 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-23 06:58:35.663   928  2988 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-23 06:58:35.663   928  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 06:58:35.663   928  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:58:35.670   928  5217 D DhcpClient: Clearing IP address
,09-23 06:58:35.670   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:58:35.678   507   921 D CommandListener: Setting iface cfg
,09-23 06:58:35.684  3672  5271 V NativeCrypto: Read error: ssl=0x7f90b66000: I/O error during system call, Connection timed out
09-23 06:58:35.686  3672  5271 V NativeCrypto: SSL shutdown failed: ssl=0x7f90b66000: I/O error during system call, Broken pipe
,09-23 06:58:35.688   928  3620 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-23 06:58:35.689   928  5215 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-23 06:58:35.692   928  5215 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-23 06:58:35.692   928  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-23 06:58:35.693   928  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 06:58:35.694   928  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-23 06:58:35.695   928  5218 D DhcpClient: Receive thread stopped
09-23 06:58:35.697   928  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-23 06:58:35.697   928  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-23 06:58:35.700   533   533 E Parcel  : Reading a NULL string not supported here.
,09-23 06:58:35.703   928   928 D RttService: SCAN_AVAILABLE : 1
09-23 06:58:35.703   928  3096 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 06:58:35.707   928  2990 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 06:58:35.709  3535  3695 W QCNEJ   : |CORE| network lost: 100
09-23 06:58:35.709  3535  3695 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-23 06:58:35.735   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:58:35.749   928  2988 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 06:58:35.749   928  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:58:35.766   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:58:35.766   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:58:35.767   928  2990 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-23 06:58:35.767   928  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 06:58:35.767   507   921 D TetherController: Setting IP forward enable = 0
,09-23 06:58:35.770   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-23 06:58:35.773   928  2988 D DhcpClient: doQuit
09-23 06:58:35.773   928  2988 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 06:58:35.773   928  5217 D DhcpClient: onQuitting
09-23 06:58:35.774  3646  3646 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:35.781  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:35.784  3933  3933 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-23 06:58:35.785  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:35.788  4921  4936 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 06:58:35.788  4921  4936 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 06:58:35.788  4921  4936 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 06:58:35.788  4921  4936 E SarControlService: no key has been found,reset the power
09-23 06:58:35.789  4921  4962 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 06:58:35.789  4921  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 06:58:35.789  4921  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 06:58:35.789  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:58:35.789  4950  4950 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:35.791  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:35.791  4921  4962 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 06:58:35.791  4921  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 06:58:35.791  4921  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 06:58:35.792  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:58:35.792  4950  4950 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 06:58:35.793  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:35.797  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:35.798  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dc86403 HexData = [00000000ea03000000000000ffffffff]
09-23 06:58:35.798  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:58:35.799  4950  4964 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,09-23 06:58:35.799  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:58:35.799  4921  4933 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 06:58:35.800  3933  3933 D SystemUpdateService: onCreate
09-23 06:58:35.801  3646  3646 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 06:58:35.802  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:35.803  3933  3933 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 06:58:35.804  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dc86403 HexData = [00000000eb03000000000000ffffffff]
09-23 06:58:35.805  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:58:35.805  4950  4964 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-23 06:58:35.805  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:58:35.806  4921  4932 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:35.806  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:35.808  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:35.809  3646  3646 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-23 06:58:35.812  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:35.814  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:35.816  3933  5556 I SystemUpdateService: active receiver: enabled
09-23 06:58:35.818  3933  3933 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 06:58:35.825  3933  3933 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 06:58:35.826  3933  3933 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 06:58:35.829  3933  5242 I iu.UploadsManager: num queued entries: 0
09-23 06:58:35.830  3933  5556 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 06:58:35.831  3933  5242 I iu.UploadsManager: num updated entries: 0
,09-23 06:58:35.834   507   914 W SocketClient: write error (Broken pipe)
,09-23 06:58:35.834   507   914 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-23 06:58:35.834   507   914 W SocketListener: Error sending broadcast (Broken pipe)
09-23 06:58:35.836  3933  5556 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-23 06:58:35.837  3933  5556 I SystemUpdateService: now status is 0 (complete)
09-23 06:58:35.837  3933  5556 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 06:58:35.837  3933  5556 I SystemUpdateService: file has been verified
09-23 06:58:35.837  3933  5556 I SystemUpdateService: OTA package size = 21989297
,09-23 06:58:35.839   928  3435 I ActivityManager: Start proc 5559:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-23 06:58:35.845  3933  5242 I iu.SyncManager: NEXT; no task
,09-23 06:58:35.845  3933  5556 I SystemUpdateService: showing system update notification
,09-23 06:58:35.853   507   921 E Netd    : netlink response contains error (No such file or directory)
09-23 06:58:35.855   507   921 D TetherController: Setting IP forward enable = 0
,09-23 06:58:35.856   928  2990 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 06:58:35.859  3933  3933 D SystemUpdateService: onDestroy
,09-23 06:58:35.871  3646  3646 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 06:58:35.880  5559  5559 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-23 06:58:35.883  5559  5559 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 06:58:35.890  5559  5559 D SprintDMHelper: simOperator: 
09-23 06:58:35.890  5559  5559 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 06:58:35.893  3646  3646 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:58:35.898   928  2988 D wifi    : In wifi stop Hal
09-23 06:58:35.898   928  2988 D wifi    : halHandle = 0x7f8f984ae0, mVM = 0x7fabb0d140, mCls = 0x100af6
09-23 06:58:35.898   928  3645 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 06:58:35.898   928  3645 D WifiHAL : Got a signal to exit!!!
09-23 06:58:35.898   928  3645 I WifiHAL : Exit wifi_event_loop
09-23 06:58:35.899   928  2988 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-23 06:58:35.899   928  2988 E WifiHAL : Event processing terminated
09-23 06:58:35.899   928  2988 D wifi    : In wifi cleaned up handler
09-23 06:58:35.899   928  2988 I WifiHAL : Internal cleanup completed
,09-23 06:58:35.902  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:35.904  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:35.906  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:35.907  3516  4052 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:58:35.911  4316  4316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:58:35.915  4316  5574 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 06:58:35.923   928  3645 D wifi    : set interface wlan0 flags (DOWN)
09-23 06:58:35.924   928  2988 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 06:58:35.927   928  3242 I ActivityManager: Start proc 5575:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 06:58:35.929   928  3242 I ActivityManager: Killing 4884:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 06:58:35.961  5575  5575 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 06:58:35.968   928   939 I ActivityManager: Killing 5001:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-23 06:58:36.132   928   945 D Tethering: InitialState.processMessage what=4
,09-23 06:58:36.135  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 06:58:36.142   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 06:58:36.165  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:36.168   928  3432 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-23 06:58:36.168   928  3432 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:58:36.173   507   921 D SoftapController: Softap fwReload - Ok
,09-23 06:58:36.176   507   921 D CommandListener: Setting iface cfg
09-23 06:58:36.177   507   921 D CommandListener: Trying to bring down wlan0
,09-23 06:58:36.178   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:58:36.181   928  2988 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:58:36.673   928  3599 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-23 06:58:36.674   928  3599 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:58:36.798   928  2988 D wifi    : set interface wlan0 flags (UP)
,09-23 06:58:36.799   928  2988 I WifiHAL : Initializing wifi
09-23 06:58:36.799   928  2988 I WifiHAL : Creating socket
,09-23 06:58:36.805   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 06:58:36.810   928  2988 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 06:58:36.810   928  2988 D wifi    : Did set static halHandle = 0x7f8f984ae0
,09-23 06:58:36.810   928  2988 D wifi    : halHandle = 0x7f8f984ae0, mVM = 0x7fabb0d140, mCls = 0x10180e
,09-23 06:58:36.810   928  2988 D wifi    : array field set
,09-23 06:58:36.811   928  2988 I WifiNative-HAL: interface[0] = wlan0
,09-23 06:58:36.813   928  5590 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547869969120
09-23 06:58:36.813   928  5590 D wifi    : waitForHalEvents called, vm = 0x7fabb0d140, obj = 0x10180e, env = 0x7f91e5f180
,09-23 06:58:36.898  5591  5591 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 06:58:36.920  5591  5591 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:58:36.920   928  2988 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-23 06:58:36.927  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:36.930  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:36.931  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:36.936  5591  5591 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:58:36.936  5591  5591 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 06:58:36.951   928  2988 D WifiConfigStore: Loading config and enabling all networks 
,09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:36.955  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:36.956  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:36.959  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:36.961  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:36.966  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:36.966   928  2988 D WifiConfigStore: loaded 0 passpoint configs
09-23 06:58:36.966   928  2988 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:58:36.967   928  2988 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-23 06:58:36.968   928  2988 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-23 06:58:36.968  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:36.969   928  2988 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:58:36.969   928  2988 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 06:58:36.970   928  2988 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-23 06:58:36.970   928  2988 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 06:58:36.973   928  2988 D WifiNative-HAL: Setting external_sim to 1
,09-23 06:58:36.973  4316  4316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:58:36.973   928  2988 D wifi    : setting dfs flag to true, 0x7f96574f60
09-23 06:58:36.974   928  2988 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 06:58:36.974   928  2988 D wifi    : setting scan oui 0x7f96574f60
09-23 06:58:36.974   928  2988 D WifiHAL : Sending mac address OUI
,09-23 06:58:36.978   928  2988 E native  : do suspend false
,09-23 06:58:36.984   928  2988 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 06:58:36.984   928   928 D RttService: SCAN_AVAILABLE : 3
09-23 06:58:36.984   928  3096 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:58:36.984   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 06:58:36.985   507   921 D CommandListener: Setting iface cfg
,09-23 06:58:36.988   928  2987 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
09-23 06:58:36.989   928  2987 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 06:58:36.997   928  2987 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 06:58:37.001   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=204418 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-23 06:58:37.002   928  2987 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 06:58:37.179  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:37.188  4499  4557 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 06:58:37.188  4499  4557 D BluetoothAdapterProperties: Setting state to 13
,09-23 06:58:37.188  4499  4557 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 06:58:37.190  4499  4557 D BluetoothAdapterProperties: onBluetoothDisable()
,09-23 06:58:37.191  4499  4557 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:58:37.194  4499  4499 D BluetoothMapService: onReceive
,09-23 06:58:37.195  4499  4499 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:58:37.195  4499  4499 D BluetoothMapService: STATE_TURNING_OFF
09-23 06:58:37.195  4499  4499 D BluetoothMapService: MAP Service closeService in
09-23 06:58:37.195  4499  4499 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 06:58:37.195  4499  4499 D ObexServerSockets0: shutdown(block = true)
09-23 06:58:37.196  4499  4499 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:58:37.196  4499  4499 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:58:37.196  4499  4717 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 06:58:37.196  4499  4718 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 06:58:37.197  4499  4695 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 06:58:37.197  4499  4499 I BtOppRfcommListener: stopping Accept Thread
09-23 06:58:37.198  4499  5168 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 06:58:37.198  4499  5168 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 06:58:37.200  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:37.200  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:37.201  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:37.201  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:37.204  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:37.204  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:37.205  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:37.205  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:37.208  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:37.209  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:37.209  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:37.210  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:37.214   928   941 I ActivityManager: Start proc 5595:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-23 06:58:37.215  4499  4561 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:58:37.215  4499  4557 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 06:58:37.220  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:37.221  4499  4499 D HeadsetService: Received stop request...Stopping profile...
09-23 06:58:37.221  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:37.223  3145  3734 D BluetoothHeadset: Proxy object disconnected
09-23 06:58:37.223  4499  4499 D A2dpService: Received stop request...Stopping profile...
09-23 06:58:37.223  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:37.224  4499  4700 D A2dpStateMachine: Exit Disconnected: -1
09-23 06:58:37.224  3587  3961 D BluetoothHeadset: Proxy object disconnected
09-23 06:58:37.224   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 06:58:37.224   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 06:58:37.224   928   928 D BluetoothHeadset: Proxy object disconnected
,09-23 06:58:37.225  3145  3145 D HeadsetProfile: Bluetooth service disconnected
09-23 06:58:37.228   928   928 D BluetoothA2dp: Proxy object disconnected
,09-23 06:58:37.228  4499  4499 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:37.228  4499  4499 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.228  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:37.228  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.229  3145  3145 D BluetoothA2dp: Proxy object disconnected
,09-23 06:58:37.231  4499  4499 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 06:58:37.231  4499  4499 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 06:58:37.231  4499  4561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 06:58:37.231  4499  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:37.232  4499  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:37.232  4499  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:37.232  4499  4561 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 06:58:37.232  4499  4499 D HidService: Received stop request...Stopping profile...
09-23 06:58:37.232  4499  4499 D HidService: Stopping Bluetooth HidService
09-23 06:58:37.234  3145  3145 D BluetoothInputDevice: Proxy object disconnected
09-23 06:58:37.234  4499  4499 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:37.234  3145  3145 D HidProfile: Bluetooth service disconnected
,09-23 06:58:37.234  4499  4499 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.234  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:37.234  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.234  4499  4499 D HealthService: Received stop request...Stopping profile...
09-23 06:58:37.236  4499  4561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-23 06:58:37.236  4499  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:37.237  4499  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:37.237  4499  4690 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:58:37.237  4499  4690 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:58:37.237  4499  4499 D PanService: Received stop request...Stopping profile...
09-23 06:58:37.237  4499  4690 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:58:37.237  4499  4690 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-23 06:58:37.238  3145  3145 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:58:37.238  4499  4499 D BluetoothMapService: Received stop request...Stopping profile...
09-23 06:58:37.238  3145  3145 D PanProfile: Bluetooth service disconnected
09-23 06:58:37.238  4499  4499 D BluetoothMapService: stop()
,09-23 06:58:37.239  4499  4499 D BluetoothMapAppObserver: deinitObservers()
09-23 06:58:37.239  4499  4499 D BluetoothMapAppObserver: removeReceiver()
09-23 06:58:37.241  3145  3145 D BluetoothMap: Proxy object disconnected
09-23 06:58:37.241  3145  3145 D MapProfile: Bluetooth service disconnected
09-23 06:58:37.242  4499  4499 D SapService: Received stop request...Stopping profile...
09-23 06:58:37.242  4499  4499 V SapService: stop()
09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.245  4499  4499 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 06:58:37.245  4499  4499 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isTurningOn()=false
,09-23 06:58:37.245  4499  4561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:37.245  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.246  4499  4499 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 06:58:37.246  4499  4561 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-23 06:58:37.247  4499  4499 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 06:58:37.247  4499  4499 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:37.247  4499  4499 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.247  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:37.247  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.248  4499  4499 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 06:58:37.248  4499  4499 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-23 06:58:37.251  4499  4499 D BluetoothMapService: MAP Service closeService in
,09-23 06:58:37.251  4499  4499 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:58:37.251  4499  4499 V BluetoothAdapterState: isTurningOn()=false
,09-23 06:58:37.251  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:58:37.251  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.252  4499  4499 D BluetoothMapService: cleanup()
09-23 06:58:37.252  4499  4499 D BluetoothMapService: MAP Service closeService in
09-23 06:58:37.252  4499  4499 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:37.252  4499  4499 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.252  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:37.252  4499  4499 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.252  4499  4557 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 06:58:37.252  4499  4557 D BluetoothAdapterProperties: Setting state to 15
09-23 06:58:37.252  4499  4557 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-23 06:58:37.253  4499  4557 I BluetoothAdapterState: Entering BleOnState
09-23 06:58:37.256  3145  3163 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-23 06:58:37.257  3145  3636 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:58:37.257   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:37.257   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:37.257   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:58:37.258  3145  3734 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:58:37.258  3145  3157 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:58:37.259  3587  3842 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:37.260  3145  3163 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:58:37.260  3145  3636 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:37.260   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:37.261  4499  4557 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 06:58:37.261  4499  4557 D BluetoothAdapterProperties: Setting state to 16
09-23 06:58:37.261  4499  4557 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 06:58:37.262  4499  4557 D BluetoothAdapterProperties: onBleDisable
09-23 06:58:37.262  4499  4557 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:58:37.262  4499  4558 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 06:58:37.264  4499  4690 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 06:58:37.264  4499  4690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:37.264  4499  4561 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:58:37.266  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:37.267  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:37.270  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:37.274  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:37.277  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:37.278  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:37.284  5595  5595 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-23 06:58:37.295  5595  5595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:58:37.299   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8677948:true
,09-23 06:58:37.300  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:58:37.315   928   938 I ActivityManager: Start proc 5607:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 06:58:37.329  5595  5595 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 06:58:37.332  5595  5595 D BluetoothMap: Create BluetoothMap proxy object
,09-23 06:58:37.342  5595  5595 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 06:58:37.354  5607  5607 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 06:58:37.358  5595  5595 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:58:37.366   928  3242 I ActivityManager: Killing 5292:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-23 06:58:37.470  4499  4561 I bt_hci  : shut_down
,09-23 06:58:37.472  4499  4566 D bt_hwcfg: hw_epilog_process
09-23 06:58:37.473  4499  4566 I bt_vendor: low_power_mode_cb
,09-23 06:58:37.475  4499  4566 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 06:58:37.475  4499  4566 I bt_vendor: epilog_cb
09-23 06:58:37.475  4499  4566 I bt_hci  : epilog_finished_callback
,09-23 06:58:37.478  4499  4561 I bt_hci_h4: hal_close
,09-23 06:58:37.479  4499  4561 I bt_userial_vendor: device fd = 54 close
,09-23 06:58:37.562  5607  5607 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.562  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.563  5607  5607 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:58:37.563  5607  5607 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:58:37.567  5595  5595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:58:37.573  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:58:37.577  5595  5595 D DockEventReceiver: finishStartingService: stopping service
09-23 06:58:37.580   928   939 I ActivityManager: Killing 4571:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 06:58:37.617  4499  4558 D bt_stack_manager: event_shut_down_stack finished.
09-23 06:58:37.618  4499  4557 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 06:58:37.620  4499  4557 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 06:58:37.620  4499  4499 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:58:37.621  4499  4499 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 06:58:37.621  4499  4499 D BtGatt.GattService: stop()
09-23 06:58:37.621  4499  4499 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 06:58:37.622  4499  4499 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:37.622  4499  4499 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.623  4499  4499 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:37.623  4499  4499 V BluetoothAdapterState: isBleTurningOff()=true
09-23 06:58:37.623  4499  4557 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 06:58:37.623  4499  4557 D BluetoothAdapterProperties: Setting state to 10
09-23 06:58:37.623  4499  4557 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 06:58:37.624  4499  4557 I BluetoothAdapterState: Entering OffState
09-23 06:58:37.624   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-23 06:58:37.630  4499  4499 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 06:58:37.630  4499  4499 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 06:58:37.631  4499  4499 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 06:58:37.632  4499  4558 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-23 06:58:37.640  4499  4499 I art     : System.exit called, status: 0
09-23 06:58:37.640  4499  4499 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 06:58:37.684   928  3143 I ActivityManager: Process com.android.bluetooth (pid 4499) has died
,09-23 06:58:37.687  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:37.700   928   945 I ActivityManager: Start proc 5639:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 06:58:37.760  5639  5639 D AdapterServiceConfig: Adding HeadsetService
,09-23 06:58:37.760  5639  5639 D AdapterServiceConfig: Adding A2dpService
09-23 06:58:37.761  5639  5639 D AdapterServiceConfig: Adding HidService
09-23 06:58:37.761  5639  5639 D AdapterServiceConfig: Adding HealthService
09-23 06:58:37.761  5639  5639 D AdapterServiceConfig: Adding PanService
09-23 06:58:37.761  5639  5639 D AdapterServiceConfig: Adding GattService
09-23 06:58:37.761  5639  5639 D AdapterServiceConfig: Adding BluetoothMapService
,09-23 06:58:37.761  5639  5639 D AdapterServiceConfig: Adding SapService
,09-23 06:58:37.770   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b5aaf89:true
,09-23 06:58:37.770  5639  5639 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 06:58:37.772  5639  5639 I bt_bluedroid: init
,09-23 06:58:37.773  5639  5651 I BluetoothAdapterState: Entering OffState
,09-23 06:58:37.774  5639  5652 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 06:58:37.774  5639  5652 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 06:58:37.774  5639  5652 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 06:58:37.774  5639  5652 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 06:58:37.775  5639  5639 I bt_bluedroid: get_profile_interface socket
,09-23 06:58:37.776  5639  5655 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:58:37.776  5639  5639 I bt_bluedroid: get_profile_interface sdp
,09-23 06:58:37.778  5639  5655 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:58:37.781  5639  5650 I bt_bluedroid: config_hci_snoop_log
,09-23 06:58:37.781   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-23 06:58:37.785  5639  5651 D BluetoothAdapterState: Current state: OFF, message: 0
,09-23 06:58:37.785  5639  5651 D BluetoothAdapterProperties: Setting state to 14
,09-23 06:58:37.785  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 06:58:37.786  5639  5651 D BluetoothBondStateMachine: make
09-23 06:58:37.787  5639  5656 I BluetoothBondStateMachine: StableState(): Entering Off State
09-23 06:58:37.790  5639  5651 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:58:37.790  5639  5639 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 06:58:37.792  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:37.792  5639  5639 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:58:37.792  5639  5639 D BtGatt.GattService: Received start request. Starting profile...
09-23 06:58:37.792  5639  5639 D BtGatt.GattService: start()
09-23 06:58:37.792  5639  5639 I bt_bluedroid: get_profile_interface gatt
,09-23 06:58:37.793  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:37.793  5639  5639 D BtGatt.AdvertiseManager: advertise manager created
,09-23 06:58:37.797  5639  5639 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:58:37.797  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:37.797  5639  5639 V BluetoothAdapterState: isBleTurningOn()=true
09-23 06:58:37.797  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:37.798  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 06:58:37.800  5639  5651 I bt_bluedroid: bt_bluedroid
,09-23 06:58:37.800  5639  5652 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 06:58:37.800  5639  5652 I bt_hci  : start_up
,09-23 06:58:37.805  5639  5652 I bt_vendor: alloc value 0xf3ccf871
,09-23 06:58:37.805  5639  5652 I bt_vendor: init
09-23 06:58:37.805  5639  5652 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 06:58:37.805  5639  5652 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
09-23 06:58:37.805  5607  5625 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 06:58:37.827   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6089e66:true
,09-23 06:58:37.913  5639  5652 D bt_hci  : start_up starting async portion
09-23 06:58:37.911  5662  5662 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:58:37.913  5639  5659 I bt_hci  : event_finish_startup
09-23 06:58:37.913  5639  5659 I bt_hci_h4: hal_open
09-23 06:58:37.913  5639  5659 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-23 06:58:37.914  5639  5659 I bt_userial_vendor: device fd = 54 open
,09-23 06:58:37.926  5639  5659 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:58:37.928  5639  5659 D bt_hwcfg: Chipset BCM4358A3
,09-23 06:58:37.928  5639  5659 D bt_hwcfg: Target name = [BCM4358A3]
09-23 06:58:37.929  5639  5659 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 06:58:38.196  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 06:58:38.309  5639  5659 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 06:58:38.309  5639  5659 D bt_hwcfg: Settlement delay -- 100 ms
09-23 06:58:38.309  5639  5659 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 06:58:38.432  5639  5659 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:58:38.433  5639  5659 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 06:58:38.434  5639  5659 I bt_hwcfg: vendor lib fwcfg completed
09-23 06:58:38.434  5639  5659 I bt_vendor: firmware callback
09-23 06:58:38.434  5639  5659 I bt_hci  : firmware_config_callback
,09-23 06:58:38.443  5639  5664 I bt_btu  : btu_task pending for preload complete event
,09-23 06:58:38.443  5639  5664 I bt_btu_task: Bluetooth chip preload is complete
,09-23 06:58:38.443  5639  5664 I bt_btu  : btu_task received preload complete event
,09-23 06:58:38.450  5639  5664 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_A2D
,09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 06:58:38.451  5639  5664 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 06:58:38.452  5639  5664 I         : BTE_InitTraceLevels -- TRC_PAN
,09-23 06:58:38.452  5639  5664 I         : BTE_InitTraceLevels -- TRC_SDP
09-23 06:58:38.452  5639  5664 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 06:58:38.452  5639  5664 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 06:58:38.452  5639  5664 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 06:58:38.452  5639  5664 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 06:58:38.538  5639  5664 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c4d549
,09-23 06:58:38.538  5639  5664 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c4d549 
,09-23 06:58:38.559  5639  5655 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 06:58:38.560  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:58:38.561  5639  5655 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:58:38.564  5639  5655 D BluetoothAdapterProperties: Name is: Nexus 6P
09-23 06:58:38.567  5639  5655 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:58:38.567  5639  5655 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-23 06:58:38.567  5639  5655 D bt_hci  : do_postload posting postload work item
,09-23 06:58:38.567  5639  5659 I bt_hci  : event_postload
09-23 06:58:38.568  5639  5659 I bt_vendor: sco_config_cb
09-23 06:58:38.568  5639  5659 I bt_hci  : sco_config_callback postload finished.
09-23 06:58:38.571  5639  5655 D bt_bte_conf: Device ID record 1 : primary
,09-23 06:58:38.571  5639  5655 D bt_bte_conf:   vendorId            = 000f
09-23 06:58:38.571  5639  5655 D bt_bte_conf:   vendorIdSource      = 0001
09-23 06:58:38.571  5639  5655 D bt_bte_conf:   product             = 1200
09-23 06:58:38.571  5639  5655 D bt_bte_conf:   version             = 1436
09-23 06:58:38.571  5639  5655 D bt_bte_conf:   clientExecutableURL = 
09-23 06:58:38.571  5639  5655 D bt_bte_conf:   serviceDescription  = 
09-23 06:58:38.572  5639  5655 D bt_bte_conf:   documentationURL    = 
09-23 06:58:38.572  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.572  5639  5655 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-23 06:58:38.572  5639  5652 D bt_stack_manager: event_start_up_stack finished
09-23 06:58:38.574  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.576  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.576  5639  5659 I bt_vendor: low_power_mode_cb
09-23 06:58:38.577  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 06:58:38.577  5639  5651 D BluetoothAdapterProperties: Setting state to 15
09-23 06:58:38.578  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-23 06:58:38.579  5639  5651 I BluetoothAdapterState: Entering BleOnState
09-23 06:58:38.583  5639  5651 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 06:58:38.583  5639  5651 D BluetoothAdapterProperties: Setting state to 11
09-23 06:58:38.584  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 06:58:38.592  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:38.593  5639  5639 D HeadsetService: Received start request. Starting profile...
,09-23 06:58:38.596  5639  5639 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-23 06:58:38.597  5639  5639 D HeadsetStateMachine: make
09-23 06:58:38.602  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.606  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.609  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.612  5639  5639 D HeadsetStateMachine: max_hf_connections = 1
,09-23 06:58:38.612  5639  5639 I bt_bluedroid: get_profile_interface handsfree
09-23 06:58:38.613  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 06:58:38.613  5639  5655 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-23 06:58:38.613  5639  5651 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:58:38.616  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:38.617  5639  5639 D A2dpService: Received start request. Starting profile...
09-23 06:58:38.618  5639  5639 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 06:58:38.618  5639  5639 I bt_bluedroid: get_profile_interface avrcp
,09-23 06:58:38.625  5639  5639 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 06:58:38.625  5639  5639 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 06:58:38.625  5639  5639 D A2dpStateMachine: make
09-23 06:58:38.627  5639  5639 I bt_bluedroid: get_profile_interface a2dp
,09-23 06:58:38.629  5639  5672 D A2dpStateMachine: Enter Disconnected: -2
,09-23 06:58:38.630  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-23 06:58:38.630  5639  5639 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 06:58:38.631  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:38.632  5639  5639 D HidService: Received start request. Starting profile...
,09-23 06:58:38.633  5639  5639 I bt_bluedroid: get_profile_interface hidhost
09-23 06:58:38.632  5595  5595 D BluetoothInputDevice: Proxy object connected
09-23 06:58:38.633  5639  5639 D HidService: setHidService(): set to: null
09-23 06:58:38.633  5639  5655 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c2e56d
09-23 06:58:38.633  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 06:58:38.634  5595  5595 D HidProfile: Bluetooth service connected
09-23 06:58:38.635  5639  5639 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 06:58:38.636  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:38.637  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:58:38.637  5639  5639 D HealthService: Received start request. Starting profile...
,09-23 06:58:38.639  5639  5639 I bt_bluedroid: get_profile_interface health
,09-23 06:58:38.640  5639  5639 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 06:58:38.641  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:38.644  5639  5639 D PanService: Received start request. Starting profile...
,09-23 06:58:38.644  5639  5639 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-23 06:58:38.644  5639  5639 I bt_bluedroid: get_profile_interface pan
09-23 06:58:38.645  5639  5655 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 06:58:38.649  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:38.651  5639  5639 D BluetoothMapService: Received start request. Starting profile...
,09-23 06:58:38.650  5595  5595 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:58:38.651  5639  5639 D BluetoothMapService: start()
09-23 06:58:38.651  5595  5595 D PanProfile: Bluetooth service connected
09-23 06:58:38.652  5595  5595 D BluetoothMap: Proxy object connected
,09-23 06:58:38.652  5595  5595 D MapProfile: Bluetooth service connected
09-23 06:58:38.652  5595  5595 D BluetoothMap: getConnectedDevices()
09-23 06:58:38.653  5595  5595 D BluetoothMap: Bluetooth is Not enabled
,09-23 06:58:38.654  5639  5639 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 06:58:38.655  5639  5639 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 06:58:38.655  5639  5639 D BluetoothMapAppObserver: createReceiver()
,09-23 06:58:38.656  5639  5639 D BluetoothMapAppObserver: initObservers()
,09-23 06:58:38.656  5639  5639 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 06:58:38.663  5639  5639 V SapService: SapBinder()
,09-23 06:58:38.663  5639  5639 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:38.664  5639  5639 D SapService: Received start request. Starting profile...
09-23 06:58:38.664  5639  5639 V SapService: start()
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.665  5639  5669 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.665  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.666  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.667  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.667  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.667  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.667  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.667  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.667  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.668  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:38.668  5639  5639 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:38.668  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.668  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.668  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-23 06:58:38.668  5639  5651 D BluetoothAdapterProperties: ScanMode =  20
09-23 06:58:38.668  5639  5651 D BluetoothAdapterProperties: State =  11
09-23 06:58:38.671  5639  5655 D BluetoothAdapterProperties: Scan Mode:21
09-23 06:58:38.671  5639  5651 D BluetoothAdapterProperties: Setting state to 12
,09-23 06:58:38.671  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 06:58:38.671  5639  5655 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:58:38.672  5639  5651 I BluetoothAdapterState: Entering OnState
09-23 06:58:38.672  5595  5605 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:58:38.672  5595  5606 D BluetoothPan: onBluetoothStateChange on: true
,09-23 06:58:38.673  3145  3636 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 06:58:38.674  5479  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-23 06:58:38.675  5595  5605 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:58:38.675  3145  3734 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:58:38.676  3145  3145 D BluetoothA2dp: Proxy object connected
09-23 06:58:38.678  5479  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 06:58:38.678  3145  3145 D BluetoothInputDevice: Proxy object connected
09-23 06:58:38.678  3145  3145 D HidProfile: Bluetooth service connected
09-23 06:58:38.678   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:38.678   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:38.679   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 06:58:38.679   928   928 D BluetoothA2dp: Proxy object connected
09-23 06:58:38.680  3145  3163 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:38.681  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:38.682  5639  5639 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:58:38.682  3145  3636 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:58:38.682  5639  5639 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 06:58:38.682  3145  3145 D BluetoothMap: Proxy object connected
09-23 06:58:38.682  3145  3145 D MapProfile: Bluetooth service connected
09-23 06:58:38.682  3145  3145 D BluetoothMap: getConnectedDevices()
,09-23 06:58:38.684  3587  3842 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:38.684  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:38.684  3145  3734 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:58:38.685  5639  5639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:38.686  3145  3145 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:58:38.686  3145  3145 D PanProfile: Bluetooth service connected
09-23 06:58:38.686  3145  3157 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:58:38.687   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:58:38.687  5595  5606 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:58:38.688  5639  5639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:38.689  5639  5639 D ObexServerSockets: Succeed to create listening sockets 
09-23 06:58:38.689  5639  5639 D ObexServerSockets0: startAccept()
09-23 06:58:38.689  5639  5639 D ObexServerSockets0: prepareForNewConnect()
09-23 06:58:38.690   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:38.691  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:38.692  5639  5639 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 06:58:38.692  5639  5639 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 06:58:38.693  5639  5639 D BluetoothMapService: onReceive
09-23 06:58:38.693  5639  5639 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-23 06:58:38.694  5639  5639 D BluetoothMapService: STATE_ON
09-23 06:58:38.694  5639  5678 D ObexServerSockets0: Accepting socket connection...
09-23 06:58:38.694  5639  5679 D ObexServerSockets0: Accepting socket connection...
,09-23 06:58:38.695  5595  5595 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-23 06:58:38.695  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:38.697  5639  5681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:38.699  5595  5595 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:38.701  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:38.701  5639  5681 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 06:58:38.701  5639  5681 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 06:58:38.703  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:38.704  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.705  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.706  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:58:38.706  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:58:38.706  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.708  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.708  5595  5595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:58:38.708  5479  5525 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-23 06:58:38.709  5479  5525 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-23 06:58:38.711  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.711  5595  5595 D BluetoothA2dp: Proxy object connected
09-23 06:58:38.712  5639  5651 D BluetoothAdapterState: Current state: ON, message: 23
09-23 06:58:38.713  5639  5651 D BluetoothAdapterProperties: Setting state to 13
,09-23 06:58:38.713  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 06:58:38.713  5639  5651 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 06:58:38.715  5639  5655 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:58:38.715  5639  5651 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:58:38.717  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 06:58:38.717  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:58:38.719  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:38.720  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:38.720  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:38.720  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:38.724  5595  5595 D DockEventReceiver: finishStartingService: stopping service
09-23 06:58:38.724  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:38.724  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:38.726  5595  5595 D BluetoothPbap: Proxy object connected
,09-23 06:58:38.726  5479  5479 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:38.727  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:38.727  5595  5595 D PbapServerProfile: Bluetooth service connected
09-23 06:58:38.727  5639  5639 D HeadsetService: Received stop request...Stopping profile...
,09-23 06:58:38.728  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.728  5639  5639 D A2dpService: Received stop request...Stopping profile...
09-23 06:58:38.729  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.729  5639  5672 D A2dpStateMachine: Exit Disconnected: -1
09-23 06:58:38.731   928   928 D BluetoothA2dp: Proxy object disconnected
09-23 06:58:38.731  5595  5595 D BluetoothA2dp: Proxy object disconnected
,09-23 06:58:38.732  5639  5639 D BluetoothMapService: onReceive
09-23 06:58:38.732  5639  5639 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:58:38.732  5639  5639 D BluetoothMapService: STATE_TURNING_OFF
,09-23 06:58:38.737  5639  5639 D HidService: Received stop request...Stopping profile...
,09-23 06:58:38.737  5639  5639 D HidService: Stopping Bluetooth HidService
,09-23 06:58:38.739  5595  5595 D BluetoothInputDevice: Proxy object disconnected
,09-23 06:58:38.739  5595  5595 D HidProfile: Bluetooth service disconnected
09-23 06:58:38.739  5639  5639 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:38.739  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:38.739  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.739  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:58:38.741  5595  5595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:58:38.741  5639  5639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 06:58:38.741  5639  5639 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 06:58:38.742  5639  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:38.742  5639  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 06:58:38.742  5639  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:38.742  5639  5639 D HealthService: Received stop request...Stopping profile...
09-23 06:58:38.743  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 06:58:38.743  5639  5655 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-23 06:58:38.744  5639  5639 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:38.744  5639  5639 V BluetoothAdapterState: isTurningOn()=false
,09-23 06:58:38.744  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:58:38.744  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.745  3145  3145 D BluetoothPbap: Proxy object connected
09-23 06:58:38.745  3145  3145 D PbapServerProfile: Bluetooth service connected
09-23 06:58:38.745  3145  3145 D BluetoothA2dp: Proxy object disconnected
09-23 06:58:38.745  3145  3145 D BluetoothInputDevice: Proxy object disconnected
09-23 06:58:38.745  3145  3145 D HidProfile: Bluetooth service disconnected
09-23 06:58:38.745  5639  5639 D PanService: Received stop request...Stopping profile...
09-23 06:58:38.746  3145  3145 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:58:38.746  3145  3145 D PanProfile: Bluetooth service disconnected
09-23 06:58:38.747  5639  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:38.747  5639  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 06:58:38.747  5639  5639 D BluetoothMapService: Received stop request...Stopping profile...
09-23 06:58:38.747  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 06:58:38.747  5639  5639 D BluetoothMapService: stop()
09-23 06:58:38.747  5639  5664 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:58:38.747  5639  5664 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:58:38.747  5639  5664 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:58:38.747  5639  5664 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:58:38.748  5639  5639 D BluetoothMapAppObserver: deinitObservers()
09-23 06:58:38.748  5639  5639 D BluetoothMapAppObserver: removeReceiver()
09-23 06:58:38.749  3145  3145 D BluetoothMap: Proxy object disconnected
09-23 06:58:38.749  3145  3145 D MapProfile: Bluetooth service disconnected
09-23 06:58:38.749  5639  5639 D SapService: Received stop request...Stopping profile...
,09-23 06:58:38.749  5639  5639 V SapService: stop()
09-23 06:58:38.753  5595  5595 D DockEventReceiver: finishStartingService: stopping service
09-23 06:58:38.754  5595  5595 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:58:38.754  5595  5595 D PanProfile: Bluetooth service disconnected
09-23 06:58:38.754  5595  5595 D BluetoothMap: Proxy object disconnected
09-23 06:58:38.754  5595  5595 D MapProfile: Bluetooth service disconnected
,09-23 06:58:38.761  5639  5639 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:58:38.761  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:38.761  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.762  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.762  5639  5639 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 06:58:38.762  5639  5639 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-23 06:58:38.762  5639  5655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:58:38.762  5639  5639 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:38.762  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:38.762  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.762  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.762  5639  5639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 06:58:38.762  5639  5655 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 06:58:38.763  5639  5639 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 06:58:38.763  5639  5639 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:38.763  5639  5639 V BluetoothAdapterState: isTurningOn()=false
,09-23 06:58:38.763  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.763  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.764  5639  5639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-23 06:58:38.764  5639  5639 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 06:58:38.766  5639  5639 D BluetoothMapService: MAP Service closeService in
09-23 06:58:38.766  5639  5639 D BluetoothMapMasInstance0: MAP Service shutdown
,09-23 06:58:38.766  5639  5639 D ObexServerSockets0: shutdown(block = true)
09-23 06:58:38.766  5639  5639 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:58:38.767  5639  5639 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:58:38.767  5639  5679 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 06:58:38.767  5639  5666 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 06:58:38.767  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:58:38.771  5639  5678 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 06:58:38.772  5639  5639 V BluetoothAdapterState: isTurningOff()=true
09-23 06:58:38.772  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:38.772  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:58:38.772  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:38.772  5639  5639 D BluetoothMapService: cleanup()
09-23 06:58:38.772  5639  5639 D BluetoothMapService: MAP Service closeService in
,09-23 06:58:38.773  5639  5639 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:58:38.773  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:38.773  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:38.773  5639  5639 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:58:38.773  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 06:58:38.773  5639  5651 D BluetoothAdapterProperties: Setting state to 15
09-23 06:58:38.773  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 06:58:38.774  5639  5651 I BluetoothAdapterState: Entering BleOnState
09-23 06:58:38.774  5595  5605 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:58:38.775  5595  5606 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:58:38.776  3145  3163 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:58:38.776  5595  5605 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:58:38.777  3145  3145 D BluetoothPbap: Proxy object disconnected
09-23 06:58:38.777  3145  3145 D PbapServerProfile: Bluetooth service disconnected
,09-23 06:58:38.778  5595  5606 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-23 06:58:38.779  3145  3734 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-23 06:58:38.779   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:38.780   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:38.780  5595  5605 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:38.780   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:58:38.780  3145  3163 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:58:38.781  3145  3157 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:58:38.782  3587  3605 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:38.782  3145  3636 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:58:38.782  3145  3734 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:38.783   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:58:38.783  5595  5606 D BluetoothPbap: onBluetoothStateChange: up=false
,09-23 06:58:38.789  5639  5651 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 06:58:38.789  5639  5651 D BluetoothAdapterProperties: Setting state to 16
09-23 06:58:38.789  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-23 06:58:38.790  5639  5651 D BluetoothAdapterProperties: onBleDisable
09-23 06:58:38.790  5639  5651 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:58:38.791  5595  5595 D BluetoothPbap: Proxy object disconnected
,09-23 06:58:38.791  5595  5595 D PbapServerProfile: Bluetooth service disconnected
09-23 06:58:38.791  5639  5655 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:58:38.792  5639  5652 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 06:58:38.793  5639  5664 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 06:58:38.793  5639  5664 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:58:38.794  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.795  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:38.796  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.797  5595  5595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:58:38.797  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:38.804  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:58:38.805  5595  5595 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:58:38.993  5639  5655 I bt_hci  : shut_down
09-23 06:58:38.993  5639  5659 D bt_hwcfg: hw_epilog_process
,09-23 06:58:38.995  5639  5659 I bt_vendor: low_power_mode_cb
,09-23 06:58:38.999  5639  5659 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 06:58:38.999  5639  5659 I bt_vendor: epilog_cb
09-23 06:58:38.999  5639  5659 I bt_hci  : epilog_finished_callback
09-23 06:58:39.001  5639  5655 I bt_hci_h4: hal_close
09-23 06:58:39.002  5639  5655 I bt_userial_vendor: device fd = 54 close
,09-23 06:58:39.127  5639  5652 D bt_stack_manager: event_shut_down_stack finished.
09-23 06:58:39.127  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 06:58:39.131  5639  5651 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 06:58:39.131  5639  5639 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:58:39.132  5639  5639 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 06:58:39.133  5639  5639 D BtGatt.GattService: stop()
09-23 06:58:39.133  5639  5639 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 06:58:39.137  5639  5639 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:39.137  5639  5639 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:39.137  5639  5639 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:39.137  5639  5639 V BluetoothAdapterState: isBleTurningOff()=true
09-23 06:58:39.138  5639  5651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 06:58:39.138  5639  5651 D BluetoothAdapterProperties: Setting state to 10
09-23 06:58:39.139  5639  5651 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 06:58:39.140  5639  5651 I BluetoothAdapterState: Entering OffState
09-23 06:58:39.142   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-23 06:58:39.155  5639  5639 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 06:58:39.155  5639  5639 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 06:58:39.155  5639  5639 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 06:58:39.159  5639  5652 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-23 06:58:39.167  5639  5639 I art     : System.exit called, status: 0
09-23 06:58:39.167  5639  5639 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 06:58:39.195   928  3597 I ActivityManager: Process com.android.bluetooth (pid 5639) has died
,09-23 06:58:39.212  5479  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:39.212  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:39.212  5479  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:58:39.213  5479  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:39.214  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:39.227   928   945 I ActivityManager: Start proc 5694:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 06:58:39.289  5694  5694 D AdapterServiceConfig: Adding HeadsetService
,09-23 06:58:39.289  5694  5694 D AdapterServiceConfig: Adding A2dpService
09-23 06:58:39.289  5694  5694 D AdapterServiceConfig: Adding HidService
09-23 06:58:39.289  5694  5694 D AdapterServiceConfig: Adding HealthService
,09-23 06:58:39.290  5694  5694 D AdapterServiceConfig: Adding PanService
09-23 06:58:39.290  5694  5694 D AdapterServiceConfig: Adding GattService
09-23 06:58:39.290  5694  5694 D AdapterServiceConfig: Adding BluetoothMapService
09-23 06:58:39.290  5694  5694 D AdapterServiceConfig: Adding SapService
,09-23 06:58:39.303   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a89e167:true
,09-23 06:58:39.303  5694  5694 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 06:58:39.305  5694  5694 I bt_bluedroid: init
09-23 06:58:39.305  5694  5706 I BluetoothAdapterState: Entering OffState
,09-23 06:58:39.307  5694  5707 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-23 06:58:39.307  5694  5707 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 06:58:39.307  5694  5707 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 06:58:39.307  5694  5707 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-23 06:58:39.308  5694  5694 I bt_bluedroid: get_profile_interface socket
,09-23 06:58:39.309  5694  5694 I bt_bluedroid: get_profile_interface sdp
09-23 06:58:39.309  5694  5710 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:58:39.311  5694  5710 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:58:39.314  5694  5705 I bt_bluedroid: config_hci_snoop_log
,09-23 06:58:39.315   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 06:58:39.319  5694  5706 D BluetoothAdapterState: Current state: OFF, message: 0
,09-23 06:58:39.319  5694  5706 D BluetoothAdapterProperties: Setting state to 14
09-23 06:58:39.319  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 06:58:39.320  5694  5706 D BluetoothBondStateMachine: make
,09-23 06:58:39.322  5694  5711 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 06:58:39.324  5694  5706 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:58:39.325  5694  5694 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 06:58:39.327  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:39.327  5694  5694 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:58:39.328  5694  5694 D BtGatt.GattService: Received start request. Starting profile...
09-23 06:58:39.328  5694  5694 D BtGatt.GattService: start()
09-23 06:58:39.328  5694  5694 I bt_bluedroid: get_profile_interface gatt
09-23 06:58:39.329  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:39.329  5694  5694 D BtGatt.AdvertiseManager: advertise manager created
,09-23 06:58:39.333  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:39.333  5694  5694 V BluetoothAdapterState: isTurningOn()=false
09-23 06:58:39.333  5694  5694 V BluetoothAdapterState: isBleTurningOn()=true
09-23 06:58:39.334  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:39.334  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 06:58:39.335  5694  5706 I bt_bluedroid: bt_bluedroid
,09-23 06:58:39.335  5694  5707 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 06:58:39.335  5694  5707 I bt_hci  : start_up
,09-23 06:58:39.340  5694  5707 I bt_vendor: alloc value 0xf3ccf871
,09-23 06:58:39.340  5694  5707 I bt_vendor: init
09-23 06:58:39.340  5694  5707 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 06:58:39.341  5694  5707 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 06:58:39.453  5694  5707 D bt_hci  : start_up starting async portion
09-23 06:58:39.453  5694  5714 I bt_hci  : event_finish_startup
,09-23 06:58:39.454  5694  5714 I bt_hci_h4: hal_open
09-23 06:58:39.454  5694  5714 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 06:58:39.451  5715  5715 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-23 06:58:39.456  5694  5714 I bt_userial_vendor: device fd = 54 open
,09-23 06:58:39.470  5694  5714 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:58:39.473  5694  5714 D bt_hwcfg: Chipset BCM4358A3
,09-23 06:58:39.473  5694  5714 D bt_hwcfg: Target name = [BCM4358A3]
,09-23 06:58:39.474  5694  5714 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 06:58:39.721  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 06:58:39.874  5694  5714 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 06:58:39.874  5694  5714 D bt_hwcfg: Settlement delay -- 100 ms
,09-23 06:58:39.875  5694  5714 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 06:58:39.998  5694  5714 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:58:39.998  5694  5714 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 06:58:39.999  5694  5714 I bt_hwcfg: vendor lib fwcfg completed
,09-23 06:58:40.000  5694  5714 I bt_vendor: firmware callback
09-23 06:58:40.000  5694  5714 I bt_hci  : firmware_config_callback
09-23 06:58:40.008  5694  5717 I bt_btu  : btu_task pending for preload complete event
09-23 06:58:40.008  5694  5717 I bt_btu_task: Bluetooth chip preload is complete
,09-23 06:58:40.008  5694  5717 I bt_btu  : btu_task received preload complete event
,09-23 06:58:40.014  5694  5717 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 06:58:40.014  5694  5717 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 06:58:40.014  5694  5717 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 06:58:40.014  5694  5717 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 06:58:40.014  5694  5717 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_A2D
,09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 06:58:40.015  5694  5717 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 06:58:40.016  5694  5717 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 06:58:40.098  5694  5717 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c4d549
09-23 06:58:40.098  5694  5717 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c4d549 
,09-23 06:58:40.122  5694  5710 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 06:58:40.124  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:58:40.124  5694  5710 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:58:40.126  5694  5710 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:58:40.128  5694  5710 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:58:40.129  5694  5710 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:58:40.129  5694  5710 D bt_hci  : do_postload posting postload work item
09-23 06:58:40.129  5694  5714 I bt_hci  : event_postload
09-23 06:58:40.129  5694  5714 I bt_vendor: sco_config_cb
09-23 06:58:40.130  5694  5714 I bt_hci  : sco_config_callback postload finished.
,09-23 06:58:40.134  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:40.136  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:40.136  5694  5710 D bt_bte_conf: Device ID record 1 : primary
09-23 06:58:40.136  5694  5710 D bt_bte_conf:   vendorId            = 000f
09-23 06:58:40.136  5694  5710 D bt_bte_conf:   vendorIdSource      = 0001
09-23 06:58:40.137  5694  5710 D bt_bte_conf:   product             = 1200
09-23 06:58:40.137  5694  5710 D bt_bte_conf:   version             = 1436
09-23 06:58:40.137  5694  5710 D bt_bte_conf:   clientExecutableURL = 
09-23 06:58:40.137  5694  5710 D bt_bte_conf:   serviceDescription  = 
09-23 06:58:40.137  5694  5710 D bt_bte_conf:   documentationURL    = 
09-23 06:58:40.137  5694  5710 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 06:58:40.137  5694  5707 D bt_stack_manager: event_start_up_stack finished
09-23 06:58:40.137  5694  5714 I bt_vendor: low_power_mode_cb
09-23 06:58:40.137  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-23 06:58:40.138  5694  5706 D BluetoothAdapterProperties: Setting state to 15
09-23 06:58:40.138  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 06:58:40.138  5694  5706 I BluetoothAdapterState: Entering BleOnState
,09-23 06:58:40.142  5694  5706 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-23 06:58:40.142  5694  5706 D BluetoothAdapterProperties: Setting state to 11
09-23 06:58:40.142  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 06:58:40.147  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:40.149  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:40.152  5595  5605 D BluetoothHeadset: Proxy object connected
09-23 06:58:40.152  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:40.152  5694  5694 D HeadsetService: Received start request. Starting profile...
09-23 06:58:40.154  3145  3636 D BluetoothHeadset: Proxy object connected
09-23 06:58:40.154  3145  3145 D HeadsetProfile: Bluetooth service connected
09-23 06:58:40.154  3587  3842 D BluetoothHeadset: Proxy object connected
09-23 06:58:40.154  5694  5694 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 06:58:40.154   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:58:40.154   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:58:40.155  5694  5694 D HeadsetStateMachine: make
09-23 06:58:40.155   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:58:40.155  5595  5595 D HeadsetProfile: Bluetooth service connected
,09-23 06:58:40.162  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:58:40.164  5694  5706 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:58:40.165  5694  5694 D HeadsetStateMachine: max_hf_connections = 1
,09-23 06:58:40.165  5694  5694 I bt_bluedroid: get_profile_interface handsfree
09-23 06:58:40.165  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 06:58:40.165  5694  5710 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-23 06:58:40.167  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:40.168  5694  5694 D A2dpService: Received start request. Starting profile...
09-23 06:58:40.168  5694  5694 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 06:58:40.169  5694  5694 I bt_bluedroid: get_profile_interface avrcp
09-23 06:58:40.169  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:58:40.173  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:58:40.174  5694  5694 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 06:58:40.174  5694  5694 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 06:58:40.174  5694  5694 D A2dpStateMachine: make
09-23 06:58:40.175  5694  5694 I bt_bluedroid: get_profile_interface a2dp
,09-23 06:58:40.175  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-23 06:58:40.176  5694  5726 D A2dpStateMachine: Enter Disconnected: -2
09-23 06:58:40.177  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-23 06:58:40.177  5694  5694 I BluetoothHidServiceJni: classInitNative: succeeds
09-23 06:58:40.177  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:40.178  5694  5694 D HidService: Received start request. Starting profile...
09-23 06:58:40.178  5694  5694 I bt_bluedroid: get_profile_interface hidhost
09-23 06:58:40.178  5694  5694 D HidService: setHidService(): set to: null
09-23 06:58:40.178  5694  5710 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c2e56d
09-23 06:58:40.178  5694  5710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-23 06:58:40.180  5694  5694 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 06:58:40.180  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:40.181  5694  5694 D HealthService: Received start request. Starting profile...
,09-23 06:58:40.181  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:58:40.183  5694  5694 I bt_bluedroid: get_profile_interface health
,09-23 06:58:40.184  5694  5694 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 06:58:40.185  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:40.185  5694  5694 D PanService: Received start request. Starting profile...
09-23 06:58:40.185  5694  5694 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 06:58:40.185  5694  5694 I bt_bluedroid: get_profile_interface pan
09-23 06:58:40.186  5694  5710 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 06:58:40.189  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:40.189  5694  5694 D BluetoothMapService: Received start request. Starting profile...
09-23 06:58:40.189  5694  5694 D BluetoothMapService: start()
09-23 06:58:40.194  5694  5694 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 06:58:40.194  5694  5694 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 06:58:40.194  5694  5694 D BluetoothMapAppObserver: createReceiver()
09-23 06:58:40.195  5694  5694 D BluetoothMapAppObserver: initObservers()
09-23 06:58:40.196  5694  5694 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 06:58:40.201  5694  5694 V SapService: SapBinder()
09-23 06:58:40.201  5694  5694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
,09-23 06:58:40.202  5694  5694 D SapService: Received start request. Starting profile...
,09-23 06:58:40.202  5694  5694 V SapService: start()
,09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:40.204  5694  5724 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:40.204  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.205  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.205  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:58:40.205  5694  5694 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:58:40.205  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.205  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.205  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.206  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.207  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:40.208  5694  5694 V BluetoothAdapterState: isTurningOff()=false
09-23 06:58:40.208  5694  5694 V BluetoothAdapterState: isTurningOn()=true
09-23 06:58:40.208  5694  5694 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:58:40.208  5694  5694 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:58:40.208  5694  5706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 06:58:40.208  5694  5706 D BluetoothAdapterProperties: ScanMode =  20
09-23 06:58:40.208  5694  5706 D BluetoothAdapterProperties: State =  11
09-23 06:58:40.210  5694  5710 D BluetoothAdapterProperties: Scan Mode:21
09-23 06:58:40.210  5694  5706 D BluetoothAdapterProperties: Setting state to 12
09-23 06:58:40.211  5694  5706 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 06:58:40.211  5694  5710 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:58:40.211  5694  5706 I BluetoothAdapterState: Entering OnState
09-23 06:58:40.211  5595  5690 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:40.213  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:40.214  5595  5606 D BluetoothPan: onBluetoothStateChange on: true
,09-23 06:58:40.215  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:40.216  3145  3734 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:58:40.219  5595  5690 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:40.219  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:40.219  3145  3145 D BluetoothA2dp: Proxy object connected
09-23 06:58:40.220  5595  5606 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:58:40.221  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:40.222  3145  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 06:58:40.223  5694  5694 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:58:40.224  5694  5694 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 06:58:40.224  5595  5595 D BluetoothMap: Proxy object connected
09-23 06:58:40.224  5595  5595 D MapProfile: Bluetooth service connected
09-23 06:58:40.224  5595  5595 D BluetoothMap: getConnectedDevices()
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:40.224  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:40.225  5694  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:40.225   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:40.225   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:40.226  5595  5690 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:40.226  5479  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:40.226   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 06:58:40.226  3145  3636 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 06:58:40.226  5479  5525 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-23 06:58:40.227   928   928 D BluetoothA2dp: Proxy object connected
09-23 06:58:40.227   928  3143 D WifiService: setWifiEnabled: false pid=5479, uid=10077
09-23 06:58:40.227   928  3143 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:58:40.228  3145  3145 D BluetoothMap: Proxy object connected
09-23 06:58:40.228  3145  3145 D MapProfile: Bluetooth service connected
09-23 06:58:40.228  3145  3145 D BluetoothMap: getConnectedDevices()
09-23 06:58:40.228  3145  3157 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:58:40.229  5694  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:40.230  5595  5595 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:58:40.230  5595  5595 D PanProfile: Bluetooth service connected
09-23 06:58:40.230  5595  5595 D BluetoothA2dp: Proxy object connected
09-23 06:58:40.231  3587  3604 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:58:40.231   928   928 D RttService: SCAN_AVAILABLE : 1
09-23 06:58:40.231  3145  3163 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:58:40.231   928  3096 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:58:40.232  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:40.232  5694  5694 D ObexServerSockets: Succeed to create listening sockets 
09-23 06:58:40.233  5694  5694 D ObexServerSockets0: startAccept()
09-23 06:58:40.233  5694  5694 D ObexServerSockets0: prepareForNewConnect()
09-23 06:58:40.233  3145  3145 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:58:40.234  3145  3145 D PanProfile: Bluetooth service connected
09-23 06:58:40.234  3145  3734 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:58:40.234   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:58:40.234  5595  5605 D BluetoothPbap: onBluetoothStateChange: up=true
,09-23 06:58:40.235  5694  5694 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 06:58:40.235  5694  5694 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 06:58:40.236  5694  5732 D ObexServerSockets0: Accepting socket connection...
09-23 06:58:40.236  5694  5733 D ObexServerSockets0: Accepting socket connection...
,09-23 06:58:40.237  3145  3145 D BluetoothInputDevice: Proxy object connected
09-23 06:58:40.237  3145  3145 D HidProfile: Bluetooth service connected
,09-23 06:58:40.238   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 06:58:40.239   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-23 06:58:40.239  5694  5694 D BluetoothMapService: onReceive
09-23 06:58:40.239  5694  5694 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:58:40.239  5694  5694 D BluetoothMapService: STATE_ON
09-23 06:58:40.240   928  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 06:58:40.240   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:58:40.241  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:40.241  5595  5595 D BluetoothInputDevice: Proxy object connected
09-23 06:58:40.241  5595  5595 D HidProfile: Bluetooth service connected
09-23 06:58:40.243  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:40.244  5694  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:40.244   928  2988 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 06:58:40.245  5591  5591 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 06:58:40.248  5694  5735 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 06:58:40.248  5694  5735 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:40.252  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:40.253  5591  5591 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 06:58:40.254  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:40.255  5595  5595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:40.257  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:40.259  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:40.260  5694  5694 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:58:40.260  5694  5694 D ObexServerSockets0: prepareForNewConnect()
09-23 06:58:40.260  5595  5595 D DockEventReceiver: finishStartingService: stopping service
09-23 06:58:40.261  3672  3672 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:58:40.269  5595  5595 D BluetoothPbap: Proxy object connected
09-23 06:58:40.269  5595  5595 D PbapServerProfile: Bluetooth service connected
,09-23 06:58:40.270  3145  3145 D BluetoothPbap: Proxy object connected
09-23 06:58:40.270  3145  3145 D PbapServerProfile: Bluetooth service connected
,09-23 06:58:40.273  5591  5591 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 06:58:40.275  5694  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:40.283  5591  5591 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:58:40.290  5694  5744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:40.291  5694  5744 I BtOppRfcommListener: Accept thread started.
,09-23 06:58:40.387   928  2988 D wifi    : In wifi stop Hal
,09-23 06:58:40.387  4316  4316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:58:40.387   928  2988 D wifi    : halHandle = 0x7f8f984ae0, mVM = 0x7fabb0d140, mCls = 0x10180e
09-23 06:58:40.388   928  5590 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 06:58:40.388   928  5590 D WifiHAL : Got a signal to exit!!!
09-23 06:58:40.388   928  5590 I WifiHAL : Exit wifi_event_loop
09-23 06:58:40.388   928  2988 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 06:58:40.388   928  2988 E WifiHAL : Event processing terminated
09-23 06:58:40.388   928  2988 D wifi    : In wifi cleaned up handler
09-23 06:58:40.388   928  2988 I WifiHAL : Internal cleanup completed
,09-23 06:58:40.390  3516  4052 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:58:40.391  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:40.392  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:40.419   928  5590 D wifi    : set interface wlan0 flags (DOWN)
,09-23 06:58:40.419   928  2988 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 06:58:40.625   928   945 D Tethering: InitialState.processMessage what=4
,09-23 06:58:40.634   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:40.736  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:40.741  5479  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:40.744   928  3614 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-23 06:58:40.744   928  3614 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:58:40.747  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:40.751   507   921 D SoftapController: Softap fwReload - Ok
,09-23 06:58:40.755   507   921 D CommandListener: Setting iface cfg
,09-23 06:58:40.756   507   921 D CommandListener: Trying to bring down wlan0
09-23 06:58:40.757   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:58:40.762   928  2988 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:58:41.250   928  3599 D WifiService: setWifiEnabled: true pid=5479, uid=10077
,09-23 06:58:41.254   928  3599 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:58:41.346   928  2988 D wifi    : set interface wlan0 flags (UP)
,09-23 06:58:41.347   928  2988 I WifiHAL : Initializing wifi
09-23 06:58:41.347   928  2988 I WifiHAL : Creating socket
,09-23 06:58:41.351   928  2988 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 06:58:41.351   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-23 06:58:41.352   928  2988 D wifi    : Did set static halHandle = 0x7f8f984ae0
09-23 06:58:41.352   928  2988 D wifi    : halHandle = 0x7f8f984ae0, mVM = 0x7fabb0d140, mCls = 0x112a
,09-23 06:58:41.352   928  2988 D wifi    : array field set
09-23 06:58:41.352   928  2988 I WifiNative-HAL: interface[0] = wlan0
,09-23 06:58:41.354   928  5747 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547869969120
,09-23 06:58:41.354   928  5747 D wifi    : waitForHalEvents called, vm = 0x7fabb0d140, obj = 0x112a, env = 0x7f91e608c0
,09-23 06:58:41.396  5748  5748 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 06:58:41.409  5748  5748 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:58:41.435  5748  5748 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:58:41.435  5748  5748 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 06:58:41.455   928  2988 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 06:58:41.462   928  2988 D WifiConfigStore: Loading config and enabling all networks 
,09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:41.464  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:58:41.466  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:41.470  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:41.472  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:41.472   928  2988 D WifiConfigStore: loaded 0 passpoint configs
09-23 06:58:41.472   928  2988 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:58:41.473   928  2988 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 06:58:41.473  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:41.474   928  2988 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 06:58:41.474  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:58:41.475   928  2988 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:58:41.475   928  2988 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 06:58:41.475   928  2988 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 06:58:41.475   928  2988 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 06:58:41.481  4316  4316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:58:41.481   928  2988 D WifiNative-HAL: Setting external_sim to 1
,09-23 06:58:41.481   928  2988 D wifi    : setting dfs flag to true, 0x7f9228f3e0
09-23 06:58:41.482   928  2988 D WifiStateMachine: Setting OUI to DA-A1-19
,09-23 06:58:41.482   928  2988 D wifi    : setting scan oui 0x7f9228f3e0
09-23 06:58:41.482   928  2988 D WifiHAL : Sending mac address OUI
,09-23 06:58:41.487   928  2988 E native  : do suspend false
,09-23 06:58:41.494   928  2988 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-23 06:58:41.494   928   928 D RttService: SCAN_AVAILABLE : 3
09-23 06:58:41.494   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 06:58:41.494   928  3096 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 06:58:41.495   507   921 D CommandListener: Setting iface cfg
,09-23 06:58:41.498   928  2987 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-23 06:58:41.499   928  2987 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 06:58:41.507   928  2987 D WifiNative-HAL: p2pGetDeviceAddress
09-23 06:58:41.508   928  2987 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 06:58:41.513   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=208930 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:41.766  5479  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:41.771  5479  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:58:41.774  5479  5525 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 06:58:41.775   928  3635 D WifiService: setWifiEnabled: true pid=5479, uid=10077
09-23 06:58:41.775   928  3635 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:58:41.776  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:58:41.776  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:58:41.777  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:58:41.777  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 06:58:41.777  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef34ba3 removed from the list
09-23 06:58:41.777  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:58:41.777  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50ea0 removed from the list
,09-23 06:58:41.777  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:58:41.777  5479  5525 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:58:41.777  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:58:41.779  5479  5525 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
09-23 06:58:41.781  5479  5525 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-23 06:58:41.785  5479  5750 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-23 06:58:41.785  5479  5750 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 06:58:42.302  5479  5750 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-23 06:58:42.302  5479  5752 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-23 06:58:42.303  5479  5752 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:58:42.303  5479  5750 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:58:42.304  5479  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:58:42.304  5479  5752 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:58:42.305  5479  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:58:42.305  5479  5752 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:58:42.305  5479  5754 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender)
,09-23 06:58:42.306  5479  5750 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 06:58:42.306  5479  5755 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Sender)
,09-23 06:58:42.307  5479  5752 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 06:58:42.307  5479  5756 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: OutgoingSocketThread/Receiver)
09-23 06:58:42.308  5479  5757 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver)
09-23 06:58:42.308  5479  5756 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: OutgoingSocketThread/Receiver)
09-23 06:58:42.308  5479  5757 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver)
09-23 06:58:42.308  5479  5756 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 06:58:42.308  5479  5757 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 06:58:42.309  5479  5756 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 06:58:42.309  5479  5757 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-23 06:58:42.789  5479  5525 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-23 06:58:42.792  5479  5525 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-23 06:58:42.794  5479  5525 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
09-23 06:58:42.798  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-23 06:58:42.799  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-23 06:58:42.800  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,09-23 06:58:42.800  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-23 06:58:42.802  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-23 06:58:42.807  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-23 06:58:42.807  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4617957 Bundle[{}]
09-23 06:58:42.809  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-23 06:58:42.809  5479  5525 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 06:58:42.809  5479  5525 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-23 06:58:42.811  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,09-23 06:58:42.811  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-23 06:58:42.813  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-23 06:58:42.813  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-23 06:58:42.814  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,09-23 06:58:42.815  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-23 06:58:42.816  5479  5525 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
09-23 06:58:42.817  5479  5525 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-23 06:58:42.820  5479  5525 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-23 06:58:42.823  5479  5525 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-23 06:58:42.826  5479  5525 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-23 06:58:42.827  5479  5525 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,09-23 06:58:42.829  5479  5525 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-23 06:58:42.831  5479  5525 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-23 06:58:42.833  5479  5525 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-23 06:58:42.835  5479  5758 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-23 06:58:42.835  5479  5758 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 06:58:42.840  5479  5758 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-23 06:58:42.840  5479  5758 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:58:42.840  5479  5758 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:58:42.840  5479  5758 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:58:42.841  5479  5758 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-23 06:58:42.842  5479  5760 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-23 06:58:42.842  5479  5760 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:58:42.842  5479  5761 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Sender)
,09-23 06:58:42.842  5479  5760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:58:42.843  5479  5762 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver)
,09-23 06:58:42.844  5479  5760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:58:42.844  5479  5762 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver)
,09-23 06:58:42.844  5479  5762 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 06:58:42.845  5479  5763 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: IncomingSocketThread/Sender)
,09-23 06:58:42.845  5479  5762 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 06:58:42.845  5479  5760 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 06:58:42.847  5479  5764 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: IncomingSocketThread/Receiver)
,09-23 06:58:42.848  5479  5764 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: IncomingSocketThread/Receiver)
09-23 06:58:42.848  5479  5764 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 06:58:42.848  5479  5764 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 06:58:43.340  5479  5525 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-23 06:58:43.342  5479  5525 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
09-23 06:58:43.344  5479  5525 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-23 06:58:43.348  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-23 06:58:43.350  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-23 06:58:43.353  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-23 06:58:43.354  5479  5525 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 183)
,09-23 06:58:43.356  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
09-23 06:58:43.356  5479  5525 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-23 06:58:43.357  5479  5525 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 184)
,09-23 06:58:43.358  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-23 06:58:43.359  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-23 06:58:43.360  5479  5525 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,09-23 06:58:43.361  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:58:43.361  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48c1315 added. We now have 3 listener(s)
09-23 06:58:43.363  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:43.363  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:58:43.363  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:58:43.364  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:58:43.364  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b2b62a added. We now have 3 listener(s)
,09-23 06:58:43.364  5479  5525 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:58:43.365  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:58:43.368  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:58:43.372  5479  5525 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:58:43.374  5479  5525 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:58:43.375  5479  5525 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:58:43.377  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:43.380  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:58:43.380  5479  5525 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,09-23 06:58:43.381  5479  5525 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,09-23 06:58:43.381  5479  5525 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-23 06:58:43.381  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-23 06:58:43.382  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:43.382  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-23 06:58:43.382  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:58:43.382  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:43.383  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:58:43.384  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 06:58:43.385  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:58:43.385  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:58:43.385  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:58:43.385  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:58:43.385  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:43.385  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:58:43.386  5479  5765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:58:43.389  5479  5765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 06:58:43.384  5704  5704 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[29546]" dev="sockfs" ino=29546 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:43.384  5704  5704 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[29546]" dev="sockfs" ino=29546 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:58:43.392  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:58:43.392  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:58:43.396  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:58:43.397  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:58:43.397  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:58:43.398  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:58:43.399  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:43.399  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-23 06:58:43.399  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:43.399  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:43.399  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:58:43.400  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:43.403  5694  5704 D BtGatt.GattService: registerClient() - UUID=077c8d7d-e31d-4567-97e4-630aace75ba2
,09-23 06:58:43.404  5694  5710 D BtGatt.GattService: onClientRegistered() - UUID=077c8d7d-e31d-4567-97e4-630aace75ba2, clientIf=5
09-23 06:58:43.404  5479  5489 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:58:43.407  5694  5712 D BtGatt.AdvertiseManager: message : 0
,09-23 06:58:43.409  5694  5712 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:58:43.420  5694  5710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:58:43.426  5694  5710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:58:43.427  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 06:58:43.427  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:58:43.428  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:58:43.430  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:43.430  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:58:43.430  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:58:43.430  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:58:43.430  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-23 06:58:43.431  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:58:43.433  5479  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:58:43.433  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:58:43.934  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:58:43.935  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:58:43.935  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:58:44.728   928  2988 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 06:58:44.729   928  2988 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 06:58:44.730   928  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:58:44.741   928  2988 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 06:58:44.777   928  2988 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 06:58:44.779  5748  5748 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 06:58:45.226  5748  5748 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 06:58:45.263  5748  5748 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 06:58:45.264  5748  5748 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 06:58:45.273   928  2988 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 06:58:45.274   928  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:58:45.274   928  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
,09-23 06:58:45.288   928  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:58:45.298   507   921 D CommandListener: Setting iface cfg
,09-23 06:58:45.303   928  2988 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 06:58:45.310   928  5770 D DhcpClient: Receive thread started
,09-23 06:58:45.314   928  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:58:45.314   928  2988 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 06:58:45.314   928  2990 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 06:58:45.395   928  2988 E native  : do suspend false
,09-23 06:58:45.405   928  5769 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 06:58:45.434   928  5770 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172628, domain null
,09-23 06:58:45.435   928  5769 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172628 seconds
,09-23 06:58:45.437   928  5769 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 06:58:45.457   928  5770 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 06:58:45.458   928  5769 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-23 06:58:45.461   507   921 D CommandListener: Setting iface cfg
09-23 06:58:45.466   928  2988 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 06:58:45.473   928  5769 D DhcpClient: Scheduling renewal in 86399s
,09-23 06:58:45.480   928  2988 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 06:58:45.480   928  2988 D WifiConfigStore: No blacklist allowed without epno enabled
,09-23 06:58:45.481   928  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-23 06:58:45.483   928  2990 D ConnectivityService: Adding iface wlan0 to network 101
,09-23 06:58:45.493   928  2988 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 06:58:45.533   928  2990 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 06:58:45.533   928  2990 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 06:58:45.540   928  2990 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 06:58:45.542   928  2990 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-23 06:58:45.546   928  2990 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 06:58:45.552   928  2990 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:58:45.557   928  2990 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-23 06:58:45.557   928  2990 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-23 06:58:45.557   928  2990 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-23 06:58:45.557   928  2988 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 06:58:45.557   928  2990 D ConnectivityService:    accepting network in place of null
09-23 06:58:45.557   928  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:58:45.558   928  2990 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 06:58:45.572   928  5768 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212989, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 06:58:45.581   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:58:45.602   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:58:45.606   928  2990 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-23 06:58:45.606  3535  3695 W QCNEJ   : |CORE| network available: 101
,09-23 06:58:45.606   928  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 06:58:45.607   928  2990 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-23 06:58:45.608  3535  3695 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-23 06:58:45.608   928   945 D Tethering: MasterInitialState.processMessage what=3
09-23 06:58:45.610  3535  3695 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-23 06:58:45.610  3535  3695 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:45.616  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:58:45.618  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:45.622  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:58:45.623  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:58:45.626  5479  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:58:45.628  5479  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:58:45.632  4921  4936 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 06:58:45.632  4921  4936 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 06:58:45.632  4921  4936 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 06:58:45.632  4921  4936 E SarControlService: no key has been found,reset the power
09-23 06:58:45.632  4921  4962 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 06:58:45.632  4921  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 06:58:45.632  4921  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 06:58:45.633  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:58:45.633  4950  4950 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 06:58:45.634  4921  4962 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 06:58:45.634  4921  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 06:58:45.635  4921  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 06:58:45.635  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:58:45.635  4950  4950 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 06:58:45.638  3933  3933 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 06:58:45.639   928  5767 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-23 06:58:45.641  3933  3933 D SystemUpdateService: onCreate
09-23 06:58:45.642  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dc86403 HexData = [00000000ec03000000000000ffffffff]
09-23 06:58:45.642  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:58:45.642  4950  4964 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 06:58:45.643  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:58:45.643  4921  4933 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 06:58:45.646  3933  3933 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 06:58:45.647  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@dc86403 HexData = [00000000ed03000000000000ffffffff]
09-23 06:58:45.647  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:58:45.647  4950  4964 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 06:58:45.648  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:58:45.648  4921  4932 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 06:58:45.660  3933  3933 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 06:58:45.666  3933  5783 I SystemUpdateService: active receiver: enabled
09-23 06:58:45.667  3933  5242 I iu.UploadsManager: num queued entries: 0
09-23 06:58:45.667  3933  5242 I iu.UploadsManager: num updated entries: 0
09-23 06:58:45.668  3933  5242 I iu.SyncManager: NEXT; no task
09-23 06:58:45.672  3933  3933 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-23 06:58:45.674  3933  3933 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-23 06:58:45.676  5559  5559 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-23 06:58:45.680  5559  5559 D SprintDMHelper: simOperator: 
09-23 06:58:45.680  5559  5559 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-23 06:58:45.689   928  5767 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 10:58:45 GMT], X-Android-Received-Millis=[1474628325688], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474628325663]}
09-23 06:58:45.690   928  2990 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-23 06:58:45.690   928  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-23 06:58:45.690   928  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-23 06:58:45.691   928  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-23 06:58:45.704  3933  5783 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 06:58:45.717  3933  5783 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 06:58:45.717  3933  5783 I SystemUpdateService: now status is 0 (complete)
09-23 06:58:45.717  3933  5783 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 06:58:45.717  3933  5783 I SystemUpdateService: file has been verified
09-23 06:58:45.718  3933  5783 I SystemUpdateService: OTA package size = 21989297
,09-23 06:58:45.723  3933  5783 I SystemUpdateService: showing system update notification
,09-23 06:58:45.734  3933  3933 D SystemUpdateService: onDestroy
,09-23 06:58:45.796  4316  5788 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 06:58:46.607   928  2990 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 06:58:46.932  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 06:58:46.933  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 06:58:46.933  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:58:46.933  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:58:46.933  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:58:46.934  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:58:46.934  5479  5765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:58:46.934  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:58:46.934  5479  5765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-23 06:58:46.934  5479  5765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:58:46.934  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:58:46.935  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:58:46.935  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 06:58:46.935  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:58:46.935  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:58:46.935  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:58:46.938  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:46.938  5479  5525 D BluetoothLeScanner: could not find callback wrapper
09-23 06:58:46.938  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:46.938  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 06:58:46.940  5694  5712 D BtGatt.AdvertiseManager: message : 1
09-23 06:58:46.942  5694  5712 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:58:46.956  5694  5710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:58:46.956  5694  5710 D BtGatt.GattService: Client app is not null!
,09-23 06:58:46.957  5694  5736 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:58:46.958  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 06:58:46.958  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:58:46.958  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:58:46.958  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:58:46.959  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:58:46.961  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:58:46.961  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:58:46.961  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:58:46.962  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 06:58:46.964  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:58:46.964  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:58:46.964  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:58:46.964  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:46.965  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:46.965  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:58:46.969  5479  5525 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,09-23 06:58:46.969  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 06:58:46.971  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:58:46.971  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 06:58:46.971  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 06:58:46.971  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:58:46.971  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 06:58:46.977  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:58:46.977  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:58:46.982  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:58:46.984  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:58:46.984  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:58:46.990  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 06:58:46.991  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 06:58:46.992  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 06:58:46.993  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:46.997  5694  5705 D BtGatt.GattService: registerClient() - UUID=930efdc3-86bf-4a4c-94e7-a083a2bd7824
,09-23 06:58:46.998  5694  5710 D BtGatt.GattService: onClientRegistered() - UUID=930efdc3-86bf-4a4c-94e7-a083a2bd7824, clientIf=5
09-23 06:58:46.998  5479  5490 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 06:58:46.999  5694  5736 D BtGatt.GattService: start scan with filters
,09-23 06:58:47.004  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 06:58:47.004  5694  5713 D BtGatt.ScanManager: handling starting scan
09-23 06:58:47.004  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 06:58:47.004  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 06:58:47.005  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 06:58:47.006  5694  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@851ee98
09-23 06:58:47.008  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 06:58:47.008  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:58:47.008  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 06:58:47.010  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:58:47.015  5694  5710 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 06:58:47.015  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:47.016  5694  5713 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 06:58:47.023  5694  5710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 06:58:47.023  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:47.024  5694  5713 D BtGatt.ScanManager: Starting BLE batch scan
09-23 06:58:47.024  5694  5713 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 06:58:47.036  5694  5710 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 06:58:47.036  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:47.042  5694  5710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 06:58:47.043  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:47.509  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 06:58:47.510  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:58:47.510  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:58:48.334   928  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:58:50.017  5479  5525 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-23 06:58:50.017  5479  5525 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-23 06:58:50.017  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 06:58:50.018  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:58:50.018  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:58:50.023  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:50.024  5694  5734 D BtGatt.GattService: stopScan() - queue size =1
,09-23 06:58:50.026  5694  5705 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:58:50.027  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:50.027  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 06:58:50.027  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:58:50.027  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 06:58:50.028  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 06:58:50.028  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 06:58:50.030  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:50.034  5694  5694 D BtGatt.ScanManager: awakened up at time 217451
,09-23 06:58:50.037  5694  5723 D BtGatt.GattService: registerClient() - UUID=a1d34494-7ef8-422c-8117-5f92c7c443db
09-23 06:58:50.038  5694  5710 D BtGatt.GattService: onClientRegistered() - UUID=a1d34494-7ef8-422c-8117-5f92c7c443db, clientIf=5
,09-23 06:58:50.038  5479  5489 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 06:58:50.038  5694  5705 D BtGatt.GattService: start scan with filters
09-23 06:58:50.039  5694  5710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 06:58:50.039  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:50.040  5694  5713 D BtGatt.ScanManager: stopping BLe Batch
,09-23 06:58:50.042  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 06:58:50.043  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 06:58:50.043  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:50.044  5479  5525 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:58:50.044  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:58:50.044  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:58:50.045  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:58:50.045  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:58:50.045  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-23 06:58:50.045  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:58:50.045  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:58:50.045  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 06:58:50.046  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 06:58:50.046  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:58:50.046  5479  5795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:58:50.046  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:50.047  5694  5723 D BtGatt.GattService: stopScan() - queue size =0
09-23 06:58:50.048  5694  5710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 06:58:50.048  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:58:50.048  5479  5795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:58:50.044  5704  5704 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32402]" dev="sockfs" ino=32402 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:50.044  5704  5704 W Binder_1: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32402]" dev="sockfs" ino=32402 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:58:50.049  5694  5713 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 06:58:50.049  5694  5705 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:58:50.050  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:50.050  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-23 06:58:50.050  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 06:58:50.050  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 06:58:50.050  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 06:58:50.051  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:50.052  5479  5525 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:58:50.055  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:58:50.055  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:58:50.055  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-23 06:58:50.055  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:50.055  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:58:50.055  5479  5525 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 06:58:50.056  5479  5525 D BluetoothAdapter: STATE_ON
,09-23 06:58:50.062  5694  5722 D BtGatt.GattService: registerClient() - UUID=748e5f82-4518-4826-b083-62c0158d35dd,
09-23 06:58:50.062  5694  5710 D BtGatt.GattService: onClientRegistered() - UUID=748e5f82-4518-4826-b083-62c0158d35dd, clientIf=5
09-23 06:58:50.063  5479  5490 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:58:50.063  5694  5712 D BtGatt.AdvertiseManager: message : 0
,09-23 06:58:50.066  5694  5710 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-23 06:58:50.066  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:50.066  5694  5710 D BtGatt.GattService: current time is 217483845499
09-23 06:58:50.067  5694  5710 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 12, -58, 53, 126, 72, 127, 1, -128, -60, 32, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -46, -4, -117, 6, 105, -37, 1, -128, -74, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -74, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 06:58:50.067  5694  5713 D BtGatt.ScanManager: handling starting scan
09-23 06:58:50.068  5694  5710 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 06:58:50.068  5694  5712 D BtGatt.AdvertiseManager: starting multi advertising
09-23 06:58:50.069  5694  5710 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-23 06:58:50.069  5694  5710 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-23 06:58:50.069  5694  5710 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 06:58:50.069  5694  5710 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 06:58:50.070  5694  5710 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-23 06:58:50.075  5694  5710 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 06:58:50.075  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:58:50.076  5694  5713 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-23 06:58:50.084  5694  5710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-23 06:58:50.089  5694  5710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 06:58:50.089  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:58:50.089  5694  5713 D BtGatt.ScanManager: Starting BLE batch scan
09-23 06:58:50.089  5694  5713 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 06:58:50.094  5694  5710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-23 06:58:50.094  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:58:50.094  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:58:50.096  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:58:50.097  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:58:50.097  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:50.097  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:58:50.097  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:58:50.097  5479  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:58:50.098  5479  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:58:50.098  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:58:50.100  5479  5479 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:58:50.100  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:58:50.103  5694  5710 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 06:58:50.104  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:50.109  5694  5710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 06:58:50.109  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:50.115  5694  5710 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-23 06:58:50.115  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:58:50.116  5694  5713 D BtGatt.ScanManager: stopping BLe Batch
,09-23 06:58:50.121  5694  5710 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-23 06:58:50.121  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:58:50.121  5694  5713 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 06:58:50.126  5694  5710 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-23 06:58:50.126  5694  5710 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:58:50.601  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:58:50.602  5479  5479 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:58:50.602  5479  5479 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:58:51.133   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 06:58:51.133   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 06:58:51.364   928  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:58:51.997   928  2988 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,09-23 06:58:53.559   928  2990 D ConnectivityService: handlePromptUnvalidated 101
,09-23 06:58:53.601  5479  5525 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-23 06:58:53.602  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:58:53.602  5479  5525 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:58:53.602  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-23 06:58:53.602  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:58:53.603  5479  5795 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:58:53.604  5479  5795 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-23 06:58:53.604  5479  5795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:58:53.604  5479  5479 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:58:53.603  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:58:53.605  5479  5525 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:58:53.606  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 06:58:53.606  5479  5479 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:58:53.606  5479  5525 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48c1315 removed from the list
09-23 06:58:53.607  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:58:53.607  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 06:58:53.607  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:58:53.607  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 06:58:53.607  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:58:53.609  5479  5525 D BluetoothAdapter: STATE_ON
09-23 06:58:53.609  5479  5525 D BluetoothLeScanner: could not find callback wrapper
09-23 06:58:53.610  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:58:53.610  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 06:58:53.611  5694  5712 D BtGatt.AdvertiseManager: message : 1
09-23 06:58:53.612  5694  5712 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:58:53.626  5694  5710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:58:53.626  5694  5710 D BtGatt.GattService: Client app is not null!
,09-23 06:58:53.627  5694  5723 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:58:53.628  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 06:58:53.629  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:58:53.629  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:58:53.629  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:58:53.629  5479  5525 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:58:53.632  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:58:53.632  5479  5525 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:58:53.632  5479  5525 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:58:53.633  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:58:53.636  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 06:58:53.636  5479  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:58:53.636  5479  5479 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:58:53.637  5479  5525 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b2b62a removed from the list
09-23 06:58:53.637  5479  5525 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 06:58:53.637  5479  5525 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 06:58:53.640  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-23 06:58:53.640  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-23 06:58:53.640  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:58:53.640  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-23 06:58:53.640  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:58:53.641  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 06:58:53.641  5479  5525 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 06:58:53.642  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
09-23 06:58:53.643  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
09-23 06:58:53.645  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,09-23 06:58:53.646  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,09-23 06:58:53.648  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-23 06:58:53.649  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-23 06:58:53.650  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
09-23 06:58:53.651  5479  5525 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
09-23 06:58:53.653  5479  5525 I StreamCopyingThreadTest: Starting test: testRun
,09-23 06:58:53.656  5479  5800 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name)
,09-23 06:58:53.900   928  2988 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-23 06:58:54.137  5479  5479 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 06:58:55.378  5479  5800 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 197
,09-23 06:58:55.379  5479  5800 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 197, name: My test thread name)
09-23 06:58:55.379  5479  5800 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-23 06:58:55.661  5479  5525 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-23 06:58:55.665  5479  5802 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 199, name: My test thread name)
,09-23 06:58:55.666  5479  5802 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 199, thread name: My test thread name)
09-23 06:58:55.666  5479  5802 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 199, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-23 06:58:55.668  5479  5525 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-23 06:58:55.670  5479  5525 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:58:55.673  5479  5525 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-23 06:58:55.676  5479  5803 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 203, name: My test thread name)
09-23 06:58:55.677  5479  5803 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 203, thread name: My test thread name): Test exception.
,09-23 06:58:55.677  5479  5803 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 203, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-23 06:58:55.682  5479  5525 I jxcore-log: *Native tests were executed*
09-23 06:58:55.682  5479  5525 I jxcore-log: 
09-23 06:58:55.682  5479  5525 I jxcore-log: Total number of executed tests:  82
09-23 06:58:55.682  5479  5525 I jxcore-log: 
09-23 06:58:55.682  5479  5525 I jxcore-log: Number of passed tests:  82
09-23 06:58:55.682  5479  5525 I jxcore-log: 
09-23 06:58:55.683  5479  5525 I jxcore-log: Number of failed tests:  0
09-23 06:58:55.683  5479  5525 I jxcore-log: 
09-23 06:58:55.683  5479  5525 I jxcore-log: Number of ignored tests:  0
09-23 06:58:55.683  5479  5525 I jxcore-log: 
09-23 06:58:55.685  5479  5525 I jxcore-log: Total duration:  21934
09-23 06:58:55.685  5479  5525 I jxcore-log: 
09-23 06:58:55.685  5479  5525 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 06:58:55.685  5479  5525 I jxcore-log: 
09-23 06:58:55.692  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.692  5479  5525 I jxcore-log: 
,09-23 06:58:55.698  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.698  5479  5525 I jxcore-log: 
09-23 06:58:55.700  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.700  5479  5525 I jxcore-log: 
09-23 06:58:55.702  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:58:55.702  5479  5525 I jxcore-log: 
09-23 06:58:55.705  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:58:55.705  5479  5525 I jxcore-log: 
09-23 06:58:55.708  5479  5479 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-23 06:58:55.708  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:58:55.708  5479  5525 I jxcore-log: 
09-23 06:58:55.712  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.712  5479  5525 I jxcore-log: 
09-23 06:58:55.715  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.715  5479  5525 I jxcore-log: 
09-23 06:58:55.717  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:58:55.717  5479  5525 I jxcore-log: 
09-23 06:58:55.718  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:58:55.718  5479  5525 I jxcore-log: 
09-23 06:58:55.719  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:58:55.719  5479  5525 I jxcore-log: 
09-23 06:58:55.721  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 06:58:55.721  5479  5525 I jxcore-log: 
,09-23 06:58:55.722  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.722  5479  5525 I jxcore-log: 
,09-23 06:58:55.724  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.724  5479  5525 I jxcore-log: 
09-23 06:58:55.725  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.725  5479  5525 I jxcore-log: 
09-23 06:58:55.727  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.727  5479  5525 I jxcore-log: 
,09-23 06:58:55.728  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.728  5479  5525 I jxcore-log: 
09-23 06:58:55.729  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.729  5479  5525 I jxcore-log: 
09-23 06:58:55.730  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.730  5479  5525 I jxcore-log: 
,09-23 06:58:55.731  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.731  5479  5525 I jxcore-log: 
,09-23 06:58:55.732  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.732  5479  5525 I jxcore-log: 
09-23 06:58:55.733  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.733  5479  5525 I jxcore-log: 
09-23 06:58:55.734  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.734  5479  5525 I jxcore-log: 
09-23 06:58:55.735  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.735  5479  5525 I jxcore-log: 
09-23 06:58:55.735  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.735  5479  5525 I jxcore-log: 
09-23 06:58:55.736  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.736  5479  5525 I jxcore-log: 
09-23 06:58:55.737  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.737  5479  5525 I jxcore-log: 
09-23 06:58:55.738  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:58:55.738  5479  5525 I jxcore-log: 
09-23 06:58:55.738  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:58:55.738  5479  5525 I jxcore-log: 
09-23 06:58:55.739  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:58:55.739  5479  5525 I jxcore-log: 
,09-23 06:58:55.741  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.741  5479  5525 I jxcore-log: 
09-23 06:58:55.742  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.742  5479  5525 I jxcore-log: 
09-23 06:58:55.743  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.743  5479  5525 I jxcore-log: 
,09-23 06:58:55.744  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:58:55.744  5479  5525 I jxcore-log: 
09-23 06:58:55.745  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:58:55.745  5479  5525 I jxcore-log: 
09-23 06:58:55.746  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.746  5479  5525 I jxcore-log: 
09-23 06:58:55.747  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.747  5479  5525 I jxcore-log: 
,09-23 06:58:55.747  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:58:55.747  5479  5525 I jxcore-log: 
09-23 06:58:55.748  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-23 06:58:55.748  5479  5525 I jxcore-log: 
09-23 06:58:55.749  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:58:55.749  5479  5525 I jxcore-log: 
09-23 06:58:55.749  5479  5525 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 06:58:55.749  5479  5525 I jxcore-log: 
,09-23 06:58:56.253  5804  5804 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 06:58:56.259  5804  5804 D AndroidRuntime: CheckJNI is OFF
,09-23 06:58:56.288  5804  5804 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 06:58:56.323  5804  5804 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 06:58:56.341  5804  5804 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 06:58:56.352   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-23 06:58:56.353   928   941 I ActivityManager: Killing 5479:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 06:58:56.436   928  3242 D GraphicsStats: Buffer count: 2
09-23 06:58:56.436   928  3620 I WindowState: WIN DEATH: Window{42ff64 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-23 06:58:56.437   928  2989 D WifiService: Client connection lost with reason: 4
,09-23 06:58:56.496   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-23 06:58:56.497   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-23 06:58:56.498   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-23 06:58:56.498   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 06:58:56.498   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:56.498   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:56.498   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:58:56.498   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 06:58:56.498   928   941 I ActivityManager:   Force finishing activity ActivityRecord{9be96b1 u0 com.test.thalitest/.MainActivity t2}
09-23 06:58:56.499   928   951 I art     : Starting a blocking GC Explicit
,09-23 06:58:56.508   928  3432 W ActivityManager: Spurious death for ProcessRecord{48d78e7 0:com.test.thalitest/u0a77}, curProc for 5479: null
,09-23 06:58:56.508   928  2988 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,09-23 06:58:56.511   928   946 W WindowManager: Attempted to add application window with unknown token Token{5f64796 ActivityRecord{9be96b1 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-23 06:58:56.512   928   946 W WindowManager: Token{5f64796 ActivityRecord{9be96b1 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{5f64796 ActivityRecord{9be96b1 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-23 06:58:56.512   928   946 W WindowManager: view not successfully added to wm, removing view
09-23 06:58:56.512   928   946 W WindowManager: Exception when adding starting window
09-23 06:58:56.512   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{876a47e V.E...... R.....ID 0,0-0,0} not attached to window manager
09-23 06:58:56.512   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-23 06:58:56.512   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-23 06:58:56.512   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-23 06:58:56.512   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-23 06:58:56.512   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-23 06:58:56.512   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:56.512   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:56.512   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:58:56.512   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 06:58:56.583   928   951 I art     : Explicit concurrent mark sweep GC freed 44693(2MB) AllocSpace objects, 9(296KB) LOS objects, 33% free, 28MB/43MB, paused 1.675ms total 83.308ms
,09-23 06:58:56.602   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 06:58:56.605  5804  5804 I art     : System.exit called, status: 0
,09-23 06:58:56.605  5804  5804 I AndroidRuntime: VM exiting with result code 0.
,09-23 06:58:56.609   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 06:58:56.621   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-23 06:58:56.627  5694  5694 D BluetoothMapAppObserver: onReceive
09-23 06:58:56.627  5694  5694 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-23 06:58:56.629  3516  3990 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-23 06:58:56.634  3436  3436 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-23 06:58:56.637   928  2980 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 06:58:56.652  3407  5816 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-23 06:58:56.654  3436  5815 I Keyboard.Facilitator.DecoderInitializer: run()
,09-23 06:58:56.675  3436  5815 I Decoder : createOrResetDecoder
,09-23 06:58:56.678  3587  3587 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 06:58:56.694   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-23 06:58:56.697  3672  3672 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-23 06:58:56.698  3672  3672 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 06:58:56.704    29    29 W kworker/2:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:58:56.717  3933  5821 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-23 06:58:56.718  3672  3672 I ConfigService: onCreate
09-23 06:58:56.718  3933  5821 D AccountUtils: Clearing selected account for com.test.thalitest
,09-23 06:58:56.714    29    29 W kworker/2:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:58:56.738    29    29 W kworker/2:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:58:56.743  3436  5815 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-23 06:58:56.780  3407  5816 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
09-23 06:58:56.781  3407  5816 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-23 06:58:56.781  3407  5816 E AndroidRuntime: Process: android.process.acore, PID: 3407
09-23 06:58:56.781  3407  5816 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:58:56.781  3407  5816 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 06:58:56.787   928  5825 E DropBoxManagerService: Can't write: system_app_crash
09-23 06:58:56.787   928  5825 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:58:56.787   928  5825 E DropBoxManagerService: 	... 5 more
,09-23 06:58:56.795  3933  5821 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-23 06:58:56.811  3407  5816 I Process : Sending signal. PID: 3407 SIG: 9
,09-23 06:58:56.851   928  3631 I ActivityManager: Process android.process.acore (pid 3407) has died
,09-23 06:58:56.851   928  3631 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-23 06:58:57.115   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
