#### Test 8670713946f5300_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-26 06:54:16.602   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-26 06:54:16.602   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 06:54:17.127  5612  5612 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 06:54:17.132  5612  5612 D AndroidRuntime: CheckJNI is OFF
09-26 06:54:17.163  5612  5612 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 06:54:17.199  5612  5612 I Radio-JNI: register_android_hardware_Radio DONE
09-26 06:54:17.215  5612  5612 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-26 06:54:17.219   933  3115 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-26 06:54:17.258   933  3115 I ActivityManager: Start proc 5621:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-26 06:54:17.274  5612  5612 D AndroidRuntime: Shutting down VM
,09-26 06:54:17.600   933  5533 I WindowManager: Screenshot max retries 4 of Token{32a40ac ActivityRecord{9cd0e5f u0 com.test.thalitest/.MainActivity t2}} appWin=Window{9146a57 u0 Starting com.test.thalitest} drawState=2
,09-26 06:54:17.664  5621  5621 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-26 06:54:17.699  5621  5621 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-26 06:54:17.724  5621  5621 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 678-697)
,09-26 06:54:17.724  5621  5621 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-26 06:54:17.743  5621  5621 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cddce8}
09-26 06:54:17.744  5621  5621 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-26 06:54:17.744  5621  5621 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-26 06:54:17.749  5621  5621 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-26 06:54:17.750  5621  5621 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-26 06:54:17.787  5621  5621 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-26 06:54:17.800  5621  5621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-26 06:54:17.800  5621  5621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 06:54:17.800  5621  5621 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-26 06:54:17.800  5621  5621 I Adreno  : Build Date                       : 12/06/15
09-26 06:54:17.800  5621  5621 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-26 06:54:17.800  5621  5621 I Adreno  : Local Branch                     : mybranch17112971
09-26 06:54:17.800  5621  5621 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-26 06:54:17.800  5621  5621 I Adreno  : Remote Branch                    : NONE
09-26 06:54:17.800  5621  5621 I Adreno  : Reconstruct Branch               : NOTHING
,09-26 06:54:17.857   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77c4d4f:true
,09-26 06:54:17.891   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28301]" dev="sockfs" ino=28301 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 06:54:17.891   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[28301]" dev="sockfs" ino=28301 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 06:54:17.906  5621  5621 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-26 06:54:17.915  5621  5621 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-26 06:54:17.946  5621  5658 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-26 06:54:17.945   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32562]" dev="sockfs" ino=32562 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 06:54:17.945   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32562]" dev="sockfs" ino=32562 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 06:54:17.948  5533  5533 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28312]" dev="sockfs" ino=28312 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 06:54:17.948  5533  5533 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28312]" dev="sockfs" ino=28312 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 06:54:17.954  5621  5645 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-26 06:54:17.977  5621  5658 I OpenGLRenderer: Initialized EGL, version 1.4
,09-26 06:54:18.065   933   951 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +462ms (total +834ms)
,09-26 06:54:18.110  5621  5621 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5621
,09-26 06:54:18.197  5621  5621 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 06:54:18.318  5621  5660 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -580650704
,09-26 06:54:18.322  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 06:54:18.322  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 06:54:18.322  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 06:54:18.322  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 06:54:18.322  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-26 06:54:18.322  5621  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e28af9 added. We now have 1 listener(s)
09-26 06:54:18.324  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-26 06:54:18.325  5621  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 06:54:18.325  5621  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:54:18.325  5621  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-26 06:54:18.327  5621  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d445ec added. We now have 1 listener(s)
09-26 06:54:18.328  5621  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:54:18.332   933  2962 D WifiService: New client listening to asynchronous messages
,09-26 06:54:18.333  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 06:54:18.333  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-26 06:54:18.333  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-26 06:54:18.333  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-26 06:54:18.333  5621  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-26 06:54:18.335  5621  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:18.336  5621  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-26 06:54:18.342  5621  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:18.342  5621  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:54:18.342  5621  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 06:54:18.342  5621  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 06:54:18.343  5621  5660 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 06:54:18.345  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:18.349  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:18.359  5621  5621 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 06:54:18.642  5621  5667 W jxcore-log: Initializing JXcore engine
09-26 06:54:18.642  5621  5667 W jxcore-log: JXcore engine is ready
,09-26 06:54:18.668  5667  5667 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=2919 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-26 06:54:18.668  5667  5667 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15393]" dev="sockfs" ino=15393 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-26 06:54:18.668  5667  5667 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-26 06:54:18.668  5667  5667 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32542]" dev="sockfs" ino=32542 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-26 06:54:18.676  5621  5667 W jxcore-log: Starting JXcore engine
,09-26 06:54:18.732  5621  5667 W jxcore-log: Platform android
09-26 06:54:18.732  5621  5667 W jxcore-log: 
,09-26 06:54:18.733  5621  5667 W jxcore-log: Process ARCH arm
09-26 06:54:18.733  5621  5667 W jxcore-log: 
,09-26 06:54:18.759   933  2961 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 06:54:18.829  5621  5667 I jxcore-log: JXcore Cordova bridge is ready!
09-26 06:54:18.829  5621  5667 I jxcore-log: 
09-26 06:54:18.830  5621  5667 W jxcore-log: JXcore engine is started
,09-26 06:54:18.845  5621  5660 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 06:54:18.851  5621  5621 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 06:54:26.604   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:27.605   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:28.484  5621  5667 I jxcore-log: 2016-09-26 10:54:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-26 06:54:28.484  5621  5667 I jxcore-log: 
,09-26 06:54:28.486  5621  5667 I jxcore-log: 2016-09-26 10:54:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-26 06:54:28.486  5621  5667 I jxcore-log: 
,09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:28.489  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:54:28.491  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:54:28.493  5621  5667 I jxcore-log: 2016-09-26 10:54:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-26 06:54:28.493  5621  5667 I jxcore-log: 
,09-26 06:54:28.495  5621  5667 I jxcore-log: 2016-09-26 10:54:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-26 06:54:28.495  5621  5667 I jxcore-log: 
,09-26 06:54:28.606   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:28.738  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 06:54:28.738  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f998d83 added. We now have 2 listener(s)
,09-26 06:54:28.739  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 06:54:28.739  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:54:28.739  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 06:54:28.739  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:54:28.739  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d15b00 added. We now have 2 listener(s)
09-26 06:54:28.739  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 06:54:28.740  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 06:54:28.742  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:28.745  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:54:28.745  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:28.746  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 06:54:28.746  5621  5667 D executeNativeTests: Running unit tests
,09-26 06:54:28.753  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:28.758  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:28.784  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 06:54:28.784  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e added. We now have 3 listener(s)
,09-26 06:54:28.785  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 06:54:28.785  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:54:28.785  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 06:54:28.785  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:54:28.785  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf added. We now have 3 listener(s)
09-26 06:54:28.785  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:54:28.785  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 06:54:28.787  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:28.789  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:54:28.790  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:28.791  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 06:54:28.794  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 06:54:28.794  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 06:54:28.794  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 06:54:28.794  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 06:54:28.794  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:28.795  5621  5667 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-26 06:54:28.795  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-26 06:54:28.795  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-26 06:54:28.795  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 06:54:28.795  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 06:54:28.795  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 06:54:28.796  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:28.796  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:28.796  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:28.796  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:28.796  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.796  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:28.796  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 06:54:28.796  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e removed from the list
,09-26 06:54:28.796  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:28.796  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf removed from the list
09-26 06:54:28.798  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:28.798  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:28.798  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:28.799  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.799  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:28.799  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:28.799  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:28.799  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:28.799  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
,09-26 06:54:28.800  5621  5667 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-26 06:54:28.801  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:28.801  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:28.801  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:28.801  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:28.801  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.801  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:28.801  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:28.801  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:28.801  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:28.801  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:28.801  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.801  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:28.801  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.801  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:28.802  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:28.802  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:28.802  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:28.802  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
,09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-26 06:54:28.804  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 06:54:28.805  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:28.805  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:28.805  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:28.805  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:54:28.805  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.805  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:28.805  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:28.805  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:28.805  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:28.805  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:28.805  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.806  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:28.806  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:28.806  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:28.807  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:28.807  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:28.807  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:28.807  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:28.807  5621  5667 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 06:54:28.808  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:28.810  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:54:28.811  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:54:28.811  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:54:28.811  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:54:28.811  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 06:54:28.811  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 06:54:28.811  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:28.811  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:28.813  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:54:28.813  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 06:54:28.813  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:28.816  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:54:28.816  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:28.817  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 06:54:28.817  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 06:54:28.818  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-26 06:54:28.819  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-26 06:54:28.819  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 06:54:28.819  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-26 06:54:28.819  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 06:54:28.820  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:54:28.822  4574  4587 D BtGatt.GattService: registerClient() - UUID=48105be4-6e4d-4073-810f-8f07a4109ab4
,09-26 06:54:28.823  4574  4661 D BtGatt.GattService: onClientRegistered() - UUID=48105be4-6e4d-4073-810f-8f07a4109ab4, clientIf=5
,09-26 06:54:28.824  5621  5632 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 06:54:28.824  4574  4799 D BtGatt.GattService: start scan with filters
,09-26 06:54:28.828  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 06:54:28.828  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 06:54:28.828  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 06:54:28.828  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 06:54:28.828  4574  4666 D BtGatt.ScanManager: handling starting scan
,09-26 06:54:28.830  4574  4666 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:54:28.830  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 06:54:28.830  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-26 06:54:28.831  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 06:54:28.831  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 06:54:28.832  5621  5667 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 06:54:28.837  4574  4661 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 06:54:28.837  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:28.838  4574  4666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 06:54:28.844  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 06:54:28.844  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:28.845  4574  4666 D BtGatt.ScanManager: Starting BLE batch scan
,09-26 06:54:28.845  4574  4666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 06:54:28.854  4574  4661 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-26 06:54:28.854  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:28.859  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 06:54:28.860  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:29.332  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-26 06:54:29.333  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 06:54:29.333  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 06:54:29.396   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-26 06:54:29.399   933  2963 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-26 06:54:29.607   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:30.608   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:31.609   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 06:54:32.423   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-26 06:54:32.427   933  2963 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-26 06:54:33.836  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:33.837  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:33.837  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 06:54:33.837  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:33.837  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:54:33.837  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 06:54:33.837  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-26 06:54:33.837  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 06:54:33.837  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 06:54:33.838  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 06:54:33.838  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 06:54:33.839  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:33.840  4574  4587 D BtGatt.GattService: stopScan() - queue size =1
,09-26 06:54:33.841  4574  4799 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 06:54:33.842  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:33.843  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 06:54:33.843  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 06:54:33.843  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-26 06:54:33.843  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 06:54:33.845  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:54:33.845  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 06:54:33.845  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-26 06:54:33.846  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 06:54:33.847  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:33.849  4574  4574 D BtGatt.ScanManager: awakened up at time 236822
,09-26 06:54:33.851  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:33.851  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:33.851  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:33.851  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
,09-26 06:54:33.851  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:33.851  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:33.851  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:33.851  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:33.851  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:33.851  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:33.852  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:33.853  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-26 06:54:33.853  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:33.854  4574  4666 D BtGatt.ScanManager: stopping BLe Batch
09-26 06:54:33.858  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:54:33.858  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 06:54:33.866  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-26 06:54:33.866  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:33.866  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 06:54:33.867  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:54:33.868  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:54:33.868  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 06:54:33.868  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 06:54:33.869  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:33.873  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:33.873  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:33.873  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:33.878  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:54:33.879  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:33.879  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:33.882  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 06:54:33.891  4574  4661 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-26 06:54:33.891  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:33.892  4574  4661 D BtGatt.GattService: current time is 236865725791
09-26 06:54:33.892  4574  4661 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -78, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -70, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-26 06:54:33.895  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 06:54:33.897  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 06:54:33.897  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 06:54:33.898  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 06:54:33.898  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 06:54:33.898  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-26 06:54:34.383  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 06:54:35.455   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 06:54:36.610   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:37.612   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:38.614   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:38.853  5621  5667 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-26 06:54:38.855  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:38.862  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:54:38.864  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:38.864  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 06:54:38.865  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:54:38.865  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 06:54:38.865  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 06:54:38.865  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:38.865  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:54:38.869  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:38.871  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:54:38.876  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:38.880  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 06:54:38.880  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-26 06:54:38.880  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 06:54:38.881  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:54:38.886  4574  4587 D BtGatt.GattService: registerClient() - UUID=c9e372e9-c5a1-4d22-825e-0deaca90701e
,09-26 06:54:38.887  4574  4661 D BtGatt.GattService: onClientRegistered() - UUID=c9e372e9-c5a1-4d22-825e-0deaca90701e, clientIf=5
09-26 06:54:38.887  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 06:54:38.888  4574  4588 D BtGatt.GattService: start scan with filters
,09-26 06:54:38.892  4574  4666 D BtGatt.ScanManager: handling starting scan
09-26 06:54:38.893  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 06:54:38.893  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-26 06:54:38.893  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-26 06:54:38.893  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 06:54:38.897  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 06:54:38.897  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-26 06:54:38.898  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 06:54:38.902  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 06:54:38.902  4574  4661 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 06:54:38.903  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.903  4574  4666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 06:54:38.909  5621  5667 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 06:54:38.912  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:38.912  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 06:54:38.912  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.912  5621  5667 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-26 06:54:38.913  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:38.913  4574  4666 D BtGatt.ScanManager: Starting BLE batch scan
09-26 06:54:38.913  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 06:54:38.913  4574  4666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-26 06:54:38.913  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:38.913  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:54:38.913  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 06:54:38.913  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 06:54:38.913  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 06:54:38.913  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 06:54:38.913  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 06:54:38.913  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 06:54:38.915  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:38.915  4574  4587 D BtGatt.GattService: stopScan() - queue size =1
,09-26 06:54:38.917  4574  4588 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 06:54:38.919  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:38.919  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 06:54:38.919  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 06:54:38.919  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 06:54:38.919  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 06:54:38.921  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 06:54:38.921  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:38.921  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 06:54:38.921  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:38.922  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:38.923  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:38.923  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:38.923  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:54:38.923  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:54:38.924  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:38.924  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:54:38.924  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:38.924  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:38.924  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:38.924  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 06:54:38.924  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:38.927  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:54:38.927  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 06:54:38.928  4574  4661 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 06:54:38.928  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:38.932  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:54:38.933  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:54:38.933  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 06:54:38.933  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 06:54:38.934  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:38.934  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 06:54:38.934  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.936  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:38.936  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:38.939  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:54:38.939  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:38.939  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:38.940  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:38.940  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:38.940  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:38.940  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:38.940  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:38.940  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:38.940  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:38.940  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:54:38.941  5621  5667 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 06:54:38.942  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:38.943  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:54:38.943  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:38.944  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:38.943  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 06:54:38.944  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.944  4574  4666 D BtGatt.ScanManager: stopping BLe Batch
,09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:38.947  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:54:38.950  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:38.950  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:54:38.950  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:54:38.950  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:54:38.950  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 06:54:38.950  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 06:54:38.950  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:38.950  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:38.950  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 06:54:38.951  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.951  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 06:54:38.953  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:54:38.953  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:38.956  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:38.957  4574  4661 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 06:54:38.957  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.957  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 06:54:38.957  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 06:54:38.958  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 06:54:38.958  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:54:38.960  4574  4799 D BtGatt.GattService: registerClient() - UUID=99d3d639-e7b2-4623-b459-078ed07ced8a
09-26 06:54:38.960  4574  4661 D BtGatt.GattService: onClientRegistered() - UUID=99d3d639-e7b2-4623-b459-078ed07ced8a, clientIf=5
,09-26 06:54:38.960  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 06:54:38.961  4574  4587 D BtGatt.GattService: start scan with filters
,09-26 06:54:38.963  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 06:54:38.963  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 06:54:38.963  4574  4666 D BtGatt.ScanManager: handling starting scan
09-26 06:54:38.963  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 06:54:38.963  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 06:54:38.965  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 06:54:38.966  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 06:54:38.966  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 06:54:38.967  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 06:54:38.968  4574  4661 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-26 06:54:38.968  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.969  4574  4666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 06:54:38.969  5621  5667 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 06:54:38.974  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 06:54:38.974  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:38.975  4574  4666 D BtGatt.ScanManager: Starting BLE batch scan
09-26 06:54:38.975  4574  4666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 06:54:38.983  4574  4661 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 06:54:38.984  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:38.989  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-26 06:54:38.989  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:39.467  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-26 06:54:39.467  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:54:39.468  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 06:54:39.615   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:40.615   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:41.616   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 06:54:43.970  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:43.970  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:43.970  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 06:54:43.971  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:43.971  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:54:43.971  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 06:54:43.971  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 06:54:43.971  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-26 06:54:43.971  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-26 06:54:43.972  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 06:54:43.972  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 06:54:43.974  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:43.975  4574  4799 D BtGatt.GattService: stopScan() - queue size =1
,09-26 06:54:43.977  4574  4588 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 06:54:43.978  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:43.978  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 06:54:43.979  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 06:54:43.979  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 06:54:43.979  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 06:54:43.981  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:54:43.981  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:43.982  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 06:54:43.982  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:43.984  4574  4574 D BtGatt.ScanManager: awakened up at time 246957
09-26 06:54:43.985  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:43.988  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:43.988  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:43.988  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:43.991  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 06:54:43.992  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:43.992  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:54:43.992  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 06:54:43.993  4574  4666 D BtGatt.ScanManager: stopping BLe Batch
,09-26 06:54:43.999  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 06:54:43.999  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:54:44.000  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 06:54:44.001  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:54:44.002  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:54:44.002  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 06:54:44.002  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:44.003  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:44.006  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:44.006  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:44.006  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:44.009  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:54:44.010  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:44.011  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 06:54:44.013  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 06:54:44.017  4574  4661 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-26 06:54:44.017  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:54:44.017  4574  4661 D BtGatt.GattService: current time is 246991108816
,09-26 06:54:44.017  4574  4661 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -78, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -81, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -71, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -75, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 06:54:44.018  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 06:54:44.018  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 06:54:44.018  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 06:54:44.018  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 06:54:44.018  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 06:54:44.018  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 06:54:44.514  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-26 06:54:44.514  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:44.515  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 06:54:48.989  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:48.990  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 06:54:48.990  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 06:54:48.990  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:48.990  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:48.990  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:48.991  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:48.991  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:48.991  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:48.991  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 06:54:48.991  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:48.992  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:48.993  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:48.997  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:48.998  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:48.998  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:54:49.000  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.001  5621  5667 D BluetoothLeScanner: could not find callback wrapper
,09-26 06:54:49.001  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 06:54:49.001  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.001  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.002  5621  5667 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-26 06:54:49.004  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:49.004  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.005  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.005  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.005  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.005  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.005  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.005  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:49.006  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.006  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.006  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.006  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.006  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.006  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.008  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:54:49.008  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.008  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.009  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.009  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.009  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.009  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.009  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
,09-26 06:54:49.011  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-26 06:54:49.011  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:49.011  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.011  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.011  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.011  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.011  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.011  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.011  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.011  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.011  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.012  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:49.012  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.012  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.012  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.013  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.013  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.013  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.014  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.014  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.014  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 06:54:49.014  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.014  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.015  5621  5667 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-26 06:54:49.015  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:49.015  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.015  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.015  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.016  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.016  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.016  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
,09-26 06:54:49.016  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.016  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.016  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.016  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.016  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.016  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.016  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.018  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.018  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.019  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.019  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:54:49.019  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.020  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.020  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:49.020  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
,09-26 06:54:49.021  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-26 06:54:49.021  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:49.021  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.021  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.021  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:54:49.021  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:49.021  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:49.021  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.021  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.021  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.021  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.021  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.021  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.022  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.022  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.023  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.023  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.023  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.024  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.024  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.024  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.024  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.024  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.025  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 06:54:49.025  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 06:54:49.025  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-26 06:54:49.025  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 06:54:49.025  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 06:54:49.025  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-26 06:54:49.026  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 06:54:49.026  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 06:54:49.026  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 06:54:49.026  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:49.026  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.026  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.026  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.026  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.026  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.026  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.026  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.026  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.027  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.027  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.027  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.027  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.027  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.028  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.028  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.028  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.029  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.029  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.029  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.029  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.029  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.030  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 06:54:49.030  5621  5667 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 06:54:49.030  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 06:54:49.033  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 06:54:49.033  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:,210:210]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 06:54:49.033  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 06:54:49.034  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 06:54:49.035  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 06:54:49.035  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 06:54:49.035  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-26 06:54:49.035  5621  5667 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 06:54:49.035  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-26 06:54:49.035  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 06:54:49.035  5621  5667 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 06:54:49.035  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-26 06:54:49.035  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 06:54:49.035  5621  5667 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 06:54:49.036  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-26 06:54:49.039  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-26 06:54:49.040  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-26 06:54:49.040  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-26 06:54:49.041  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-26 06:54:49.041  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-26 06:54:49.041  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-26 06:54:49.041  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 06:54:49.041  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-26 06:54:49.041  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-26 06:54:49.042  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:49.042  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.042  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.042  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.042  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.042  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.043  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-26 06:54:49.044  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.044  5621  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:54:49.044  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.044  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.044  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.044  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.044  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.044  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.044  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.044  5621  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-26 06:54:49.044  5621  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-26 06:54:49.044  5621  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-26 06:54:49.045  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.045  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.046  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.047  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.047  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.047  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.047  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.047  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.048  5621  5667 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-26 06:54:49.048  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-26 06:54:49.048  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:49.048  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.048  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.049  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.049  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.049  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.049  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.049  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.049  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.049  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.049  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.049  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.049  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.049  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.045  4588  4588 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32588]" dev="sockfs" ino=32588 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 06:54:49.045  4588  4588 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32588]" dev="sockfs" ino=32588 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 06:54:49.051  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.051  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.051  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.052  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.052  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.052  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.052  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.052  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.053  5621  5667 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-26 06:54:49.053  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:49.054  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.054  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.054  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.054  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.054  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.054  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.054  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.054  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.054  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.054  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.054  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.054  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.054  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.055  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.055  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.055  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.056  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.056  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.056  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.056  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.056  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.058  5621  5667 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-26 06:54:49.058  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-26 06:54:49.058  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 06:54:49.058  5621  5667 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-26 06:54:49.058  5621  5667 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 06:54:49.058  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-26 06:54:49.058  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 06:54:49.058  5621  5667 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-26 06:54:49.058  5621  5667 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 06:54:49.058  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 06:54:49.059  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 06:54:49.059  5621  5667 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-26 06:54:49.059  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:49.059  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:49.059  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:49.059  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.059  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.059  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.059  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.059  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.059  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.059  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.059  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.059  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.059  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.059  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.060  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:49.060  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:49.060  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:49.061  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:49.061  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:49.061  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:49.061  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.061  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.062  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:49.062  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.062  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:49.062  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:49.062  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:49.062  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:49.062  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:49.062  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:49.062  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:51.617   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:52.618   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:53.619   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:54.063  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:54.063  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.063  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:54.063  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.064  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:54.064  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.064  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:54.064  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:54.064  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:54.065  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:54:54.065  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.065  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.065  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.065  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.065  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
,09-26 06:54:54.066  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:54.066  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.066  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.066  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:54.066  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.070  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:54:54.071  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:54.071  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:54:54.073  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:54.073  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:54.073  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 06:54:54.073  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:54.073  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.077  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-26 06:54:54.080  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:54.081  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-26 06:54:54.082  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-26 06:54:54.083  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-26 06:54:54.083  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-26 06:54:54.083  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 06:54:54.083  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-26 06:54:54.084  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:54.084  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 06:54:54.084  5621  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:54:54.084  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-26 06:54:54.084  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-26 06:54:54.084  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.084  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 06:54:54.084  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.084  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-26 06:54:54.084  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.084  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 06:54:54.084  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 06:54:54.084  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 06:54:54.085  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 06:54:54.085  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:54.085  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:54.086  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:54.086  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 06:54:54.086  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 06:54:54.086  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.086  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.087  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:54:54.087  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.087  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:54:54.087  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:54.087  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:54.087  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:54:54.087  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:54.088  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:54.088  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:54.088  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.088  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:54.088  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.088  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.088  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.088  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:54.088  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.088  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:54.088  4588  4588 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33718]" dev="sockfs" ino=33718 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 06:54:54.088  4588  4588 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33718]" dev="sockfs" ino=33718 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 06:54:54.090  5621  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 06:54:54.090  5621  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-26 06:54:54.090  5621  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 06:54:54.091  5621  5621 V io.jxcore.node.ConnectionHelper,: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:54:54.091  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 06:54:54.097  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 06:54:54.097  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:54:54.097  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 06:54:54.098  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 06:54:54.098  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.100  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.100  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:54.101  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:54.102  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:54.102  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:54:54.102  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:54.103  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:54.103  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:54.103  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.103  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 06:54:54.103  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.103  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:54:54.103  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:54:54.104  5621  5667 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-26 06:54:54.104  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 06:54:54.105  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 06:54:54.105  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 06:54:54.105  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 06:54:54.105  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:54.105  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:54.105  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:54.105  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:54.105  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.105  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:54.107  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:54:54.107  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.107  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:54:54.107  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.107  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.107  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:54.107  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.108  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:54:54.108  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:54.110  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:54:54.110  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:54:54.110  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.110  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 06:54:54.111  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:54.111  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:54.111  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:54:54.112  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:54:54.112  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:54.112  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:54.112  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.112  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
,09-26 06:54:54.116  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:54:54.116  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:54.116  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:54.116  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:54:54.116  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.117  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.117  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.117  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.117  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.117  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 06:54:54.117  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.117  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.117  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.117  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.118  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:54.118  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:54.118  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:54:54.119  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:54:54.119  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:54.119  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:54.119  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.119  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.120  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:54:54.120  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:54:54.120  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:54:54.120  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:54:54.120  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.120  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:54.120  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3502e2e not in the list
09-26 06:54:54.120  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.120  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.120  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:54.120  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.121  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:54.121  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:54.121  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:54.122  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:54:54.122  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:54:54.122  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:54:54.123  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:54:54.123  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:54:54.123  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:54:54.123  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:54:54.123  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc9ddcf not in the list
09-26 06:54:54.124  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-26 06:54:54.124  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 06:54:54.124  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-26 06:54:54.124  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 06:54:54.124  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-26 06:54:54.124  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 06:54:54.126  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-26 06:54:54.126  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-26 06:54:54.127  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-26 06:54:54.127  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 06:54:54.127  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-26 06:54:54.127  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 06:54:54.127  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-26 06:54:54.127  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-26 06:54:54.128  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-26 06:54:54.128  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-26 06:54:54.128  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-26 06:54:54.128  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-26 06:54:54.128  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-26 06:54:54.129  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-26 06:54:54.130  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 06:54:54.130  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a23978d added. We now have 3 listener(s)
09-26 06:54:54.131  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:54:54.132  5621  5667 D BluetoothAdapter: enable(): BT is already enabled..!
09-26 06:54:54.133   933  3116 D WifiService: setWifiEnabled: true pid=5621, uid=10077
09-26 06:54:54.133   933  3116 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 06:54:54.173  4574  4779 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-26 06:54:54.173  4574  4792 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-26 06:54:54.611  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 06:54:54.620   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:55.621   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:54:56.621   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 06:54:58.764   933  2961 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 06:54:59.138  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 06:54:59.138  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d62ad42 added. We now have 4 listener(s)
09-26 06:54:59.138  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:54:59.150  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:59.151  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d62ad42 removed from the list
,09-26 06:54:59.151  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:59.151  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:59.151  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:54:59.153  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 06:54:59.154  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6da1153 added. We now have 4 listener(s)
,09-26 06:54:59.154  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 06:54:59.158  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:54:59.159  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6da1153 removed from the list
09-26 06:54:59.159  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:54:59.159  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:54:59.159  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:54:59.161  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 06:54:59.161  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@552da90 added. We now have 4 listener(s)
09-26 06:54:59.161  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:54:59.167   933  3115 D WifiService: setWifiEnabled: false pid=5621, uid=10077
,09-26 06:54:59.167   933  3115 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 06:54:59.173   933  2961 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-26 06:54:59.173   933  2961 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 06:54:59.174   933  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 06:54:59.174   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:54:59.181  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:54:59.182  4574  4657 D BluetoothAdapterState: Current state: ON, message: 23
09-26 06:54:59.182  4574  4657 D BluetoothAdapterProperties: Setting state to 13
09-26 06:54:59.182  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-26 06:54:59.183  4574  4657 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 06:54:59.184  4574  4657 I BluetoothAdapterState: Entering PendingCommandState
,09-26 06:54:59.187  4574  4574 D BluetoothMapService: onReceive
,09-26 06:54:59.188  4574  4574 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 06:54:59.188  4574  4574 D BluetoothMapService: STATE_TURNING_OFF
09-26 06:54:59.189  4574  4574 D BluetoothMapService: MAP Service closeService in
09-26 06:54:59.189  4574  4574 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 06:54:59.189  4574  4574 D ObexServerSockets0: shutdown(block = true)
09-26 06:54:59.190  4574  4834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-26 06:54:59.190  4574  4574 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 06:54:59.191  4574  4574 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 06:54:59.191  4574  4792 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-26 06:54:59.191  4574  4835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 06:54:59.193  4574  4574 I BtOppRfcommListener: stopping Accept Thread
09-26 06:54:59.193  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:59.193  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:54:59.193  4574  5299 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 06:54:59.194  4574  5299 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-26 06:54:59.195  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.195  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:59.195  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 06:54:59.199  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:59.203  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:59.205   933  5361 D DhcpClient: Clearing IP address
,09-26 06:54:59.206   506   927 D CommandListener: Clearing all IP addresses on wlan0
,09-26 06:54:59.208  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:59.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:54:59.210  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:54:59.211  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:59.214   506   927 D CommandListener: Setting iface cfg
09-26 06:54:59.215  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:54:59.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:54:59.216  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:54:59.216  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:54:59.217  3570  5415 V NativeCrypto: Read error: ssl=0x7f918ec100: I/O error during system call, Connection timed out
09-26 06:54:59.218   933   946 I ActivityManager: Start proc 5674:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-26 06:54:59.218  4574  4661 D BluetoothAdapterProperties: Scan Mode:20
09-26 06:54:59.219  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-26 06:54:59.219  3570  5415 V NativeCrypto: SSL shutdown failed: ssl=0x7f918ec100: I/O error during system call, Broken pipe
,09-26 06:54:59.221  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.223   933  3116 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-26 06:54:59.224   933  5359 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-26 06:54:59.224  4574  4574 D HeadsetService: Received stop request...Stopping profile...
09-26 06:54:59.224  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.227   933   933 D BluetoothHeadset: Proxy object disconnected
09-26 06:54:59.227  3119  3972 D BluetoothHeadset: Proxy object disconnected
09-26 06:54:59.227   933   933 D BluetoothHeadset: Proxy object disconnected
09-26 06:54:59.227  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.227  3119  3119 D HeadsetProfile: Bluetooth service disconnected
09-26 06:54:59.228  3794  4031 D BluetoothHeadset: Proxy object disconnected
09-26 06:54:59.228   933  5359 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-26 06:54:59.228   933   933 D BluetoothHeadset: Proxy object disconnected
09-26 06:54:59.228   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-26 06:54:59.228   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 06:54:59.230   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 06:54:59.233  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.233  4574  4574 D A2dpService: Received stop request...Stopping profile...
09-26 06:54:59.233  4574  4808 D A2dpStateMachine: Exit Disconnected: -1
,09-26 06:54:59.237   933   933 D BluetoothA2dp: Proxy object disconnected
,09-26 06:54:59.237  3119  3119 D BluetoothA2dp: Proxy object disconnected
09-26 06:54:59.239  4574  4574 V BluetoothAdapterState: isTurningOff()=true
09-26 06:54:59.239  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.239  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.240  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 06:54:59.241  4574  4574 D HidService: Received stop request...Stopping profile...
09-26 06:54:59.241  4574  4574 D HidService: Stopping Bluetooth HidService
09-26 06:54:59.242  3119  3119 D BluetoothInputDevice: Proxy object disconnected
09-26 06:54:59.242  3119  3119 D HidProfile: Bluetooth service disconnected
09-26 06:54:59.244  4574  4574 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 06:54:59.244  4574  4574 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-26 06:54:59.244  4574  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:54:59.245  4574  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:54:59.245  4574  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:54:59.245  4574  4574 D HealthService: Received stop request...Stopping profile...
09-26 06:54:59.246  4574  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 06:54:59.247  4574  4661 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-26 06:54:59.247  4574  4574 D PanService: Received stop request...Stopping profile...
,09-26 06:54:59.248  4574  4574 D BluetoothMapService: Received stop request...Stopping profile...
,09-26 06:54:59.248  4574  4574 D BluetoothMapService: stop()
09-26 06:54:59.248   933  5362 D DhcpClient: Receive thread stopped
09-26 06:54:59.249   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-26 06:54:59.249   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-26 06:54:59.251  4574  4574 D BluetoothMapAppObserver: deinitObservers()
,09-26 06:54:59.251  4574  4574 D BluetoothMapAppObserver: removeReceiver()
,09-26 06:54:59.251   534   534 E Parcel  : Reading a NULL string not supported here.
09-26 06:54:59.256   933   933 D RttService: SCAN_AVAILABLE : 1
09-26 06:54:59.256   933  3070 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-26 06:54:59.257   933  2963 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-26 06:54:59.258  4574  4574 D SapService: Received stop request...Stopping profile...
09-26 06:54:59.258  4574  4574 V SapService: stop()
09-26 06:54:59.258  3759  3899 W QCNEJ   : |CORE| network lost: 100
09-26 06:54:59.259  3759  3899 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-26 06:54:59.259  3119  3119 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 06:54:59.259  3119  3119 D PanProfile: Bluetooth service disconnected
09-26 06:54:59.259  3119  3119 D BluetoothMap: Proxy object disconnected
09-26 06:54:59.260  4574  4574 V BluetoothAdapterState: isTurningOff()=true
09-26 06:54:59.260  3119  3119 D MapProfile: Bluetooth service disconnected
09-26 06:54:59.260  4574  4574 V BluetoothAdapterState: isTurningOn()=false
,09-26 06:54:59.260  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.260  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:54:59.261  4574  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:54:59.261  4574  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:54:59.261  4574  4779 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 06:54:59.261  4574  4779 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 06:54:59.261  4574  4779 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 06:54:59.261  4574  4779 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 06:54:59.261  4574  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-26 06:54:59.262  4574  4574 V BluetoothAdapterState: isTurningOff()=true
,09-26 06:54:59.262  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.262  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.262  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:54:59.263  4574  4574 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-26 06:54:59.263  4574  4574 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 06:54:59.263  4574  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 06:54:59.264  4574  4574 V BluetoothAdapterState: isTurningOff()=true
09-26 06:54:59.264  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.264  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.264  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:54:59.264  4574  4574 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 06:54:59.264  4574  4661 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 06:54:59.264  4574  4574 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 06:54:59.265  4574  4574 V BluetoothAdapterState: isTurningOff()=true
09-26 06:54:59.265  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.265  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.265  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:54:59.265  4574  4574 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 06:54:59.265  4574  4574 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-26 06:54:59.266   933  2961 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-26 06:54:59.268  4574  4574 D BluetoothMapService: MAP Service closeService in
,09-26 06:54:59.268  4574  4574 V BluetoothAdapterState: isTurningOff()=true
09-26 06:54:59.268  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.268  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.268  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:54:59.268  4574  4574 D BluetoothMapService: cleanup()
09-26 06:54:59.268  4574  4574 D BluetoothMapService: MAP Service closeService in
09-26 06:54:59.269  4574  4574 V BluetoothAdapterState: isTurningOff()=true
09-26 06:54:59.269  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.269  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.269  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 06:54:59.273  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-26 06:54:59.273  4574  4657 D BluetoothAdapterProperties: Setting state to 15
09-26 06:54:59.273  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 06:54:59.274  4574  4657 I BluetoothAdapterState: Entering BleOnState
09-26 06:54:59.275  3119  3968 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 06:54:59.276   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 06:54:59.276  3794  3832 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:54:59.277   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:54:59.277  3119  3137 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 06:54:59.278  5674  5674 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-26 06:54:59.278  3119  3972 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:54:59.278   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-26 06:54:59.278  3119  3130 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 06:54:59.279   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:54:59.279  3119  3968 D BluetoothMap: onBluetoothStateChange: up=false
,09-26 06:54:59.279  3119  3137 D BluetoothPan: onBluetoothStateChange on: false
09-26 06:54:59.280  4574  4657 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-26 06:54:59.280  4574  4657 D BluetoothAdapterProperties: Setting state to 16
09-26 06:54:59.280  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 06:54:59.283  4574  4657 D BluetoothAdapterProperties: onBleDisable
,09-26 06:54:59.283  4574  4657 I BluetoothAdapterState: Entering PendingCommandState
09-26 06:54:59.283  4574  4658 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 06:54:59.284  4574  4779 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 06:54:59.284   933  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 06:54:59.284  4574  4779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:54:59.284  4574  4661 D BluetoothAdapterProperties: Scan Mode:20
09-26 06:54:59.288  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:54:59.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:54:59.289  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.289  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:54:59.296  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:54:59.296  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:54:59.297  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:54:59.297  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:54:59.298  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 06:54:59.300  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:54:59.300  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:54:59.300  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.301  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:54:59.303  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:59.304  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 06:54:59.305  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:59.306  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.307   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad8072a:true
09-26 06:54:59.307   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-26 06:54:59.317   933  3698 I ActivityManager: Start proc 5694:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-26 06:54:59.330   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:54:59.330   506   927 D CommandListener: Clearing all IP addresses on wlan0
09-26 06:54:59.330   506   927 D TetherController: Setting IP forward enable = 0
,09-26 06:54:59.331   933  2963 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-26 06:54:59.333   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 06:54:59.334   933   950 D Tethering: MasterInitialState.processMessage what=3
09-26 06:54:59.336   933  2961 D DhcpClient: doQuit
09-26 06:54:59.336   933  2961 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 06:54:59.337   933  5361 D DhcpClient: onQuitting
09-26 06:54:59.337  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.338  3466  3466 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 06:54:59.339  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.341  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:54:59.341  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:54:59.342  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.342  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:54:59.343  5256  5256 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@14054 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-26 06:54:59.344  3911  3911 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-26 06:54:59.345  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:54:59.346  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:54:59.347  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.347  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:54:59.348  5018  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-26 06:54:59.348  5018  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 06:54:59.348  5018  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-26 06:54:59.348  5018  5042 E SarControlService: no key has been found,reset the power
09-26 06:54:59.348  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 06:54:59.348  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 06:54:59.349  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 06:54:59.349  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:54:59.349  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:54:59.349  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 06:54:59.349  5043  5043 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 06:54:59.350  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:54:59.350  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:54:59.350  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 06:54:59.350  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 06:54:59.350  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 06:54:59.352  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 06:54:59.352  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.352  5043  5043 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-26 06:54:59.354  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000ea03000000000000ffffffff]
09-26 06:54:59.355  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:54:59.355  5043  5057 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-26 06:54:59.355  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 06:54:59.355  5018  5028 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-26 06:54:59.360  5674  5674 D LocalBluetoothProfileManager: Adding local MAP profile
,09-26 06:54:59.362  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000eb03000000000000ffffffff]
09-26 06:54:59.362  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:54:59.362  5043  5057 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-26 06:54:59.363  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 06:54:59.364  5018  5029 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 06:54:59.364  5674  5674 D BluetoothMap: Create BluetoothMap proxy object
09-26 06:54:59.365  3466  3466 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-26 06:54:59.370  3466  3466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-26 06:54:59.388  5694  5694 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-26 06:54:59.390  5674  5674 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-26 06:54:59.402  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,09-26 06:54:59.404  3466  3466 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-26 06:54:59.410   933  5533 I ActivityManager: Killing 4951:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-26 06:54:59.413  3466  3466 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 06:54:59.492  4574  4661 I bt_hci  : shut_down
,09-26 06:54:59.495  4574  4668 D bt_hwcfg: hw_epilog_process
,09-26 06:54:59.496  4574  4668 I bt_vendor: low_power_mode_cb
,09-26 06:54:59.498  4574  4668 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-26 06:54:59.498  4574  4668 I bt_vendor: epilog_cb
09-26 06:54:59.498  4574  4668 I bt_hci  : epilog_finished_callback
,09-26 06:54:59.500  4574  4661 I bt_hci_h4: hal_close
,09-26 06:54:59.501  4574  4661 I bt_userial_vendor: device fd = 54 close
,09-26 06:54:59.518   933  2961 D wifi    : In wifi stop Hal
,09-26 06:54:59.518   933  2961 D wifi    : halHandle = 0x7f905c8680, mVM = 0x7facc0d140, mCls = 0x100a02
09-26 06:54:59.518   933  3465 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 06:54:59.518   933  3465 D WifiHAL : Got a signal to exit!!!
09-26 06:54:59.518   933  3465 I WifiHAL : Exit wifi_event_loop
09-26 06:54:59.518  4992  4992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 06:54:59.518   933  2961 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 06:54:59.519   933  2961 E WifiHAL : Event processing terminated
09-26 06:54:59.519   933  2961 D wifi    : In wifi cleaned up handler
09-26 06:54:59.519   933  2961 I WifiHAL : Internal cleanup completed
09-26 06:54:59.520  4090  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 06:54:59.522  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:59.524  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:54:59.526  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:54:59.543   933  3465 D wifi    : set interface wlan0 flags (DOWN)
,09-26 06:54:59.543   933  2961 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 06:54:59.585  5694  5694 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 06:54:59.585  5694  5694 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.585  5694  5694 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.585  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.586  5694  5694 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.586  5694  5694 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.k.d(PG:583)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.586  5694  5694 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.586  5694  5694 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.586  5694  5694 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:54:59.586  5694  5694 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:54:59.592  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 06:54:59.597  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 06:54:59.601  5674  5674 D DockEventReceiver: finishStartingService: stopping service
09-26 06:54:59.604   933   944 I ActivityManager: Killing 5100:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-26 06:54:59.635  3731  3731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 06:54:59.635  4574  4658 D bt_stack_manager: event_shut_down_stack finished.
09-26 06:54:59.635  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-26 06:54:59.637  4574  4574 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 06:54:59.638  4574  4574 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 06:54:59.638  4574  4574 D BtGatt.GattService: stop()
09-26 06:54:59.638  4574  4574 D BtGatt.AdvertiseManager: advertise clients cleared
09-26 06:54:59.638  4574  4657 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 06:54:59.639  3731  3731 D SystemUpdateService: onCreate
09-26 06:54:59.640  4574  4574 V BluetoothAdapterState: isTurningOff()=false
09-26 06:54:59.640  4574  4574 V BluetoothAdapterState: isTurningOn()=false
09-26 06:54:59.640  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:54:59.640  4574  4574 V BluetoothAdapterState: isBleTurningOff()=true
09-26 06:54:59.641  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-26 06:54:59.641  4574  4657 D BluetoothAdapterProperties: Setting state to 10
09-26 06:54:59.641  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-26 06:54:59.641  4574  4657 I BluetoothAdapterState: Entering OffState
09-26 06:54:59.642   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-26 06:54:59.643  3731  3731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-26 06:54:59.650  4574  4574 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-26 06:54:59.651  4574  4574 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 06:54:59.651  4574  4574 I BluetoothServiceJni: cleanupNative: return from cleanup
09-26 06:54:59.652  4574  4658 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-26 06:54:59.661  3731  3731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-26 06:54:59.664  4574  4658 D bt_stack_manager: event_clean_up_stack finished.
,09-26 06:54:59.674  3731  5386 I iu.UploadsManager: num queued entries: 0
,09-26 06:54:59.674  3731  5386 I iu.UploadsManager: num updated entries: 0
09-26 06:54:59.675  3731  5386 I iu.SyncManager: NEXT; no task
,09-26 06:54:59.676  4574  4574 I art     : System.exit called, status: 0
09-26 06:54:59.676  4574  4574 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-26 06:54:59.691  3731  3731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 06:54:59.692  3731  3731 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 06:54:59.695  3731  5734 I SystemUpdateService: active receiver: enabled
,09-26 06:54:59.703  3731  5734 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 06:54:59.706   933  5533 I ActivityManager: Start proc 5737:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-26 06:54:59.715   933  3116 I ActivityManager: Process com.android.bluetooth (pid 4574) has died
,09-26 06:54:59.734  3731  5734 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-26 06:54:59.734  3731  5734 I SystemUpdateService: now status is 0 (complete)
09-26 06:54:59.734  3731  5734 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 06:54:59.734  3731  5734 I SystemUpdateService: file has been verified
09-26 06:54:59.734  3731  5734 I SystemUpdateService: OTA package size = 21989297
,09-26 06:54:59.745  5737  5737 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-26 06:54:59.745   933   950 D Tethering: InitialState.processMessage what=4
,09-26 06:54:59.747   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 06:54:59.748  5737  5737 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 06:54:59.762  5737  5737 D SprintDMHelper: simOperator: 
,09-26 06:54:59.762  5737  5737 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 06:54:59.764  3731  5734 I SystemUpdateService: showing system update notification
,09-26 06:54:59.775   933   943 I ActivityManager: Start proc 5749:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-26 06:54:59.838  3731  3731 D SystemUpdateService: onDestroy
,09-26 06:54:59.840   933   943 I ActivityManager: Killing 5437:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-26 06:54:59.877  4992  5763 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 06:54:59.889   933  3845 I ActivityManager: Start proc 5764:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-26 06:54:59.892   933  5533 I ActivityManager: Killing 5256:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-26 06:54:59.955  5764  5764 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-26 06:54:59.976   933  3397 I ActivityManager: Killing 4673:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-26 06:55:00.065  5694  5721 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-26 06:55:00.077   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32c15df:true
,09-26 06:55:00.428   506   927 E Netd    : netlink response contains error (No such file or directory)
,09-26 06:55:00.430   933  2963 E NetdConnector: NDC Command {113 network destroy 100} took too long (1096ms)
,09-26 06:55:00.431   933  2963 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-26 06:55:00.431   933  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-26 06:55:00.432   933  2959 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1090ms)
,09-26 06:55:00.432   933  2958 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (684ms)
,09-26 06:55:00.432   506   927 D TetherController: Setting IP forward enable = 0
,09-26 06:55:04.198   933   944 D WifiService: setWifiEnabled: true pid=5621, uid=10077
,09-26 06:55:04.198   933   944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 06:55:04.205   506   927 D SoftapController: Softap fwReload - Ok
,09-26 06:55:04.211   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:04.212   506   927 D CommandListener: Trying to bring down wlan0
09-26 06:55:04.214   506   927 D CommandListener: Clearing all IP addresses on wlan0
,09-26 06:55:04.221   933  2961 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 06:55:04.793   933  2961 D wifi    : set interface wlan0 flags (UP)
09-26 06:55:04.793   933  2961 I WifiHAL : Initializing wifi
,09-26 06:55:04.793   933  2961 I WifiHAL : Creating socket
,09-26 06:55:04.797   933  2961 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 06:55:04.797   933  2961 D wifi    : Did set static halHandle = 0x7f905c8680
09-26 06:55:04.797   933  2961 D wifi    : halHandle = 0x7f905c8680, mVM = 0x7facc0d140, mCls = 0x1996
,09-26 06:55:04.797   933  2961 D wifi    : array field set
,09-26 06:55:04.797   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-26 06:55:04.798   933  2961 I WifiNative-HAL: interface[0] = wlan0
09-26 06:55:04.801   933  5785 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547882829440
09-26 06:55:04.801   933  5785 D wifi    : waitForHalEvents called, vm = 0x7facc0d140, obj = 0x1996, env = 0x7f8d6e3980
,09-26 06:55:04.871  5786  5786 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 06:55:04.885  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 06:55:04.902   933  2961 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 06:55:04.905  5786  5786 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 06:55:04.905  5786  5786 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
09-26 06:55:04.905  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:04.906  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:04.907  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:04.919   933  2961 D WifiConfigStore: Loading config and enabling all networks 
,09-26 06:55:04.921  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:04.921  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:04.921  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:04.921  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:04.922  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:04.922  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:04.922  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:55:04.922  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:04.924  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:04.924  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:04.924  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:55:04.924  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:04.930   933  2961 D WifiConfigStore: loaded 0 passpoint configs
,09-26 06:55:04.930   933  2961 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 06:55:04.931   933  2961 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 06:55:04.931   933  2961 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 06:55:04.933   933  2961 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-26 06:55:04.933   933  2961 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-26 06:55:04.933   933  2961 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 06:55:04.933   933  2961 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 06:55:04.936   933  2961 D WifiNative-HAL: Setting external_sim to 1
09-26 06:55:04.936  4992  4992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 06:55:04.936   933  2961 D wifi    : setting dfs flag to true, 0x7f93efe900
,09-26 06:55:04.937   933  2961 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 06:55:04.937   933  2961 D wifi    : setting scan oui 0x7f93efe900
09-26 06:55:04.937   933  2961 D WifiHAL : Sending mac address OUI
,09-26 06:55:04.941   933  2961 E native  : do suspend false
,09-26 06:55:04.949   933  2961 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-26 06:55:04.949   933   933 D RttService: SCAN_AVAILABLE : 3
09-26 06:55:04.949   933  3070 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-26 06:55:04.949   506   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-26 06:55:04.950   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:04.955   933  2960 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-26 06:55:04.955   933  2960 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 06:55:04.964   933  2960 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 06:55:04.969   933  2960 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 06:55:04.969   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267943 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-26 06:55:08.124  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:08.131  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:08.137  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:08.143  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:08.204   933  2961 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 06:55:08.205   933  2961 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-26 06:55:08.205   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:55:08.216   933  2961 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 06:55:08.249   933  2961 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 06:55:08.251  5786  5786 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 06:55:08.673  5786  5786 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 06:55:08.714  5786  5786 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 06:55:08.716  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 06:55:08.727   933  2961 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 06:55:08.728   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-26 06:55:08.728   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 06:55:08.746   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:55:08.758   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:08.765   933  2961 D WifiStateMachine: Start Dhcp Watchdog 2
,09-26 06:55:08.771   933  5792 D DhcpClient: Receive thread started
,09-26 06:55:08.776   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 06:55:08.776   933  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-26 06:55:08.776   933  2963 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-26 06:55:08.859   933  2961 E native  : do suspend false
,09-26 06:55:08.873   933  5791 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 06:55:08.886   933  5792 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-26 06:55:08.887   933  5791 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-26 06:55:08.889   933  5791 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 06:55:08.905   933  5792 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 06:55:08.906   933  5791 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-26 06:55:08.908   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:08.912   933  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 06:55:08.915   933  5791 D DhcpClient: Scheduling renewal in 86399s
,09-26 06:55:08.924   933  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 06:55:08.924   933  2961 D WifiConfigStore: No blacklist allowed without epno enabled
09-26 06:55:08.925   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 06:55:08.932   933  2963 D ConnectivityService: Adding iface wlan0 to network 101
,09-26 06:55:08.936   933  2961 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 06:55:08.977   933  2963 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-26 06:55:08.977   933  2963 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-26 06:55:08.979   933  2963 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-26 06:55:08.981   933  2963 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-26 06:55:08.982   933  2963 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-26 06:55:08.991   933  2963 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 06:55:08.995   933  2963 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-26 06:55:08.996   933  2963 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-26 06:55:08.996   933  2963 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-26 06:55:08.996   933  2961 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 06:55:08.996   933  2963 D ConnectivityService:    accepting network in place of null
09-26 06:55:08.996   933  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 06:55:08.996   933  2963 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 06:55:09.006   933  5790 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271980, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 06:55:09.019   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:55:09.042   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:55:09.045   933  2963 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-26 06:55:09.045   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-26 06:55:09.045  3759  3899 W QCNEJ   : |CORE| network available: 101
,09-26 06:55:09.047   933  2963 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-26 06:55:09.047  3759  3899 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-26 06:55:09.050  3759  3899 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-26 06:55:09.051  3759  3899 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-26 06:55:09.051   933   950 D Tethering: MasterInitialState.processMessage what=3
,09-26 06:55:09.053  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:09.053  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:55:09.053  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.053  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:09.055  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:09.055  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:55:09.055  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.055  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:55:09.058  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:09.058  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 06:55:09.059  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.059  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:55:09.061  5018  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-26 06:55:09.062  5018  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 06:55:09.062  5018  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 06:55:09.062  5018  5042 E SarControlService: no key has been found,reset the power
09-26 06:55:09.062  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 06:55:09.062  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 06:55:09.062  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 06:55:09.063  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 06:55:09.063  5043  5043 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-26 06:55:09.064  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-26 06:55:09.064  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 06:55:09.065  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 06:55:09.065  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 06:55:09.065  5043  5043 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 06:55:09.069  3911  3911 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-26 06:55:09.071  3731  3731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 06:55:09.072  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000ec03000000000000ffffffff]
09-26 06:55:09.072  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:55:09.072  5043  5057 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-26 06:55:09.075  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-26 06:55:09.075   933  5789 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-26 06:55:09.075  5018  5028 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 06:55:09.076  3731  3731 D SystemUpdateService: onCreate
09-26 06:55:09.080  3731  3731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 06:55:09.084  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000ed03000000000000ffffffff]
09-26 06:55:09.084  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:55:09.084  5043  5057 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-26 06:55:09.084  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 06:55:09.085  5018  5029 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-26 06:55:09.090  3731  3731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-26 06:55:09.098  3731  5386 I iu.UploadsManager: num queued entries: 0
,09-26 06:55:09.098  3731  5386 I iu.UploadsManager: num updated entries: 0
09-26 06:55:09.099  3731  5386 I iu.SyncManager: NEXT; no task
,09-26 06:55:09.101  3731  5804 I SystemUpdateService: active receiver: enabled
,09-26 06:55:09.104  3731  3731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 06:55:09.106  3731  3731 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 06:55:09.108  5737  5737 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 06:55:09.112  5737  5737 D SprintDMHelper: simOperator: 
09-26 06:55:09.112  5737  5737 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 06:55:09.124   933  5789 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 10:55:09 GMT], X-Android-Received-Millis=[1474887309123], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474887309097]}
,09-26 06:55:09.125   933  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-26 06:55:09.125   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-26 06:55:09.126   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 06:55:09.127   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 06:55:09.135  3731  5804 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 06:55:09.149  3731  5804 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-26 06:55:09.149  3731  5804 I SystemUpdateService: now status is 0 (complete)
09-26 06:55:09.149  3731  5804 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 06:55:09.150  3731  5804 I SystemUpdateService: file has been verified
09-26 06:55:09.150  3731  5804 I SystemUpdateService: OTA package size = 21989297
,09-26 06:55:09.155  3731  5804 I SystemUpdateService: showing system update notification
,09-26 06:55:09.167  3731  3731 D SystemUpdateService: onDestroy
,09-26 06:55:09.202   933  3847 D WifiService: setWifiEnabled: false pid=5621, uid=10077
09-26 06:55:09.202   933  3847 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 06:55:09.204   933  2961 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-26 06:55:09.204   933  2961 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 06:55:09.204   933  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 06:55:09.205   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:55:09.213   933  5791 D DhcpClient: Clearing IP address
,09-26 06:55:09.214   506   927 D CommandListener: Clearing all IP addresses on wlan0
,09-26 06:55:09.218  3570  5805 V NativeCrypto: SSL handshake aborted: ssl=0x7fab41b100: I/O error during system call, Connection timed out
,09-26 06:55:09.223   933  5533 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-26 06:55:09.223   933  5789 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-26 06:55:09.223   933  5789 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-26 06:55:09.224  4992  5809 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-26 06:55:09.226   506   927 D CommandListener: Setting iface cfg
09-26 06:55:09.227   933  5792 D DhcpClient: Receive thread stopped
09-26 06:55:09.229   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-26 06:55:09.229   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-26 06:55:09.233   534   534 E Parcel  : Reading a NULL string not supported here.
09-26 06:55:09.235   933  5789 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-26 06:55:09.237   933  2963 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-26 06:55:09.238   933   933 D RttService: SCAN_AVAILABLE : 1
09-26 06:55:09.239  3759  3899 W QCNEJ   : |CORE| network lost: 101
09-26 06:55:09.239   933  3070 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-26 06:55:09.239  3759  3899 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-26 06:55:09.241   933  2961 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-26 06:55:09.244   933  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
09-26 06:55:09.252  ,4992  5809 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
09-26 06:55:09.252  4992  5809 W Babel_NetworkConnectionCheckingService: 	... 21 more
09-26 06:55:09.252  4992  5809 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-26 06:55:09.261   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:55:09.280   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:55:09.280   506   927 D CommandListener: Clearing all IP addresses on wlan0
09-26 06:55:09.281   933  2963 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-26 06:55:09.281   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-26 06:55:09.284  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:09.284  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:09.284  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.285  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:09.285   933   950 D Tethering: MasterInitialState.processMessage what=3
09-26 06:55:09.286   933  2961 D DhcpClient: doQuit
09-26 06:55:09.286   933  2961 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 06:55:09.286   933  5791 D DhcpClient: onQuitting
09-26 06:55:09.286  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:09.286  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:09.286  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.286  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:09.288  5786  5786 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 06:55:09.288  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:09.288  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:09.288  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.288  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:09.293  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:09.293  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:09.293  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.293  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:09.294  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:09.294  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:09.294  3911  3911 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-26 06:55:09.294  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.294  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:09.295  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:09.295  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:09.295  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:09.295  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:09.296  3731  3731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 06:55:09.298  5018  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-26 06:55:09.299  5018  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 06:55:09.299  5018  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-26 06:55:09.299  5018  5042 E SarControlService: no key has been found,reset the power
09-26 06:55:09.299  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 06:55:09.299  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-26 06:55:09.299  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 06:55:09.300  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 06:55:09.300  5043  5043 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 06:55:09.301  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 06:55:09.301  5786  5786 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-26 06:55:09.301  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 06:55:09.301  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 06:55:09.302  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-26 06:55:09.302  5043  5043 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 06:55:09.304  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-26 06:55:09.304  3731  3731 D SystemUpdateService: onCreate
09-26 06:55:09.306  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000ee03000000000000ffffffff]
09-26 06:55:09.306  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:55:09.306  5043  5057 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-26 06:55:09.307  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 06:55:09.307  5018  5029 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-26 06:55:09.310  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000ef03000000000000ffffffff]
09-26 06:55:09.310  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:55:09.310  5043  5057 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-26 06:55:09.311  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 06:55:09.311  5018  5028 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 06:55:09.312  3731  3731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 06:55:09.317  3731  5824 I SystemUpdateService: active receiver: enabled
,09-26 06:55:09.319  3731  3731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-26 06:55:09.325  3731  5386 I iu.UploadsManager: num queued entries: 0
,09-26 06:55:09.325  3731  5386 I iu.UploadsManager: num updated entries: 0
09-26 06:55:09.326  3731  5386 I iu.SyncManager: NEXT; no task
,09-26 06:55:09.328  3731  3731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 06:55:09.329  3731  3731 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 06:55:09.332  5737  5737 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 06:55:09.335  5737  5737 D SprintDMHelper: simOperator: 
09-26 06:55:09.335  5737  5737 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 06:55:09.337   506   927 E Netd    : netlink response contains error (No such file or directory)
,09-26 06:55:09.338   933  2963 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-26 06:55:09.338   933  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-26 06:55:09.347  4992  5827 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 06:55:09.345  3731  5824 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 06:55:09.351  5786  5786 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-26 06:55:09.352  3731  5824 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-26 06:55:09.352  3731  5824 I SystemUpdateService: now status is 0 (complete)
09-26 06:55:09.352  3731  5824 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 06:55:09.352  3731  5824 I SystemUpdateService: file has been verified
09-26 06:55:09.352  3731  5824 I SystemUpdateService: OTA package size = 21989297
,09-26 06:55:09.368  3731  5824 I SystemUpdateService: showing system update notification
,09-26 06:55:09.369  5786  5786 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 06:55:09.373  4992  4992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 06:55:09.374   933  2961 D wifi    : In wifi stop Hal
09-26 06:55:09.374   933  2961 D wifi    : halHandle = 0x7f905c8680, mVM = 0x7facc0d140, mCls = 0x1996
09-26 06:55:09.374   933  5785 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 06:55:09.374   933  5785 D WifiHAL : Got a signal to exit!!!
,09-26 06:55:09.374   933  5785 I WifiHAL : Exit wifi_event_loop
,09-26 06:55:09.376  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:09.376   933  2961 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 06:55:09.376   933  2961 E WifiHAL : Event processing terminated
09-26 06:55:09.376   933  2961 D wifi    : In wifi cleaned up handler
09-26 06:55:09.376   933  2961 I WifiHAL : Internal cleanup completed
,09-26 06:55:09.377  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:09.378  4090  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 06:55:09.378  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:09.382  3731  3731 D SystemUpdateService: onDestroy
,09-26 06:55:09.395   933  5785 D wifi    : set interface wlan0 flags (DOWN)
,09-26 06:55:09.395   933  2961 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 06:55:09.601   933   950 D Tethering: InitialState.processMessage what=4
,09-26 06:55:09.607   933   950 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 06:55:10.046   933  2963 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-26 06:55:11.622   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:12.623   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:13.624   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:14.245   933   950 I ActivityManager: Start proc 5829:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 06:55:14.351  5829  5829 D AdapterServiceConfig: Adding HeadsetService
09-26 06:55:14.352  5829  5829 D AdapterServiceConfig: Adding A2dpService
,09-26 06:55:14.352  5829  5829 D AdapterServiceConfig: Adding HidService
09-26 06:55:14.352  5829  5829 D AdapterServiceConfig: Adding HealthService
09-26 06:55:14.352  5829  5829 D AdapterServiceConfig: Adding PanService
09-26 06:55:14.352  5829  5829 D AdapterServiceConfig: Adding GattService
09-26 06:55:14.352  5829  5829 D AdapterServiceConfig: Adding BluetoothMapService
09-26 06:55:14.353  5829  5829 D AdapterServiceConfig: Adding SapService
,09-26 06:55:14.367   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48f17a2:true
,09-26 06:55:14.367  5829  5829 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 06:55:14.371  5829  5829 I bt_bluedroid: init
,09-26 06:55:14.371  5829  5841 I BluetoothAdapterState: Entering OffState
,09-26 06:55:14.374  5829  5842 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 06:55:14.374  5829  5842 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 06:55:14.374  5829  5842 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-26 06:55:14.374  5829  5842 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-26 06:55:14.375  5829  5829 I bt_bluedroid: get_profile_interface socket
,09-26 06:55:14.379  5829  5845 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-26 06:55:14.379  5829  5829 I bt_bluedroid: get_profile_interface sdp
,09-26 06:55:14.381  5829  5845 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 06:55:14.385  5829  5840 I bt_bluedroid: config_hci_snoop_log
,09-26 06:55:14.386   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 06:55:14.391  5829  5841 D BluetoothAdapterState: Current state: OFF, message: 0
09-26 06:55:14.391  5829  5841 D BluetoothAdapterProperties: Setting state to 14
09-26 06:55:14.391  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-26 06:55:14.393  5829  5841 D BluetoothBondStateMachine: make
,09-26 06:55:14.395  5829  5846 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 06:55:14.397  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,09-26 06:55:14.398  5829  5829 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 06:55:14.401  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:14.402  5829  5829 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 06:55:14.402  5829  5829 D BtGatt.GattService: Received start request. Starting profile...
09-26 06:55:14.402  5829  5829 D BtGatt.GattService: start()
09-26 06:55:14.402  5829  5829 I bt_bluedroid: get_profile_interface gatt
,09-26 06:55:14.404  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:14.404  5829  5829 D BtGatt.AdvertiseManager: advertise manager created
,09-26 06:55:14.409  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,09-26 06:55:14.409  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:14.409  5829  5829 V BluetoothAdapterState: isBleTurningOn()=true
09-26 06:55:14.409  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:14.410  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 06:55:14.411  5829  5841 I bt_bluedroid: bt_bluedroid
09-26 06:55:14.411  5829  5842 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-26 06:55:14.412  5829  5842 I bt_hci  : start_up
,09-26 06:55:14.419  5829  5842 I bt_vendor: alloc value 0xf3d6b871
,09-26 06:55:14.419  5829  5842 I bt_vendor: init
09-26 06:55:14.419  5829  5842 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 06:55:14.419  5829  5842 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 06:55:14.530  5829  5842 D bt_hci  : start_up starting async portion
09-26 06:55:14.530  5829  5849 I bt_hci  : event_finish_startup
09-26 06:55:14.530  5829  5849 I bt_hci_h4: hal_open
09-26 06:55:14.531  5829  5849 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-26 06:55:14.533  5829  5849 I bt_userial_vendor: device fd = 54 open
,09-26 06:55:14.528  5850  5850 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 06:55:14.547  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 06:55:14.550  5829  5849 D bt_hwcfg: Chipset BCM4358A3
,09-26 06:55:14.550  5829  5849 D bt_hwcfg: Target name = [BCM4358A3]
09-26 06:55:14.551  5829  5849 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 06:55:14.625   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:14.957  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-26 06:55:14.958  5829  5849 D bt_hwcfg: Settlement delay -- 100 ms
,09-26 06:55:14.958  5829  5849 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 06:55:15.094  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 06:55:15.095  5829  5849 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-26 06:55:15.096  5829  5849 I bt_hwcfg: vendor lib fwcfg completed
09-26 06:55:15.096  5829  5849 I bt_vendor: firmware callback
,09-26 06:55:15.097  5829  5849 I bt_hci  : firmware_config_callback
,09-26 06:55:15.106  5829  5852 I bt_btu  : btu_task pending for preload complete event
,09-26 06:55:15.107  5829  5852 I bt_btu_task: Bluetooth chip preload is complete
,09-26 06:55:15.107  5829  5852 I bt_btu  : btu_task received preload complete event
,09-26 06:55:15.113  5829  5852 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 06:55:15.113  5829  5852 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 06:55:15.113  5829  5852 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-26 06:55:15.113  5829  5852 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-26 06:55:15.113  5829  5852 I         : BTE_InitTraceLevels -- TRC_AVRC
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_A2D
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_GAP
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_SDP
,09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_SMP
09-26 06:55:15.114  5829  5852 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 06:55:15.115  5829  5852 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 06:55:15.196  5829  5852 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ce9549
,09-26 06:55:15.197  5829  5852 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ce9549 
,09-26 06:55:15.218  5829  5845 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 06:55:15.219  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-26 06:55:15.220  5829  5845 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 06:55:15.223  5829  5845 D BluetoothAdapterProperties: Name is: Nexus 6P
09-26 06:55:15.225  5829  5845 D BluetoothAdapterProperties: Scan Mode:20
09-26 06:55:15.226  5829  5845 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 06:55:15.226  5829  5845 D bt_hci  : do_postload posting postload work item
,09-26 06:55:15.226  5829  5849 I bt_hci  : event_postload
,09-26 06:55:15.226  5829  5849 I bt_vendor: sco_config_cb
09-26 06:55:15.226  5829  5849 I bt_hci  : sco_config_callback postload finished.
,09-26 06:55:15.230  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:15.234  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:15.237  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:15.237  5829  5849 I bt_vendor: low_power_mode_cb
09-26 06:55:15.238  5829  5845 D bt_bte_conf: Device ID record 1 : primary
09-26 06:55:15.238  5829  5845 D bt_bte_conf:   vendorId            = 000f
09-26 06:55:15.238  5829  5845 D bt_bte_conf:   vendorIdSource      = 0001
,09-26 06:55:15.238  5829  5845 D bt_bte_conf:   product             = 1200
09-26 06:55:15.238  5829  5845 D bt_bte_conf:   version             = 1436
09-26 06:55:15.238  5829  5845 D bt_bte_conf:   clientExecutableURL = 
09-26 06:55:15.238  5829  5845 D bt_bte_conf:   serviceDescription  = 
,09-26 06:55:15.239  5829  5845 D bt_bte_conf:   documentationURL    = 
09-26 06:55:15.239  5829  5845 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 06:55:15.239  5829  5842 D bt_stack_manager: event_start_up_stack finished
09-26 06:55:15.240  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 06:55:15.240  5829  5841 D BluetoothAdapterProperties: Setting state to 15
09-26 06:55:15.240  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-26 06:55:15.241  5829  5841 I BluetoothAdapterState: Entering BleOnState
,09-26 06:55:15.244  5829  5841 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-26 06:55:15.245  5829  5841 D BluetoothAdapterProperties: Setting state to 11
09-26 06:55:15.245  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-26 06:55:15.249  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:15.250  5829  5829 D HeadsetService: Received start request. Starting profile...
,09-26 06:55:15.254  5829  5829 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 06:55:15.254  5829  5829 D HeadsetStateMachine: make
,09-26 06:55:15.257  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:15.260  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:15.262  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:15.267  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,09-26 06:55:15.271  5829  5829 D HeadsetStateMachine: max_hf_connections = 1
,09-26 06:55:15.271  5829  5829 I bt_bluedroid: get_profile_interface handsfree
09-26 06:55:15.271  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 06:55:15.272  5829  5845 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-26 06:55:15.274  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:15.275  5829  5829 D A2dpService: Received start request. Starting profile...
09-26 06:55:15.276  5829  5829 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-26 06:55:15.276  5829  5829 I bt_bluedroid: get_profile_interface avrcp
,09-26 06:55:15.282  5829  5829 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-26 06:55:15.282  5829  5829 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-26 06:55:15.282  5829  5829 D A2dpStateMachine: make
09-26 06:55:15.283  5829  5829 I bt_bluedroid: get_profile_interface a2dp
,09-26 06:55:15.284  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-26 06:55:15.285  5829  5860 D A2dpStateMachine: Enter Disconnected: -2
,09-26 06:55:15.286  5829  5829 I BluetoothHidServiceJni: classInitNative: succeeds
09-26 06:55:15.287  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:15.288  5829  5829 D HidService: Received start request. Starting profile...
,09-26 06:55:15.289  5829  5829 I bt_bluedroid: get_profile_interface hidhost
09-26 06:55:15.289  5829  5829 D HidService: setHidService(): set to: null
09-26 06:55:15.289  5829  5845 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cca56d
09-26 06:55:15.289  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 06:55:15.291  5674  5674 D BluetoothInputDevice: Proxy object connected
09-26 06:55:15.291  5674  5674 D HidProfile: Bluetooth service connected
09-26 06:55:15.292  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 06:55:15.292  5829  5829 I BluetoothHealthServiceJni: classInitNative: succeeds
09-26 06:55:15.293  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:15.294  5829  5829 D HealthService: Received start request. Starting profile...
,09-26 06:55:15.295  5829  5829 I bt_bluedroid: get_profile_interface health
09-26 06:55:15.296  5829  5829 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-26 06:55:15.297  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:15.298  5829  5829 D PanService: Received start request. Starting profile...
,09-26 06:55:15.299  5829  5829 D BluetoothPanServiceJni: initializeNative(L110): pan
09-26 06:55:15.299  5829  5829 I bt_bluedroid: get_profile_interface pan
09-26 06:55:15.299  5829  5845 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 06:55:15.301  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:15.302  5674  5674 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 06:55:15.302  5829  5829 D BluetoothMapService: Received start request. Starting profile...
09-26 06:55:15.302  5829  5829 D BluetoothMapService: start()
09-26 06:55:15.302  5674  5674 D PanProfile: Bluetooth service connected
,09-26 06:55:15.303  5674  5674 D BluetoothMap: Proxy object connected
09-26 06:55:15.303  5674  5674 D MapProfile: Bluetooth service connected
09-26 06:55:15.303  5674  5674 D BluetoothMap: getConnectedDevices()
,09-26 06:55:15.305  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-26 06:55:15.306  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 06:55:15.307  5829  5829 D BluetoothMapAppObserver: createReceiver()
09-26 06:55:15.308  5829  5829 D BluetoothMapAppObserver: initObservers()
09-26 06:55:15.308  5829  5829 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 06:55:15.315  5829  5829 V SapService: SapBinder()
09-26 06:55:15.315  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:15.316  5674  5674 D BluetoothMap: Bluetooth is Not enabled
,09-26 06:55:15.317  5829  5829 D SapService: Received start request. Starting profile...
09-26 06:55:15.317  5829  5829 V SapService: start()
,09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:15.320  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:15.321  5829  5858 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.321  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:15.322  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:15.322  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.322  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.322  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:15.322  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 06:55:15.323  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:15.323  5829  5829 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:15.323  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:15.323  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:15.323  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 06:55:15.323  5829  5841 D BluetoothAdapterProperties: ScanMode =  20
09-26 06:55:15.323  5829  5841 D BluetoothAdapterProperties: State =  11
09-26 06:55:15.324  5829  5841 D BluetoothAdapterProperties: Setting state to 12
09-26 06:55:15.324  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 06:55:15.324  5829  5841 I BluetoothAdapterState: Entering OnState
09-26 06:55:15.324  3119  3968 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 06:55:15.326   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 06:55:15.326  3119  3119 D BluetoothInputDevice: Proxy object connected
09-26 06:55:15.326  3119  3119 D HidProfile: Bluetooth service connected
09-26 06:55:15.327  5674  5686 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-26 06:55:15.327  3794  3820 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:15.328   933   933 D BluetoothA2dp: Proxy object connected
09-26 06:55:15.328  5674  5685 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 06:55:15.328  5829  5845 D BluetoothAdapterProperties: Scan Mode:21
,09-26 06:55:15.329  5829  5845 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 06:55:15.329   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:15.330  3119  3137 D BluetoothPbap: onBluetoothStateChange: up=true
,09-26 06:55:15.332  3119  3130 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 06:55:15.333   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 06:55:15.333  5674  5686 D BluetoothPan: onBluetoothStateChange on: true
,09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:15.333  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:15.333  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 06:55:15.334  3119  3968 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 06:55:15.334  5829  5829 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 06:55:15.336  5674  5685 D BluetoothMap: onBluetoothStateChange: up=true
09-26 06:55:15.336  3119  3119 D BluetoothA2dp: Proxy object connected
09-26 06:55:15.336  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:15.336  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:55:15.336   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:15.337  3119  3137 D BluetoothMap: onBluetoothStateChange: up=true
09-26 06:55:15.338  3119  3968 D BluetoothPan: onBluetoothStateChange on: true
09-26 06:55:15.338  3119  3119 D BluetoothMap: Proxy object connected
09-26 06:55:15.338  3119  3119 D MapProfile: Bluetooth service connected
09-26 06:55:15.338  3119  3119 D BluetoothMap: getConnectedDevices()
,09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:15.340  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:15.340  3119  3119 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 06:55:15.340  3119  3119 D PanProfile: Bluetooth service connected
,09-26 06:55:15.342  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:15.342   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
,09-26 06:55:15.345  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 06:55:15.345  5674  5674 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:15.347  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:15.348  5829  5829 D ObexServerSockets: Succeed to create listening sockets 
09-26 06:55:15.348  5829  5829 D ObexServerSockets0: startAccept()
09-26 06:55:15.348  5829  5829 D ObexServerSockets0: prepareForNewConnect()
,09-26 06:55:15.350  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:15.351  5829  5829 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-26 06:55:15.351  5829  5829 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 06:55:15.351  5829  5829 D BluetoothMapService: onReceive
09-26 06:55:15.351  5829  5867 D ObexServerSockets0: Accepting socket connection...
09-26 06:55:15.351  5829  5829 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 06:55:15.351  5829  5829 D BluetoothMapService: STATE_ON
09-26 06:55:15.352  5829  5868 D ObexServerSockets0: Accepting socket connection...
09-26 06:55:15.352  5674  5674 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-26 06:55:15.352  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:15.353  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:15.354  5829  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:55:15.355  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:15.355  5829  5869 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 06:55:15.355  5829  5869 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-26 06:55:15.360  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 06:55:15.362  5674  5674 D BluetoothA2dp: Proxy object connected
,09-26 06:55:15.365  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 06:55:15.372  3119  3119 D BluetoothPbap: Proxy object connected
,09-26 06:55:15.372  3119  3119 D PbapServerProfile: Bluetooth service connected
,09-26 06:55:15.372  5674  5674 D DockEventReceiver: finishStartingService: stopping service
09-26 06:55:15.373  5674  5674 D BluetoothPbap: Proxy object connected
09-26 06:55:15.374  5674  5674 D PbapServerProfile: Bluetooth service connected
,09-26 06:55:15.378  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-26 06:55:15.378  5829  5829 D ObexServerSockets0: prepareForNewConnect()
09-26 06:55:15.378  5829  5873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 06:55:15.394  5829  5877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 06:55:15.395  5829  5877 I BtOppRfcommListener: Accept thread started.
,09-26 06:55:15.429   933   933 D BluetoothHeadset: Proxy object connected
,09-26 06:55:15.429  3119  3137 D BluetoothHeadset: Proxy object connected
09-26 06:55:15.429   933   950 D BluetoothHeadset: Proxy object connected
09-26 06:55:15.430  3119  3119 D HeadsetProfile: Bluetooth service connected
09-26 06:55:15.430   933   933 D BluetoothHeadset: Proxy object connected
09-26 06:55:15.430  3794  4021 D BluetoothHeadset: Proxy object connected
,09-26 06:55:15.430   933   933 D BluetoothHeadset: Proxy object connected
,09-26 06:55:15.433  3119  3130 D BluetoothHeadset: Proxy object connected
09-26 06:55:15.433  3119  3119 D HeadsetProfile: Bluetooth service connected
,09-26 06:55:15.433   933   950 D BluetoothHeadset: Proxy object connected
,09-26 06:55:15.436   933   950 D BluetoothHeadset: Proxy object connected
,09-26 06:55:15.455  5674  5685 D BluetoothHeadset: Proxy object connected
,09-26 06:55:15.456  5674  5674 D HeadsetProfile: Bluetooth service connected
,09-26 06:55:15.626   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:16.627   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 06:55:17.003   933  2963 D ConnectivityService: handlePromptUnvalidated 101
,09-26 06:55:19.216  5829  5841 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 06:55:19.216  5829  5841 D BluetoothAdapterProperties: Setting state to 13
09-26 06:55:19.216  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-26 06:55:19.217  5829  5841 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 06:55:19.219  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,09-26 06:55:19.229  5829  5829 D BluetoothMapService: onReceive
,09-26 06:55:19.229  5829  5829 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 06:55:19.229  5829  5829 D BluetoothMapService: STATE_TURNING_OFF
09-26 06:55:19.229  5829  5829 D BluetoothMapService: MAP Service closeService in
09-26 06:55:19.230  5829  5829 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 06:55:19.230  5829  5829 D ObexServerSockets0: shutdown(block = true)
,09-26 06:55:19.230  5829  5845 D BluetoothAdapterProperties: Scan Mode:20
09-26 06:55:19.230  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-26 06:55:19.230  5829  5829 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 06:55:19.231  5829  5829 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 06:55:19.231  5829  5854 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-26 06:55:19.231  5829  5868 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-26 06:55:19.231  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 06:55:19.232  5829  5867 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-26 06:55:19.233  5829  5829 I BtOppRfcommListener: stopping Accept Thread
09-26 06:55:19.234  5829  5877 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 06:55:19.234  5829  5877 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-26 06:55:19.238  5829  5829 D HeadsetService: Received stop request...Stopping profile...
09-26 06:55:19.239  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:19.239  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:19.241  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:19.241   933   933 D BluetoothHeadset: Proxy object disconnected
09-26 06:55:19.241  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:19.241  3119  3968 D BluetoothHeadset: Proxy object disconnected
09-26 06:55:19.242  5674  5674 D DockEventReceiver: finishStartingService: stopping service
09-26 06:55:19.242   933   933 D BluetoothHeadset: Proxy object disconnected
09-26 06:55:19.242  3794  4031 D BluetoothHeadset: Proxy object disconnected
09-26 06:55:19.242  5829  5829 D A2dpService: Received stop request...Stopping profile...
09-26 06:55:19.243   933   933 D BluetoothHeadset: Proxy object disconnected
09-26 06:55:19.243  5829  5860 D A2dpStateMachine: Exit Disconnected: -1
09-26 06:55:19.244  5674  5685 D BluetoothHeadset: Proxy object disconnected
09-26 06:55:19.245  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:19.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:19.245   933   933 D BluetoothA2dp: Proxy object disconnected
09-26 06:55:19.245  5674  5674 D HeadsetProfile: Bluetooth service disconnected
,09-26 06:55:19.246  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:19.246  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:19.247  5674  5674 D BluetoothA2dp: Proxy object disconnected
,09-26 06:55:19.249  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:19.249  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:19.250  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 06:55:19.250  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:19.251  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 06:55:19.251  5829  5829 D HidService: Received stop request...Stopping profile...
09-26 06:55:19.252  5829  5829 D HidService: Stopping Bluetooth HidService
09-26 06:55:19.252  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.253  5674  5674 D BluetoothInputDevice: Proxy object disconnected
09-26 06:55:19.253  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.253  5674  5674 D HidProfile: Bluetooth service disconnected
09-26 06:55:19.253  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.253  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 06:55:19.253  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 06:55:19.253  5829  5829 D HealthService: Received stop request...Stopping profile...
09-26 06:55:19.254  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.256  5829  5829 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 06:55:19.256  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.256  5829  5829 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-26 06:55:19.256  5829  5852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:55:19.256  5829  5852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:55:19.256  5829  5852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:55:19.256  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 06:55:19.256  5829  5829 D PanService: Received stop request...Stopping profile...
09-26 06:55:19.256  5829  5845 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-26 06:55:19.258  5829  5829 D BluetoothMapService: Received stop request...Stopping profile...
09-26 06:55:19.258  5829  5829 D BluetoothMapService: stop()
09-26 06:55:19.258  3119  3119 D HeadsetProfile: Bluetooth service disconnected
09-26 06:55:19.258  5829  5829 D BluetoothMapAppObserver: deinitObservers()
09-26 06:55:19.258  3119  3119 D BluetoothA2dp: Proxy object disconnected
09-26 06:55:19.258  5829  5829 D BluetoothMapAppObserver: removeReceiver()
,09-26 06:55:19.258  3119  3119 D BluetoothInputDevice: Proxy object disconnected,
09-26 06:55:19.258  3119  3119 D HidProfile: Bluetooth service disconnected
09-26 06:55:19.259  3119  3119 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 06:55:19.259  3119  3119 D PanProfile: Bluetooth service disconnected
09-26 06:55:19.260  3119  3119 D BluetoothMap: Proxy object disconnected
,09-26 06:55:19.260  3119  3119 D MapProfile: Bluetooth service disconnected
09-26 06:55:19.260  5829  5829 D SapService: Received stop request...Stopping profile...
09-26 06:55:19.260  5829  5829 V SapService: stop()
09-26 06:55:19.261  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.262  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.262  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.262  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:19.263  5829  5852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:55:19.263  5829  5852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-26 06:55:19.263  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-26 06:55:19.263  5829  5852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 06:55:19.264  5829  5852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 06:55:19.264  5829  5852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 06:55:19.264  5829  5852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 06:55:19.264  3119  3119 D BluetoothPbap: Proxy object disconnected
09-26 06:55:19.264  3119  3119 D PbapServerProfile: Bluetooth service disconnected
09-26 06:55:19.264  5674  5674 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 06:55:19.264  5674  5674 D PanProfile: Bluetooth service disconnected
09-26 06:55:19.264  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.264  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.265  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.265  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:19.265  5829  5829 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-26 06:55:19.266  5829  5829 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 06:55:19.266  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 06:55:19.266  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:19.267  5829  5829 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 06:55:19.267  5829  5845 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 06:55:19.267  5829  5829 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.267  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:19.268  5829  5829 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 06:55:19.268  5829  5829 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-26 06:55:19.268  5829  5829 D BluetoothMapService: MAP Service closeService in
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:19.269  5829  5829 D BluetoothMapService: cleanup()
09-26 06:55:19.269  5829  5829 D BluetoothMapService: MAP Service closeService in
09-26 06:55:19.265  5674  5674 D BluetoothMap: Proxy object disconnected
09-26 06:55:19.269  5674  5674 D MapProfile: Bluetooth service disconnected
,09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isTurningOff()=true
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.269  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:19.269  5674  5674 D BluetoothPbap: Proxy object disconnected
09-26 06:55:19.270  5674  5674 D PbapServerProfile: Bluetooth service disconnected
09-26 06:55:19.270  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-26 06:55:19.270  5829  5841 D BluetoothAdapterProperties: Setting state to 15
09-26 06:55:19.270  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 06:55:19.270  5829  5841 I BluetoothAdapterState: Entering BleOnState
09-26 06:55:19.270  3119  3130 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-26 06:55:19.271   933   950 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 06:55:19.272  5674  5685 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-26 06:55:19.272  3794  3832 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:55:19.272  5674  5686 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 06:55:19.273   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:55:19.273  3119  3972 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 06:55:19.274  3119  3137 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-26 06:55:19.274   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:55:19.274  5674  5685 D BluetoothPan: onBluetoothStateChange on: false
09-26 06:55:19.275  3119  3968 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 06:55:19.275  5674  5686 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:55:19.276  5674  5685 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 06:55:19.276  5674  5686 D BluetoothMap: onBluetoothStateChange: up=false
09-26 06:55:19.277   933   950 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 06:55:19.277  3119  3130 D BluetoothMap: onBluetoothStateChange: up=false
09-26 06:55:19.278  3119  3972 D BluetoothPan: onBluetoothStateChange on: false
09-26 06:55:19.279  5829  5841 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-26 06:55:19.279  5829  5841 D BluetoothAdapterProperties: Setting state to 16
09-26 06:55:19.279  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 06:55:19.279  5829  5841 D BluetoothAdapterProperties: onBleDisable
09-26 06:55:19.280  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
09-26 06:55:19.281  5829  5842 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 06:55:19.282  5829  5852 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 06:55:19.282  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.282  5829  5852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 06:55:19.282  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 06:55:19.284  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:19.285  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:19.287  5829  5845 D BluetoothAdapterProperties: Scan Mode:20
09-26 06:55:19.288  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 06:55:19.288  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.289  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.291  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:19.293  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,09-26 06:55:19.490  5829  5845 I bt_hci  : shut_down
,09-26 06:55:19.495  5829  5849 D bt_hwcfg: hw_epilog_process
,09-26 06:55:19.495  5829  5849 I bt_vendor: low_power_mode_cb
,09-26 06:55:19.498  5829  5849 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-26 06:55:19.498  5829  5849 I bt_vendor: epilog_cb
09-26 06:55:19.498  5829  5849 I bt_hci  : epilog_finished_callback
,09-26 06:55:19.500  5829  5845 I bt_hci_h4: hal_close
,09-26 06:55:19.500  5829  5845 I bt_userial_vendor: device fd = 54 close
,09-26 06:55:19.614  5829  5842 D bt_stack_manager: event_shut_down_stack finished.
,09-26 06:55:19.614  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-26 06:55:19.619  5829  5841 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 06:55:19.619  5829  5829 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-26 06:55:19.620  5829  5829 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 06:55:19.620  5829  5829 D BtGatt.GattService: stop()
,09-26 06:55:19.621  5829  5829 D BtGatt.AdvertiseManager: advertise clients cleared
,09-26 06:55:19.625  5829  5829 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:19.625  5829  5829 V BluetoothAdapterState: isTurningOn()=false
09-26 06:55:19.625  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:19.625  5829  5829 V BluetoothAdapterState: isBleTurningOff()=true
09-26 06:55:19.626  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-26 06:55:19.626  5829  5841 D BluetoothAdapterProperties: Setting state to 10
09-26 06:55:19.627  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-26 06:55:19.628  5829  5841 I BluetoothAdapterState: Entering OffState
,09-26 06:55:19.629   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-26 06:55:19.648  5829  5829 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-26 06:55:19.648  5829  5829 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 06:55:19.649  5829  5829 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-26 06:55:19.651  5829  5842 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-26 06:55:19.658  5829  5829 I art     : System.exit called, status: 0
,09-26 06:55:19.658  5829  5829 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-26 06:55:19.687   933  3845 I ActivityManager: Process com.android.bluetooth (pid 5829) has died
,09-26 06:55:24.215  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 06:55:24.215  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:24.221  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:55:24.222  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@552da90 removed from the list
,09-26 06:55:24.222  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:55:24.222  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:24.222  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:24.225  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:55:24.226  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9725b8e added. We now have 4 listener(s)
,09-26 06:55:24.227  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 06:55:24.228  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:55:24.228  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9725b8e removed from the list
,09-26 06:55:24.229  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:55:24.229  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:24.229  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:55:24.231  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:55:24.231  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6a6faf added. We now have 4 listener(s)
09-26 06:55:24.231  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:55:29.241  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:29.274   933   950 I ActivityManager: Start proc 5887:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 06:55:29.357  5887  5887 D AdapterServiceConfig: Adding HeadsetService
,09-26 06:55:29.368  5887  5887 D AdapterServiceConfig: Adding A2dpService
09-26 06:55:29.369  5887  5887 D AdapterServiceConfig: Adding HidService
09-26 06:55:29.369  5887  5887 D AdapterServiceConfig: Adding HealthService
09-26 06:55:29.369  5887  5887 D AdapterServiceConfig: Adding PanService
09-26 06:55:29.369  5887  5887 D AdapterServiceConfig: Adding GattService
,09-26 06:55:29.369  5887  5887 D AdapterServiceConfig: Adding BluetoothMapService
09-26 06:55:29.370  5887  5887 D AdapterServiceConfig: Adding SapService
,09-26 06:55:29.383   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab333f3:true
,09-26 06:55:29.383  5887  5887 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 06:55:29.386  5887  5887 I bt_bluedroid: init
09-26 06:55:29.387  5887  5899 I BluetoothAdapterState: Entering OffState
,09-26 06:55:29.388  5887  5900 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-26 06:55:29.389  5887  5900 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 06:55:29.389  5887  5900 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-26 06:55:29.389  5887  5900 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-26 06:55:29.389  5887  5887 I bt_bluedroid: get_profile_interface socket
,09-26 06:55:29.391  5887  5903 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-26 06:55:29.391  5887  5887 I bt_bluedroid: get_profile_interface sdp
,09-26 06:55:29.395  5887  5903 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 06:55:29.396  5887  5898 I bt_bluedroid: config_hci_snoop_log
,09-26 06:55:29.397   933   950 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 06:55:29.401  5887  5899 D BluetoothAdapterState: Current state: OFF, message: 0
,09-26 06:55:29.402  5887  5899 D BluetoothAdapterProperties: Setting state to 14
09-26 06:55:29.402  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-26 06:55:29.403  5887  5899 D BluetoothBondStateMachine: make
,09-26 06:55:29.405  5887  5904 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 06:55:29.408  5887  5899 I BluetoothAdapterState: Entering PendingCommandState
,09-26 06:55:29.409  5887  5887 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 06:55:29.412  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:29.412  5887  5887 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 06:55:29.413  5887  5887 D BtGatt.GattService: Received start request. Starting profile...
09-26 06:55:29.413  5887  5887 D BtGatt.GattService: start()
09-26 06:55:29.413  5887  5887 I bt_bluedroid: get_profile_interface gatt
09-26 06:55:29.414  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:29.414  5887  5887 D BtGatt.AdvertiseManager: advertise manager created
,09-26 06:55:29.419  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:29.419  5887  5887 V BluetoothAdapterState: isTurningOn()=false
,09-26 06:55:29.419  5887  5887 V BluetoothAdapterState: isBleTurningOn()=true
09-26 06:55:29.419  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 06:55:29.420  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-26 06:55:29.421  5887  5899 I bt_bluedroid: bt_bluedroid
,09-26 06:55:29.422  5887  5900 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-26 06:55:29.422  5887  5900 I bt_hci  : start_up
,09-26 06:55:29.427  5887  5900 I bt_vendor: alloc value 0xf3d6b871
,09-26 06:55:29.427  5887  5900 I bt_vendor: init
09-26 06:55:29.427  5887  5900 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 06:55:29.427  5887  5900 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 06:55:29.537  5887  5900 D bt_hci  : start_up starting async portion
,09-26 06:55:29.538  5887  5907 I bt_hci  : event_finish_startup
,09-26 06:55:29.538  5887  5907 I bt_hci_h4: hal_open
09-26 06:55:29.538  5887  5907 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-26 06:55:29.535  5908  5908 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-26 06:55:29.541  5887  5907 I bt_userial_vendor: device fd = 54 open
,09-26 06:55:29.555  5887  5907 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 06:55:29.559  5887  5907 D bt_hwcfg: Chipset BCM4358A3
,09-26 06:55:29.559  5887  5907 D bt_hwcfg: Target name = [BCM4358A3]
09-26 06:55:29.559  5887  5907 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 06:55:30.071  5887  5907 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-26 06:55:30.071  5887  5907 D bt_hwcfg: Settlement delay -- 100 ms
09-26 06:55:30.071  5887  5907 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 06:55:30.206  5887  5907 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-26 06:55:30.207  5887  5907 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-26 06:55:30.208  5887  5907 I bt_hwcfg: vendor lib fwcfg completed
,09-26 06:55:30.208  5887  5907 I bt_vendor: firmware callback
,09-26 06:55:30.208  5887  5907 I bt_hci  : firmware_config_callback
,09-26 06:55:30.217  5887  5910 I bt_btu  : btu_task pending for preload complete event
,09-26 06:55:30.217  5887  5910 I bt_btu_task: Bluetooth chip preload is complete
09-26 06:55:30.218  5887  5910 I bt_btu  : btu_task received preload complete event
,09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_AVRC
09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_A2D
09-26 06:55:30.224  5887  5910 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_GAP
,09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_SDP
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_SMP
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 06:55:30.225  5887  5910 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 06:55:30.321  5887  5910 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ce9549
,09-26 06:55:30.321  5887  5910 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ce9549 
,09-26 06:55:30.344  5887  5903 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 06:55:30.346  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 06:55:30.347  5887  5903 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 06:55:30.349  5887  5903 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 06:55:30.352  5887  5903 D BluetoothAdapterProperties: Scan Mode:20
09-26 06:55:30.352  5887  5903 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 06:55:30.353  5887  5903 D bt_hci  : do_postload posting postload work item
09-26 06:55:30.353  5887  5907 I bt_hci  : event_postload
09-26 06:55:30.353  5887  5907 I bt_vendor: sco_config_cb
09-26 06:55:30.353  5887  5907 I bt_hci  : sco_config_callback postload finished.
,09-26 06:55:30.357  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:30.359  5887  5903 D bt_bte_conf: Device ID record 1 : primary
09-26 06:55:30.359  5887  5903 D bt_bte_conf:   vendorId            = 000f
09-26 06:55:30.359  5887  5903 D bt_bte_conf:   vendorIdSource      = 0001
09-26 06:55:30.359  5887  5903 D bt_bte_conf:   product             = 1200
,09-26 06:55:30.359  5887  5903 D bt_bte_conf:   version             = 1436
09-26 06:55:30.360  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:30.359  5887  5903 D bt_bte_conf:   clientExecutableURL = 
09-26 06:55:30.360  5887  5903 D bt_bte_conf:   serviceDescription  = 
09-26 06:55:30.361  5887  5903 D bt_bte_conf:   documentationURL    = 
,09-26 06:55:30.361  5887  5903 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 06:55:30.361  5887  5900 D bt_stack_manager: event_start_up_stack finished
09-26 06:55:30.361  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 06:55:30.362  5887  5899 D BluetoothAdapterProperties: Setting state to 15
09-26 06:55:30.362  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-26 06:55:30.362  5887  5907 I bt_vendor: low_power_mode_cb
09-26 06:55:30.364  5887  5899 I BluetoothAdapterState: Entering BleOnState
,09-26 06:55:30.370  5887  5899 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-26 06:55:30.370  5887  5899 D BluetoothAdapterProperties: Setting state to 11
,09-26 06:55:30.370  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 06:55:30.375  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:30.376  5887  5887 D HeadsetService: Received start request. Starting profile...
09-26 06:55:30.379  5887  5887 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 06:55:30.379  5887  5887 D HeadsetStateMachine: make
,09-26 06:55:30.384  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:30.387  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:30.395  5887  5887 D HeadsetStateMachine: max_hf_connections = 1
,09-26 06:55:30.395  5887  5887 I bt_bluedroid: get_profile_interface handsfree
09-26 06:55:30.395  5887  5899 I BluetoothAdapterState: Entering PendingCommandState
09-26 06:55:30.395  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 06:55:30.396  5887  5903 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-26 06:55:30.399  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:30.399  5887  5887 D A2dpService: Received start request. Starting profile...
,09-26 06:55:30.400  5887  5887 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-26 06:55:30.400  5887  5887 I bt_bluedroid: get_profile_interface avrcp
,09-26 06:55:30.406  5887  5887 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-26 06:55:30.406  5887  5887 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-26 06:55:30.406  5887  5887 D A2dpStateMachine: make
,09-26 06:55:30.408  5887  5887 I bt_bluedroid: get_profile_interface a2dp
,09-26 06:55:30.408  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-26 06:55:30.410  5887  5918 D A2dpStateMachine: Enter Disconnected: -2
09-26 06:55:30.412  5887  5887 I BluetoothHidServiceJni: classInitNative: succeeds
,09-26 06:55:30.413  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 06:55:30.414  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:30.414  5887  5887 D HidService: Received start request. Starting profile...
09-26 06:55:30.415  5887  5887 I bt_bluedroid: get_profile_interface hidhost
09-26 06:55:30.415  5887  5903 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cca56d
09-26 06:55:30.415  5887  5887 D HidService: setHidService(): set to: null
,09-26 06:55:30.415  5887  5903 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 06:55:30.415  5887  5887 I BluetoothHealthServiceJni: classInitNative: succeeds
09-26 06:55:30.416  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:30.417  5887  5887 D HealthService: Received start request. Starting profile...
,09-26 06:55:30.418  5887  5887 I bt_bluedroid: get_profile_interface health
,09-26 06:55:30.421  5887  5887 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-26 06:55:30.421  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
09-26 06:55:30.422  5887  5887 D PanService: Received start request. Starting profile...
09-26 06:55:30.422  5887  5887 D BluetoothPanServiceJni: initializeNative(L110): pan
09-26 06:55:30.422  5887  5887 I bt_bluedroid: get_profile_interface pan
,09-26 06:55:30.422  5887  5903 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 06:55:30.424  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:30.425  5887  5887 D BluetoothMapService: Received start request. Starting profile...
09-26 06:55:30.425  5887  5887 D BluetoothMapService: start()
,09-26 06:55:30.430  5887  5887 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-26 06:55:30.433  5887  5887 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 06:55:30.433  5887  5887 D BluetoothMapAppObserver: createReceiver()
09-26 06:55:30.435  5887  5887 D BluetoothMapAppObserver: initObservers()
,09-26 06:55:30.435  5887  5887 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 06:55:30.442  5887  5887 V SapService: SapBinder()
,09-26 06:55:30.442  5887  5887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:30.442  5887  5887 D SapService: Received start request. Starting profile...
,09-26 06:55:30.443  5887  5887 V SapService: start()
,09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.445  5887  5915 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:30.445  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.446  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.446  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.446  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 06:55:30.446  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 06:55:30.447  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.448  5887  5887 V BluetoothAdapterState: isTurningOff()=false
09-26 06:55:30.448  5887  5887 V BluetoothAdapterState: isTurningOn()=true
09-26 06:55:30.448  5887  5887 V BluetoothAdapterState: isBleTurningOn()=false
09-26 06:55:30.448  5887  5887 V BluetoothAdapterState: isBleTurningOff()=false
09-26 06:55:30.448  5887  5899 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 06:55:30.448  5887  5899 D BluetoothAdapterProperties: ScanMode =  20
09-26 06:55:30.448  5887  5899 D BluetoothAdapterProperties: State =  11
09-26 06:55:30.448  5887  5899 D BluetoothAdapterProperties: Setting state to 12
09-26 06:55:30.448  5887  5899 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 06:55:30.449  5887  5899 I BluetoothAdapterState: Entering OnState
,09-26 06:55:30.449  3119  3968 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 06:55:30.449  5887  5903 D BluetoothAdapterProperties: Scan Mode:21
09-26 06:55:30.450  5887  5903 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 06:55:30.452   933   950 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 06:55:30.452  5674  5686 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 06:55:30.453  3119  3119 D BluetoothInputDevice: Proxy object connected
09-26 06:55:30.453  3119  3119 D HidProfile: Bluetooth service connected
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:30.454  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:30.454   933   933 D BluetoothA2dp: Proxy object connected
09-26 06:55:30.454  3794  3832 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:30.455  5674  5685 D BluetoothPbap: onBluetoothStateChange: up=true
,09-26 06:55:30.456  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:30.456   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 06:55:30.457  3119  3972 D BluetoothPbap: onBluetoothStateChange: up=true
,09-26 06:55:30.458  3119  3130 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:30.458   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:30.458  5674  5686 D BluetoothPan: onBluetoothStateChange on: true
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:30.459  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 06:55:30.460  3119  3968 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-26 06:55:30.461  5887  5887 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 06:55:30.461  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:30.462  5887  5887 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 06:55:30.462  3119  3119 D BluetoothA2dp: Proxy object connected
09-26 06:55:30.462  5674  5686 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:30.463  5887  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:55:30.463  5674  5685 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 06:55:30.465  5887  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:55:30.466  5674  5686 D BluetoothMap: onBluetoothStateChange: up=true
09-26 06:55:30.466  5674  5674 D BluetoothInputDevice: Proxy object connected
,09-26 06:55:30.466  5674  5674 D HidProfile: Bluetooth service connected
09-26 06:55:30.466  5887  5887 D ObexServerSockets: Succeed to create listening sockets 
09-26 06:55:30.466  5887  5887 D ObexServerSockets0: startAccept()
09-26 06:55:30.466  5887  5887 D ObexServerSockets0: prepareForNewConnect()
09-26 06:55:30.467   933   950 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 06:55:30.468  3119  3972 D BluetoothMap: onBluetoothStateChange: up=true
09-26 06:55:30.468  5887  5887 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 06:55:30.468  5887  5887 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 06:55:30.469  5887  5925 D ObexServerSockets0: Accepting socket connection...
09-26 06:55:30.469  5887  5926 D ObexServerSockets0: Accepting socket connection...
09-26 06:55:30.469  3119  3119 D BluetoothMap: Proxy object connected
,09-26 06:55:30.469  3119  3119 D MapProfile: Bluetooth service connected
09-26 06:55:30.469  3119  3119 D BluetoothMap: getConnectedDevices()
09-26 06:55:30.469  3119  3137 D BluetoothPan: onBluetoothStateChange on: true
09-26 06:55:30.471  3119  3119 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 06:55:30.471  3119  3119 D PanProfile: Bluetooth service connected
09-26 06:55:30.471   933   933 I Telecom : BluetoothPhoneService: queryPhoneState
09-26 06:55:30.473  5887  5887 D BluetoothMapService: onReceive
,09-26 06:55:30.473  5887  5887 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 06:55:30.473  5887  5887 D BluetoothMapService: STATE_ON
,09-26 06:55:30.475  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:30.475  5674  5674 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 06:55:30.475  5674  5674 D PanProfile: Bluetooth service connected
09-26 06:55:30.475  5674  5674 D BluetoothA2dp: Proxy object connected
09-26 06:55:30.476  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:30.477  5887  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:55:30.477  5674  5674 D BluetoothMap: Proxy object connected
09-26 06:55:30.477  5674  5674 D MapProfile: Bluetooth service connected
09-26 06:55:30.477  5674  5674 D BluetoothMap: getConnectedDevices()
09-26 06:55:30.478  5887  5927 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 06:55:30.478  5887  5927 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-26 06:55:30.484  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 06:55:30.488  5674  5674 D DockEventReceiver: finishStartingService: stopping service
09-26 06:55:30.489  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 06:55:30.496  5674  5674 D BluetoothPbap: Proxy object connected
,09-26 06:55:30.496  5674  5674 D PbapServerProfile: Bluetooth service connected
,09-26 06:55:30.499  3119  3119 D BluetoothPbap: Proxy object connected
09-26 06:55:30.499  3119  3119 D PbapServerProfile: Bluetooth service connected
,09-26 06:55:30.500  5887  5887 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 06:55:30.500  5887  5887 D ObexServerSockets0: prepareForNewConnect()
,09-26 06:55:30.503  5887  5931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 06:55:30.518  5887  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 06:55:30.519  5887  5935 I BtOppRfcommListener: Accept thread started.
,09-26 06:55:30.556   933   933 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.556  3119  3130 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.557   933   933 D BluetoothHeadset: Proxy object connected
,09-26 06:55:30.557  3119  3119 D HeadsetProfile: Bluetooth service connected
09-26 06:55:30.557  3794  3820 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.557   933   933 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.557   933   950 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.557  5674  5924 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.559  3119  3968 D BluetoothHeadset: Proxy object connected
09-26 06:55:30.559  3119  3119 D HeadsetProfile: Bluetooth service connected
09-26 06:55:30.559   933   950 D BluetoothHeadset: Proxy object connected
,09-26 06:55:30.560  5674  5674 D HeadsetProfile: Bluetooth service connected
,09-26 06:55:30.562  5674  5685 D BluetoothHeadset: Proxy object connected
,09-26 06:55:30.563  5674  5674 D HeadsetProfile: Bluetooth service connected
,09-26 06:55:30.568   933   950 D BluetoothHeadset: Proxy object connected
,09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:34.258  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:34.263  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:34.264  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:55:34.264  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6a6faf removed from the list
09-26 06:55:34.264  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 06:55:34.264  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:34.265  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:34.267  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:55:34.267  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab30fbc added. We now have 4 listener(s)
09-26 06:55:34.267  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:55:34.270   933   943 D WifiService: setWifiEnabled: false pid=5621, uid=10077
09-26 06:55:34.271   933   943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 06:55:36.628   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:37.630   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:38.631   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:39.281  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:39.282   933  5533 D WifiService: setWifiEnabled: true pid=5621, uid=10077
,09-26 06:55:39.282   933  5533 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 06:55:39.291   506   927 D SoftapController: Softap fwReload - Ok
,09-26 06:55:39.298   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:39.298   506   927 D CommandListener: Trying to bring down wlan0
09-26 06:55:39.300   506   927 D CommandListener: Clearing all IP addresses on wlan0
,09-26 06:55:39.305   933  2961 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 06:55:39.632   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:39.983   933  2961 D wifi    : set interface wlan0 flags (UP)
,09-26 06:55:39.983   933  2961 I WifiHAL : Initializing wifi
,09-26 06:55:39.983   933  2961 I WifiHAL : Creating socket
,09-26 06:55:39.989   933  2961 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 06:55:39.990   933  2961 D wifi    : Did set static halHandle = 0x7f905c8680
09-26 06:55:39.990   933  2961 D wifi    : halHandle = 0x7f905c8680, mVM = 0x7facc0d140, mCls = 0x10167a
09-26 06:55:39.990   933  2961 D wifi    : array field set
09-26 06:55:39.990   933  2961 I WifiNative-HAL: interface[0] = wlan0
09-26 06:55:39.992   933   950 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-26 06:55:39.993   933  5941 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547882829440
09-26 06:55:39.994   933  5941 D wifi    : waitForHalEvents called, vm = 0x7facc0d140, obj = 0x10167a, env = 0x7f8d6e4d00
09-26 06:55:39.999   933  2961 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 06:55:40.001   933  2961 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-26 06:55:40.007  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:40.010  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:40.045  5942  5942 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 06:55:40.065  5942  5942 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 06:55:40.106  5942  5942 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 06:55:40.106  5942  5942 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 06:55:40.634   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 06:55:41.018   933  2961 D WifiConfigStore: Loading config and enabling all networks 
,09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:41.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:41.027  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:41.035  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:41.039  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 06:55:41.044   933  2961 D WifiConfigStore: loaded 0 passpoint configs
,09-26 06:55:41.045   933  2961 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 06:55:41.045   933  2961 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 06:55:41.047   933  2961 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 06:55:41.049   933  2961 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-26 06:55:41.049   933  2961 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-26 06:55:41.049   933  2961 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 06:55:41.049   933  2961 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-26 06:55:41.055   933  2961 D WifiNative-HAL: Setting external_sim to 1
09-26 06:55:41.056   933  2961 D wifi    : setting dfs flag to true, 0x7f8dd3ef00
,09-26 06:55:41.057   933  2961 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 06:55:41.057   933  2961 D wifi    : setting scan oui 0x7f8dd3ef00
09-26 06:55:41.057   933  2961 D WifiHAL : Sending mac address OUI
09-26 06:55:41.059  4992  4992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 06:55:41.064   933  2961 E native  : do suspend false
,09-26 06:55:41.079   933  2961 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-26 06:55:41.080   506   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-26 06:55:41.081   933   933 D RttService: SCAN_AVAILABLE : 3
09-26 06:55:41.081   933  3070 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-26 06:55:41.082   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:41.088   933  2960 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-26 06:55:41.088   933  2960 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 06:55:41.102   933  2960 D WifiNative-HAL: p2pGetDeviceAddress
09-26 06:55:41.103   933  2960 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 06:55:41.111   933   948 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304084 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=23 mControllerEnergyUsed=87 }
,09-26 06:55:41.635   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 06:55:44.286  5942  5942 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:44.297  5942  5942 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 06:55:44.299  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 06:55:44.302  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 06:55:44.303  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:55:44.303  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab30fbc removed from the list
,09-26 06:55:44.303  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:55:44.303  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:44.303  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:55:44.304  5942  5942 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-26 06:55:44.308  5621  5944 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-26 06:55:44.309  5621  5944 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-26 06:55:44.311  5942  5942 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 06:55:44.345   933  2961 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-26 06:55:44.346   933  2961 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-26 06:55:44.346   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:55:44.358   933  2961 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 06:55:44.396   933  2961 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 06:55:44.398  5942  5942 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 06:55:44.831  5942  5942 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 06:55:44.867  5942  5942 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 06:55:44.868  5942  5942 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 06:55:44.878   933  2961 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 06:55:44.879   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:55:44.879   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 06:55:44.896   933  2961 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 06:55:44.908   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:44.913   933  2961 D WifiStateMachine: Start Dhcp Watchdog 3
,09-26 06:55:44.921   933  5948 D DhcpClient: Receive thread started
09-26 06:55:44.926   933  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-26 06:55:44.926   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-26 06:55:44.926   933  2963 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-26 06:55:45.015   933  2961 E native  : do suspend false
,09-26 06:55:45.037   933  5947 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 06:55:45.054   933  5948 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-26 06:55:45.056   933  5947 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-26 06:55:45.058   933  5947 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 06:55:45.072   933  5948 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 06:55:45.073   933  5947 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-26 06:55:45.076   506   927 D CommandListener: Setting iface cfg
,09-26 06:55:45.082   933  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 06:55:45.088   933  5947 D DhcpClient: Scheduling renewal in 86399s
,09-26 06:55:45.100   933  2961 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 06:55:45.101   933  2961 D WifiConfigStore: No blacklist allowed without epno enabled
09-26 06:55:45.103   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-26 06:55:45.107   933  2963 D ConnectivityService: Adding iface wlan0 to network 102
09-26 06:55:45.108   933  2961 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 06:55:45.158   933  2963 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-26 06:55:45.158   933  2963 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-26 06:55:45.161   933  2963 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-26 06:55:45.164   933  2963 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-26 06:55:45.166   933  2963 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-26 06:55:45.173   933  2963 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 06:55:45.178   933  2963 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-26 06:55:45.178   933  2963 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-26 06:55:45.178   933  2963 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-26 06:55:45.178   933  2963 D ConnectivityService:    accepting network in place of null
09-26 06:55:45.178   933  2961 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 06:55:45.178   933  2961 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 06:55:45.179   933  2963 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 06:55:45.187   933  5946 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308161, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 06:55:45.202   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:55:45.224   506   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 06:55:45.228   933  2963 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-26 06:55:45.228   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 06:55:45.229  3759  3899 W QCNEJ   : |CORE| network available: 102
,09-26 06:55:45.230   933  2963 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-26 06:55:45.231   933   950 D Tethering: MasterInitialState.processMessage what=3
,09-26 06:55:45.231  3759  3899 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-26 06:55:45.238  3759  3899 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-26 06:55:45.239  3759  3899 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:45.245  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:55:45.247  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:45.251  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:55:45.254  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:55:45.255   933  5945 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-26 06:55:45.255  5018  5042 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 06:55:45.256  5018  5042 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 06:55:45.256  5018  5042 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 06:55:45.256  5018  5042 E SarControlService: no key has been found,reset the power
09-26 06:55:45.256  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-26 06:55:45.256  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 06:55:45.256  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 06:55:45.257  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 06:55:45.257  5043  5043 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-26 06:55:45.259  3911  3911 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-26 06:55:45.261  5018  5055 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 06:55:45.261  5018  5055 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 06:55:45.261  5018  5055 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 06:55:45.262  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-26 06:55:45.264  3731  3731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 06:55:45.268  5043  5043 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-26 06:55:45.270  3731  3731 D SystemUpdateService: onCreate
09-26 06:55:45.272  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000f003000000000000ffffffff]
09-26 06:55:45.272  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:55:45.272  5043  5057 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-26 06:55:45.272  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 06:55:45.272  5018  5029 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-26 06:55:45.274  5043  5057 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@24e1da HexData = [00000000f103000000000000ffffffff]
,09-26 06:55:45.274  5043  5057 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 06:55:45.274  5043  5057 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,09-26 06:55:45.275  5043  5043 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-26 06:55:45.275  5018  5028 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 06:55:45.277  3731  3731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 06:55:45.286  3731  3731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-26 06:55:45.293  3731  5386 I iu.UploadsManager: num queued entries: 0
,09-26 06:55:45.293  3731  5386 I iu.UploadsManager: num updated entries: 0
09-26 06:55:45.294  3731  5386 I iu.SyncManager: NEXT; no task
,09-26 06:55:45.295  3731  5958 I SystemUpdateService: active receiver: enabled
,09-26 06:55:45.297  3731  3731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 06:55:45.299  3731  3731 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 06:55:45.300   933  5945 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 10:55:45 GMT], X-Android-Received-Millis=[1474887345300], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474887345278]}
09-26 06:55:45.301   933  2963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 06:55:45.301   933  2963 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-26 06:55:45.301  5737  5737 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 06:55:45.301   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 06:55:45.302   933  2963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 06:55:45.306  5737  5737 D SprintDMHelper: simOperator: 
09-26 06:55:45.306  5737  5737 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 06:55:45.342  3731  5958 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 06:55:45.352  3731  5958 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-26 06:55:45.352  3731  5958 I SystemUpdateService: now status is 0 (complete)
09-26 06:55:45.352  3731  5958 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 06:55:45.352  3731  5958 I SystemUpdateService: file has been verified
09-26 06:55:45.352  3731  5958 I SystemUpdateService: OTA package size = 21989297
,09-26 06:55:45.358  3731  5958 I SystemUpdateService: showing system update notification
,09-26 06:55:45.368  3731  3731 D SystemUpdateService: onDestroy
,09-26 06:55:45.430  4992  5964 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-26 06:55:47.339  5621  5944 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-26 06:55:47.339  5621  5970 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-26 06:55:47.340  5621  5944 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 06:55:47.340  5621  5970 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-26 06:55:47.341  5621  5944 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 06:55:47.341  5621  5970 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 06:55:47.342  5621  5944 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 06:55:47.343  5621  5970 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 06:55:47.345  5621  5972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender)
,09-26 06:55:47.345  5621  5944 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 06:55:47.349  5621  5973 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender)
,09-26 06:55:47.349  5621  5970 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-26 06:55:47.351  5621  5974 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver)
,09-26 06:55:47.352  5621  5974 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver)
,09-26 06:55:47.352  5621  5975 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver)
,09-26 06:55:47.353  5621  5974 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-26 06:55:47.353  5621  5974 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-26 06:55:47.354  5621  5975 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver)
,09-26 06:55:47.354  5621  5975 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-26 06:55:47.354  5621  5975 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-26 06:55:50.316  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-26 06:55:50.317  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-26 06:55:50.323  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@982df7e Bundle[{}]
,09-26 06:55:50.325  5621  5667 I io.jxcore.node.LifeCycleMonitor: start: OK
09-26 06:55:50.326  5621  5667 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-26 06:55:50.327  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-26 06:55:50.328  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-26 06:55:50.328  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-26 06:55:50.329  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-26 06:55:50.336  5621  5667 I System.out: Running OutgoingSocketThread
,09-26 06:55:50.339  5621  5976 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-26 06:55:50.339  5621  5976 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-26 06:55:53.183   933  2963 D ConnectivityService: handlePromptUnvalidated 102
,09-26 06:55:53.350  5621  5977 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-26 06:55:53.350  5621  5976 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-26 06:55:53.350  5621  5976 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-26 06:55:53.350  5621  5977 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-26 06:55:53.350  5621  5976 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 06:55:53.350  5621  5977 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 06:55:53.352  5621  5977 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 06:55:53.352  5621  5976 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 06:55:53.355  5621  5979 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender)
09-26 06:55:53.356  5621  5976 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-26 06:55:53.356  5621  5977 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-26 06:55:53.360  5621  5980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender)
09-26 06:55:53.360  5621  5981 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver)
09-26 06:55:53.361  5621  5982 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Receiver)
09-26 06:55:53.362  5621  5982 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: IncomingSocketThread/Receiver)
09-26 06:55:53.362  5621  5982 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-26 06:55:53.362  5621  5981 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver)
,09-26 06:55:53.363  5621  5982 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-26 06:55:53.363  5621  5981 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-26 06:55:53.363  5621  5981 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-26 06:55:56.114   933  2961 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-26 06:55:56.348  5621  5667 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-26 06:55:56.349  5621  5667 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-26 06:55:56.349  5621  5667 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-26 06:55:56.355  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 06:55:56.355  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4712b45 added. We now have 3 listener(s)
,09-26 06:55:56.361  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 06:55:56.361  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:55:56.361  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 06:55:56.361  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:55:56.361  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbca29a added. We now have 4 listener(s)
09-26 06:55:56.361  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:55:56.363  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 06:55:56.369  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:56.376  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:55:56.379  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:55:56.380  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:55:56.380  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:55:56.380  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 06:55:56.380  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:55:56.380  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:55:56.380  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:55:56.380  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:55:56.380  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 06:55:56.381  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4712b45 removed from the list
,09-26 06:55:56.381  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:55:56.381  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbca29a removed from the list
09-26 06:55:56.383  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:56.386  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:56.386  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 06:55:56.386  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:56.387  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:56.387  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:55:56.388  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:55:56.388  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:55:56.388  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:55:56.388  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbca29a not in the list
09-26 06:55:56.388  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:56.388  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:55:56.389  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:55:56.389  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:55:56.389  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:55:56.390  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbca29a not in the list
09-26 06:55:56.390  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:55:56.390  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:56.390  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:55:56.390  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4712b45 not in the list
09-26 06:55:56.390  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 06:55:56.391  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f6ba8 added. We now have 3 listener(s)
09-26 06:55:56.392  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 06:55:56.392  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:55:56.392  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 06:55:56.392  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:55:56.392  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe36c1 added. We now have 4 listener(s)
09-26 06:55:56.392  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:55:56.393  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 06:55:56.396  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:56.401  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:55:56.402  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:56.402  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:55:56.402  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:55:56.402  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 06:55:56.403  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 06:55:56.403  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:55:56.403  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:55:56.406  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:56.408  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:55:56.408  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 06:55:56.409  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:56.415  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:55:56.416  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:55:56.416  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 06:55:56.420  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 06:55:56.420  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 06:55:56.420  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-26 06:55:56.421  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:55:56.424  5887  5898 D BtGatt.GattService: registerClient() - UUID=2dace6e3-8c72-45bf-b5cf-843b6dc50c75
09-26 06:55:56.425  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=2dace6e3-8c72-45bf-b5cf-843b6dc50c75, clientIf=5
,09-26 06:55:56.425  5621  5717 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 06:55:56.426  5887  5923 D BtGatt.GattService: start scan with filters
,09-26 06:55:56.429  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-26 06:55:56.430  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 06:55:56.430  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 06:55:56.430  5887  5906 D BtGatt.ScanManager: handling starting scan
09-26 06:55:56.430  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 06:55:56.432  5887  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f59eb83
,09-26 06:55:56.432  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 06:55:56.433  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 06:55:56.433  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 06:55:56.434  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 06:55:56.437  5621  5667 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-26 06:55:56.437  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 06:55:56.437  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 06:55:56.437  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:56.437  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:55:56.437  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 06:55:56.437  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-26 06:55:56.437  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 06:55:56.437  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 06:55:56.437  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 06:55:56.437  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 06:55:56.438  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:55:56.439  5887  5897 D BtGatt.GattService: stopScan() - queue size =1
09-26 06:55:56.440  5887  5903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 06:55:56.440  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:55:56.440  5887  5916 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 06:55:56.440  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 06:55:56.440  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 06:55:56.441  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 06:55:56.441  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 06:55:56.441  5887  5906 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 06:55:56.441  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 06:55:56.442  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:55:56.442  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:55:56.442  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 06:55:56.442  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:55:56.443  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:55:56.445  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:55:56.445  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:55:56.445  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:55:56.448  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 06:55:56.448  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:55:56.448  5887  5906 D BtGatt.ScanManager: Starting BLE batch scan
09-26 06:55:56.449  5887  5906 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 06:55:56.450  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:55:56.450  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 06:55:56.455  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 06:55:56.455  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:55:56.455  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 06:55:56.456  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:55:56.456  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 06:55:56.459  5887  5903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 06:55:56.460  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:55:56.461  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 06:55:56.461  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:55:56.461  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:55:56.464  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:55:56.464  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 06:55:56.464  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:55:56.466  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 06:55:56.466  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:55:56.466  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 06:55:56.473  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 06:55:56.473  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:55:56.473  5887  5906 D BtGatt.ScanManager: stopping BLe Batch
,09-26 06:55:56.479  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 06:55:56.479  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:55:56.479  5887  5906 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 06:55:56.484  5887  5903 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-26 06:55:56.484  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:55:56.968  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 06:55:56.968  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:55:56.969  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 06:55:59.445  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:55:59.446  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 06:55:59.446  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 06:55:59.446  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:55:59.446  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:55:59.447  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 06:55:59.447  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-26 06:55:59.447  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f6ba8 removed from the list
09-26 06:55:59.447  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:55:59.447  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe36c1 removed from the list
09-26 06:55:59.447  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:55:59.448  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:59.452  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:59.452  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:59.458  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:55:59.458  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:55:59.459  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:55:59.461  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:55:59.462  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:55:59.462  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 06:55:59.462  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:55:59.462  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe36c1 not in the list
,09-26 06:55:59.463  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:55:59.463  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:55:59.466  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:55:59.468  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:55:59.468  5621  5667 D BluetoothLeScanner: could not find callback wrapper
,09-26 06:55:59.468  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:55:59.468  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:55:59.468  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:55:59.468  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:55:59.468  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffe36c1 not in the list
09-26 06:55:59.468  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:55:59.469  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:55:59.469  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:55:59.469  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77f6ba8 not in the list
09-26 06:55:59.470  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 06:55:59.470  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2c43e added. We now have 3 listener(s)
,09-26 06:55:59.473  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 06:55:59.473  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-26 06:55:59.474  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 06:55:59.474  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:55:59.474  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41ca29f added. We now have 4 listener(s)
09-26 06:55:59.474  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 06:55:59.475  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 06:55:59.481  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:55:59.490  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:55:59.493  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 06:55:59.494  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:55:59.494  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 06:55:59.495  5621  5667 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-26 06:55:59.495  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-26 06:55:59.496  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-26 06:55:59.496  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-26 06:55:59.496  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-26 06:55:59.496  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:55:59.498  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-26 06:55:59.500  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:55:59.501  5916  5916 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[36023]" dev="sockfs" ino=36023 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 06:55:59.500  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-26 06:55:59.501  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-26 06:55:59.501  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-26 06:55:59.501  5621  5983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 06:55:59.501  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-26 06:55:59.502  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:55:59.504  5621  5983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-26 06:55:59.503  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:55:59.501  5916  5916 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[36023]" dev="sockfs" ino=36023 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 06:55:59.505  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:55:59.505  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-26 06:55:59.508  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:55:59.508  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 06:55:59.512  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:55:59.513  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 06:55:59.513  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 06:55:59.515  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-26 06:55:59.516  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 06:55:59.516  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-26 06:55:59.517  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-26 06:55:59.517  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-26 06:55:59.517  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-26 06:55:59.518  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:55:59.523  5887  5923 D BtGatt.GattService: registerClient() - UUID=de0ab0a3-84d1-4650-8cf6-daaf4937ac53
,09-26 06:55:59.523  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=de0ab0a3-84d1-4650-8cf6-daaf4937ac53, clientIf=5
09-26 06:55:59.524  5621  5717 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-26 06:55:59.526  5887  5905 D BtGatt.AdvertiseManager: message : 0
,09-26 06:55:59.528  5887  5905 D BtGatt.AdvertiseManager: starting multi advertising
,09-26 06:55:59.539  5887  5903 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-26 06:55:59.546  5887  5903 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-26 06:55:59.547  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-26 06:55:59.547  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 06:55:59.549  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 06:55:59.551  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-26 06:55:59.551  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-26 06:55:59.551  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-26 06:55:59.551  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-26 06:55:59.551  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-26 06:55:59.551  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-26 06:55:59.554  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-26 06:55:59.554  5621  5621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-26 06:55:59.555  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-26 06:56:00.055  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-26 06:56:00.056  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 06:56:00.056  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 06:56:02.555  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:56:02.556  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-26 06:56:02.556  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 06:56:02.556  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 06:56:02.556  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-26 06:56:02.556  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-26 06:56:02.557  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-26 06:56:02.557  5621  5983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 06:56:02.557  5621  5983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-26 06:56:02.557  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 06:56:02.557  5621  5983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 06:56:02.557  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 06:56:02.558  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-26 06:56:02.558  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 06:56:02.558  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-26 06:56:02.558  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 06:56:02.558  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 06:56:02.562  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:56:02.562  5621  5667 D BluetoothLeScanner: could not find callback wrapper
,09-26 06:56:02.562  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:56:02.562  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-26 06:56:02.565  5887  5905 D BtGatt.AdvertiseManager: message : 1
,09-26 06:56:02.566  5887  5905 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-26 06:56:02.582  5887  5903 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-26 06:56:02.582  5887  5903 D BtGatt.GattService: Client app is not null!
,09-26 06:56:02.584  5887  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 06:56:02.585  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:56:02.585  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-26 06:56:02.585  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-26 06:56:02.585  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-26 06:56:02.585  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-26 06:56:02.588  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:56:02.589  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 06:56:02.589  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:56:02.590  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:56:02.592  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:56:02.592  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 06:56:02.592  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:02.592  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:56:02.592  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 06:56:02.592  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2c43e removed from the list
09-26 06:56:02.592  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:56:02.592  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41ca29f removed from the list
09-26 06:56:02.592  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:56:02.592  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:02.592  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 06:56:02.593  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:56:02.593  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:56:02.599  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:56:02.599  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 06:56:02.605  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 06:56:02.607  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 06:56:02.607  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 06:56:02.607  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:56:02.608  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:56:02.610  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:02.611  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:56:02.612  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:56:02.612  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 06:56:02.613  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:56:02.614  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:56:02.614  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:56:02.614  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:56:02.614  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:02.614  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:56:02.614  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41ca29f not in the list
09-26 06:56:02.614  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:56:02.614  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:56:02.619  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:56:02.619  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:56:02.620  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:02.622  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:56:02.622  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 06:56:02.623  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:56:02.624  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:56:02.625  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:56:02.625  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:56:02.625  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:56:02.625  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:56:02.625  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:56:02.625  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:02.626  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41ca29f not in the list
09-26 06:56:02.626  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 06:56:02.626  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:02.626  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:02.626  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2c43e not in the list
,09-26 06:56:02.627  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 06:56:02.627  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29c4084 added. We now have 3 listener(s)
09-26 06:56:02.629  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 06:56:02.629  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:56:02.629  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 06:56:02.629  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:56:02.629  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@247e06d added. We now have 4 listener(s)
09-26 06:56:02.629  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 06:56:02.630  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 06:56:02.635  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:56:02.640  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:56:02.642  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:56:02.642  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:56:02.642  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:56:02.642  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 06:56:02.642  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 06:56:02.642  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:56:02.642  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:56:02.645  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:56:02.648  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:56:02.648  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 06:56:02.648  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 06:56:02.653  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 06:56:02.654  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 06:56:02.654  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 06:56:02.657  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 06:56:02.657  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 06:56:02.658  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 06:56:02.658  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:56:02.661  5887  5916 D BtGatt.GattService: registerClient() - UUID=89c58b3a-c547-41c1-b50a-4a2ea06e9221
,09-26 06:56:02.661  5887  5903 D BtGatt.GattService: onClientRegistered() - UUID=89c58b3a-c547-41c1-b50a-4a2ea06e9221, clientIf=5
,09-26 06:56:02.662  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 06:56:02.662  5887  5923 D BtGatt.GattService: start scan with filters
09-26 06:56:02.665  5887  5906 D BtGatt.ScanManager: handling starting scan
09-26 06:56:02.665  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 06:56:02.665  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 06:56:02.666  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 06:56:02.666  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 06:56:02.669  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 06:56:02.670  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 06:56:02.670  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 06:56:02.671  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 06:56:02.674  5887  5903 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 06:56:02.674  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:56:02.675  5887  5906 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 06:56:02.681  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-26 06:56:02.682  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:56:02.682  5887  5906 D BtGatt.ScanManager: Starting BLE batch scan
09-26 06:56:02.682  5887  5906 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 06:56:02.694  5887  5903 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-26 06:56:02.694  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:56:02.700  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 06:56:02.700  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 06:56:03.049   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 06:56:03.124  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 06:56:03.170  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 06:56:03.170  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 06:56:03.170  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 06:56:05.683  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 06:56:05.683  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 06:56:05.683  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 06:56:05.684  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.684  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:56:05.684  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 06:56:05.684  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 06:56:05.684  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 06:56:05.684  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 06:56:05.685  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-26 06:56:05.685  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 06:56:05.687  5621  5667 D BluetoothAdapter: STATE_ON
,09-26 06:56:05.690  5887  5898 D BtGatt.GattService: stopScan() - queue size =1
09-26 06:56:05.692  5887  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 06:56:05.693  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:56:05.693  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 06:56:05.693  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-26 06:56:05.693  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 06:56:05.694  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-26 06:56:05.696  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 06:56:05.697  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:56:05.697  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 06:56:05.697  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:56:05.699  5887  5887 D BtGatt.ScanManager: awakened up at time 328673
09-26 06:56:05.700  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:56:05.703  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:56:05.703  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:56:05.703  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:56:05.703  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 06:56:05.704  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.704  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 06:56:05.704  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 06:56:05.704  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29c4084 removed from the list
09-26 06:56:05.704  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:05.704  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@247e06d removed from the list
09-26 06:56:05.704  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:56:05.704  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:56:05.708  5887  5903 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 06:56:05.708  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:56:05.708  5887  5906 D BtGatt.ScanManager: stopping BLe Batch
,09-26 06:56:05.712  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 06:56:05.712  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 06:56:05.716  5887  5903 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 06:56:05.716  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:56:05.716  5887  5906 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 06:56:05.716  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 06:56:05.717  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 06:56:05.717  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 06:56:05.717  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 06:56:05.718  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:05.721  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:56:05.721  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:05.722  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 06:56:05.722  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 06:56:05.722  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 06:56:05.725  5621  5621 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 06:56:05.726  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 06:56:05.726  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:56:05.728  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:56:05.728  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 06:56:05.728  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:56:05.728  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:56:05.729  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:56:05.729  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:56:05.729  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:56:05.729  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:05.729  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@247e06d not in the list
09-26 06:56:05.729  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.729  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:56:05.731  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 06:56:05.731  5621  5667 D BluetoothAdapter: STATE_ON
09-26 06:56:05.731  5621  5667 D BluetoothLeScanner: could not find callback wrapper
09-26 06:56:05.731  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 06:56:05.731  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:56:05.732  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 06:56:05.732  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:05.732  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@247e06d not in the list
09-26 06:56:05.732  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:56:05.732  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.732  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:05.732  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29c4084 not in the list
,09-26 06:56:05.733  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 06:56:05.733  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9975fa added. We now have 3 listener(s)
09-26 06:56:05.734  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 06:56:05.734  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 06:56:05.734  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 06:56:05.734  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 06:56:05.734  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca597ab added. We now have 4 listener(s)
09-26 06:56:05.735  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 06:56:05.735  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 06:56:05.738  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 06:56:05.744  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 06:56:05.746  5887  5903 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-26 06:56:05.746  5887  5903 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 06:56:05.746  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 06:56:05.746  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 06:56:05.747  5887  5903 D BtGatt.GattService: current time is 328720768363
09-26 06:56:05.747  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 06:56:05.747  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 06:56:05.747  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 06:56:05.747  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:56:05.747  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.747  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 06:56:05.747  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 06:56:05.747  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9975fa removed from the list
09-26 06:56:05.747  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:05.747  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca597ab removed from the list
09-26 06:56:05.748  5887  5903 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -75, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 06:56:05.749  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 06:56:05.750  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:56:05.750  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 06:56:05.750  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:56:05.750  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:05.750  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-26 06:56:05.750  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-26 06:56:05.750  5887  5903 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 06:56:05.750  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.750  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 06:56:05.751  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 06:56:05.751  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:56:05.751  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:05.752  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca597ab not in the list
09-26 06:56:05.752  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.752  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:05.753  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 06:56:05.753  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 06:56:05.753  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 06:56:05.753  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca597ab not in the list
,09-26 06:56:05.753  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:56:05.753  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 06:56:05.753  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:05.753  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9975fa not in the list
09-26 06:56:05.753  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 06:56:05.754  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-26 06:56:05.754  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 06:56:05.754  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-26 06:56:05.754  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 06:56:05.754  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-26 06:56:05.754  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-26 06:56:06.069   933  2963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 06:56:06.229  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 06:56:06.636   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 06:56:06.636   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 06:56:07.765  5621  5984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-26 06:56:09.764  5621  5667 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 191
,09-26 06:56:09.764  5621  5667 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 191, name: My test thread name)
,09-26 06:56:09.769  5621  5985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
09-26 06:56:09.769  5621  5985 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name)
,09-26 06:56:09.769  5621  5985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-26 06:56:09.774  5621  5667 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 06:56:09.781  5621  5986 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name)
,09-26 06:56:09.782  5621  5986 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
09-26 06:56:09.782  5621  5986 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-26 06:56:09.805  5621  5667 E jxcore  : Error!: logger is not a function
09-26 06:56:09.805  5621  5667 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"83","_columnNumber":"1","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:83:1"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"}]
,09-26 06:56:09.815  5621  5621 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "logger is not a function\nTypeError: logger is not a function\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:83:1\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7"", source: file:///android_asset/www/js/thali_main.js (56)
,09-26 06:56:09.815  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.815  5621  5667 I jxcore-log: 
,09-26 06:56:09.816  5621  5621 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,09-26 06:56:09.819  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.819  5621  5667 I jxcore-log: 
09-26 06:56:09.822   933   943 I ActivityManager: Killing 5484:com.android.defcontainer/u0a7 (adj 15): empty #17
09-26 06:56:09.830  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.830  5621  5667 I jxcore-log: 
09-26 06:56:09.831  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.831  5621  5667 I jxcore-log: 
,09-26 06:56:09.833  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 06:56:09.833  5621  5667 I jxcore-log: 
,09-26 06:56:09.842  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 06:56:09.842  5621  5667 I jxcore-log: 
,09-26 06:56:09.846  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.846  5621  5667 I jxcore-log: 
,09-26 06:56:09.848  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.848  5621  5667 I jxcore-log: 
,09-26 06:56:09.850  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 06:56:09.850  5621  5667 I jxcore-log: 
,09-26 06:56:09.851  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 06:56:09.851  5621  5667 I jxcore-log: 
09-26 06:56:09.852  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 06:56:09.852  5621  5667 I jxcore-log: 
09-26 06:56:09.852  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.852  5621  5667 I jxcore-log: 
,09-26 06:56:09.855  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.855  5621  5667 I jxcore-log: 
,09-26 06:56:09.857  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.857  5621  5667 I jxcore-log: 
,09-26 06:56:09.858  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.858  5621  5667 I jxcore-log: 
09-26 06:56:09.859  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.859  5621  5667 I jxcore-log: 
09-26 06:56:09.860  5621  5660 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 44ms. Plugin should use CordovaInterface.getThreadPool().
09-26 06:56:09.862  5621  5621 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-26 06:56:09.862  5621  5621 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
09-26 06:56:09.862  5621  5621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 06:56:09.862  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 06:56:09.862  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 06:56:09.862  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 06:56:09.862  5621  5621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e28af9 removed from the list
09-26 06:56:09.862  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 06:56:09.863  5621  5621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d445ec removed from the list
,09-26 06:56:09.863  5621  5621 D io.jxcore.node.ConnectivityMonitor: stop
09-26 06:56:09.864  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-26 06:56:09.864  5621  5621 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-26 06:56:09.880  5621  5984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-26 06:56:09.896  5621  5621 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@bddef39 that was originally registered here. Are you missing a call to unregisterReceiver()?
09-26 06:56:09.896  5621  5621 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@bddef39 that was originally registered here. Are you missing a call to unregisterReceiver()?
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:918)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:719)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1172)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1152)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1146)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:554)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:98)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:81)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:56:09.896  5621  5621 E ActivityThread: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-26 06:56:09.900  5621  5621 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@c54bc4a that was originally registered here. Are you missing a call to unregisterReceiver()?
09-26 06:56:09.900  5621  5621 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@c54bc4a that was originally registered here. Are you missing a call to unregisterReceiver()?
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:918)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:719)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1172)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1152)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1146)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:456)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:290)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:98)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:89)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:56:09.900  5621  5621 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-26 06:56:09.919  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.919  5621  5667 I jxcore-log: 
,09-26 06:56:09.920  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.920  5621  5667 I jxcore-log: 
,09-26 06:56:09.921  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.921  5621  5667 I jxcore-log: 
09-26 06:56:09.921  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.921  5621  5667 I jxcore-log: 
09-26 06:56:09.922  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.922  5621  5667 I jxcore-log: 
09-26 06:56:09.922  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.922  5621  5667 I jxcore-log: 
,09-26 06:56:09.933  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.933  5621  5667 I jxcore-log: 
,09-26 06:56:09.935  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.935  5621  5667 I jxcore-log: 
,09-26 06:56:09.936  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.936  5621  5667 I jxcore-log: 
,09-26 06:56:09.938  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.938  5621  5667 I jxcore-log: 
,09-26 06:56:09.939  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.939  5621  5667 I jxcore-log: 
09-26 06:56:09.939  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.939  5621  5667 I jxcore-log: 
,09-26 06:56:09.940  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.940  5621  5667 I jxcore-log: 
,09-26 06:56:09.953  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.953  5621  5667 I jxcore-log: 
,09-26 06:56:09.954  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.954  5621  5667 I jxcore-log: 
09-26 06:56:09.954  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.954  5621  5667 I jxcore-log: 
09-26 06:56:09.955  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.955  5621  5667 I jxcore-log: 
09-26 06:56:09.955  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.955  5621  5667 I jxcore-log: 
09-26 06:56:09.955  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.955  5621  5667 I jxcore-log: 
09-26 06:56:09.956  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.956  5621  5667 I jxcore-log: 
,09-26 06:56:09.957  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.957  5621  5667 I jxcore-log: 
,09-26 06:56:09.958  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.958  5621  5667 I jxcore-log: 
,09-26 06:56:09.961  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.961  5621  5667 I jxcore-log: 
,09-26 06:56:09.963  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.963  5621  5667 I jxcore-log: 
,09-26 06:56:09.967  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 06:56:09.967  5621  5667 I jxcore-log: 
,09-26 06:56:09.969  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.969  5621  5667 I jxcore-log: 
,09-26 06:56:09.970  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.970  5621  5667 I jxcore-log: 
09-26 06:56:09.970  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 06:56:09.970  5621  5667 I jxcore-log: 
,09-26 06:56:09.975  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.975  5621  5667 I jxcore-log: 
,09-26 06:56:09.977  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.977  5621  5667 I jxcore-log: 
,09-26 06:56:09.977  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.977  5621  5667 I jxcore-log: 
09-26 06:56:09.978  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.978  5621  5667 I jxcore-log: 
09-26 06:56:09.978  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 06:56:09.978  5621  5667 I jxcore-log: 
09-26 06:56:09.979  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.979  5621  5667 I jxcore-log: 
09-26 06:56:09.979  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-26 06:56:09.979  5621  5667 I jxcore-log: 
,09-26 06:56:09.985  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.985  5621  5667 I jxcore-log: 
,09-26 06:56:09.986  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 06:56:09.986  5621  5667 I jxcore-log: 
09-26 06:56:09.986  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 06:56:09.986  5621  5667 I jxcore-log: 
,09-26 06:56:09.989  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 06:56:09.989  5621  5667 I jxcore-log: 
,09-26 06:56:09.990  5621  5667 I jxcore-log: 2016-09-26 10:56:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 06:56:09.990  5621  5667 I jxcore-log: 
,09-26 06:56:10.000  5621  5667 I jxcore-log: 2016-09-26 10:56:10 - WARN testUtils: 'myNameCallback not set!'
09-26 06:56:10.000  5621  5667 I jxcore-log: 
,09-26 06:56:10.324  5987  5987 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-26 06:56:10.339  5987  5987 D AndroidRuntime: CheckJNI is OFF
,09-26 06:56:10.362  5987  5987 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-26 06:56:10.387  5987  5987 I Radio-JNI: register_android_hardware_Radio DONE
,09-26 06:56:10.403  5987  5987 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-26 06:56:10.410   933   946 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-26 06:56:10.410   933   946 I ActivityManager: Killing 5621:com.test.thalitest/u0a77 (adj 9): stop com.test.thalitest
,09-26 06:56:10.479   933   943 D GraphicsStats: Buffer count: 2
,09-26 06:56:10.480   933  2962 D WifiService: Client connection lost with reason: 4
,09-26 06:56:10.491   933  3115 W ActivityManager: Spurious death for ProcessRecord{26f5589 0:com.test.thalitest/u0a77}, curProc for 5621: null
,09-26 06:56:10.524   933   956 I art     : Starting a blocking GC Explicit
,09-26 06:56:10.623   933   956 I art     : Explicit concurrent mark sweep GC freed 55817(3MB) AllocSpace objects, 17(656KB) LOS objects, 33% free, 28MB/43MB, paused 1.995ms total 98.773ms
,09-26 06:56:10.642   933   956 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-26 06:56:10.644  5987  5987 I art     : System.exit called, status: 0
,09-26 06:56:10.645  5987  5987 I AndroidRuntime: VM exiting with result code 0.
,09-26 06:56:10.661   933   956 I ActivityManager: Start proc 5997:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-26 06:56:10.662   933   956 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-26 06:56:10.684  3671  3671 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-26 06:56:10.685  5887  5887 D BluetoothMapAppObserver: onReceive
,09-26 06:56:10.685  5887  5887 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-26 06:56:10.686   933  2951 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-26 06:56:10.686  4090  4180 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-26 06:56:10.698  3671  6009 I Keyboard.Facilitator.DecoderInitializer: run()
,09-26 06:56:10.718  3671  6009 I Decoder : createOrResetDecoder
,09-26 06:56:10.727  3383  6012 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-26 06:56:10.731    13    13 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 06:56:10.735   933   933 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-26 06:56:10.739  3794  3794 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-26 06:56:10.735    13    13 W kworker/1:0: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 06:56:10.745    13    13 W kworker/1:0: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-26 06:56:10.756   933   945 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-26 06:56:10.757   933   945 E PackageManager: Failed to write settings, restoring backup
09-26 06:56:10.757   933   945 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-26 06:56:10.757   933   945 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-26 06:56:10.757   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-26 06:56:10.757   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-26 06:56:10.757   933   945 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-26 06:56:10.757   933   945 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:56:10.757   933   945 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:56:10.757   933   945 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-26 06:56:10.761   933   946 E DropBoxManagerService: Can't write: system_server_wtf
09-26 06:56:10.761   933   946 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-26 06:56:10.761   933   946 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 06:56:10.761   933   946 E DropBoxManagerService: 	... 13 more
,09-26 06:56:10.761  3570  3570 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-26 06:56:10.762  3570  3570 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-26 06:56:10.762  3570  3570 E AndroidRuntime: FATAL EXCEPTION: main
09-26 06:56:10.762  3570  3570 E AndroidRuntime: Process: com.google.process.gapps, PID: 3570
09-26 06:56:10.762  3570  3570 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-26 06:56:10.762  3570  3570 E AndroidRuntime: 	... 8 more
,09-26 06:56:10.769  3570  3570 I Process : Sending signal. PID: 3570 SIG: 9
09-26 06:56:10.772   933  6016 E DropBoxManagerService: Can't write: system_app_crash
09-26 06:56:10.772   933  6016 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 06:56:10.772   933  6016 E DropBoxManagerService: 	... 5 more
,09-26 06:56:10.779  3826  3917 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-26 06:56:10.782   933  3397 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1868)
,09-26 06:56:10.782   933  3397 W ActivityManager: Application dead when creating service ServiceRecord{bac8f13 u0 com.google.android.gms/.config.ConfigService}
,09-26 06:56:10.784  3383  3406 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjBB17409CA) - 
,09-26 06:56:10.807  3383  6012 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-26 06:56:10.807  3383  6012 I Process : Sending signal. PID: 3383 SIG: 9
,09-26 06:56:10.811   933  2962 D WifiService: Client connection lost with reason: 4
,09-26 06:56:10.813   933  3397 I ActivityManager: Process com.google.process.gapps (pid 3570) has died
,09-26 06:56:10.814   933  3397 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-26 06:56:10.814   933  3397 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
09-26 06:56:10.814   933  3397 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
09-26 06:56:10.814   933  3397 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 30999ms
,09-26 06:56:10.815   933  3397 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 40998ms
,09-26 06:56:10.816   933  3397 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
09-26 06:56:10.816   933  3397 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-26 06:56:10.816   933  3397 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-26 06:56:10.816   933  3397 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-26 06:56:10.827   933  3586 I ActivityManager: Start proc 6017:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-26 06:56:10.828   933   944 W ActivityManager: Spurious death for ProcessRecord{c4dfa08 0:com.google.process.gapps/u0a12}, curProc for 3570: null
09-26 06:56:10.828  3826  3917 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-26 06:56:10.828  3826  3917 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3826
09-26 06:56:10.828  3826  3917 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-26 06:56:10.828  3826  3917 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-26 06:56:10.830   933  3882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-26 06:56:10.831   933  6024 E DropBoxManagerService: Can't write: system_app_crash
09-26 06:56:10.831   933  6024 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 06:56:10.831   933  6024 E DropBoxManagerService: 	... 5 more
,09-26 06:56:10.836  3826  3917 I Process : Sending signal. PID: 3826 SIG: 9
,09-26 06:56:10.863   933  3882 I ActivityManager: Start proc 6031:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-26 06:56:10.897   933  3115 I WindowState: WIN DEATH: Window{ca84ed1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-26 06:56:10.898   933  3882 D GraphicsStats: Buffer count: 1
,09-26 06:56:10.903   933   944 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3826) has died
,09-26 06:56:10.903   933   944 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-26 06:56:10.908   933   944 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-26 06:56:10.923   933   946 I ActivityManager: Start proc 6043:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-26 06:56:10.933   933  3847 I ActivityManager: Process android.process.acore (pid 3383) has died
,09-26 06:56:10.933   933  3847 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-26 06:56:11.134   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
