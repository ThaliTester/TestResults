#### Test 861725257abfc13_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 11:35:56.265   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-21 11:35:57.694  5488  5488 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 11:35:57.700  5488  5488 D AndroidRuntime: CheckJNI is OFF
09-21 11:35:57.725  5488  5488 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 11:35:57.755  5488  5488 I Radio-JNI: register_android_hardware_Radio DONE
09-21 11:35:57.770  5488  5488 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 11:35:57.774   933  3177 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 11:35:57.813   933  3177 I ActivityManager: Start proc 5497:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 11:35:57.817  5488  5488 D AndroidRuntime: Shutting down VM
,09-21 11:35:58.155   933  3151 I WindowManager: Screenshot max retries 4 of Token{8c6a371 ActivityRecord{587dd18 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{2f13730 u0 Starting com.test.thalitest} drawState=2
,09-21 11:35:58.222  5497  5497 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-21 11:35:58.253  5497  5497 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 11:35:58.279  5497  5497 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 5428-5448)
,09-21 11:35:58.280  5497  5497 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 11:35:58.301  5497  5497 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21b3e84}
,09-21 11:35:58.301  5497  5497 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 11:35:58.302  5497  5497 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 11:35:58.307  5497  5497 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 11:35:58.309  5497  5497 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 11:35:58.343  5497  5497 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 11:35:58.361  5497  5497 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 11:35:58.361  5497  5497 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 11:35:58.361  5497  5497 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 11:35:58.361  5497  5497 I Adreno  : Build Date                       : 12/06/15
09-21 11:35:58.361  5497  5497 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 11:35:58.361  5497  5497 I Adreno  : Local Branch                     : mybranch17112971
09-21 11:35:58.361  5497  5497 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 11:35:58.361  5497  5497 I Adreno  : Remote Branch                    : NONE
09-21 11:35:58.361  5497  5497 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 11:35:58.408   933   950 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@80e26c7:true
,09-21 11:35:58.442   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25365]" dev="sockfs" ino=25365 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:35:58.442   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25365]" dev="sockfs" ino=25365 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:35:58.456  5497  5497 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 11:35:58.464  5497  5497 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 11:35:58.486   754   754 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33365]" dev="sockfs" ino=33365 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 11:35:58.486   754   754 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33365]" dev="sockfs" ino=33365 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-21 11:35:58.488  5497  5534 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 11:35:58.489  3431  3431 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[27778]" dev="sockfs" ino=27778 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 11:35:58.489  3431  3431 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[27778]" dev="sockfs" ino=27778 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 11:35:58.494  5497  5521 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 11:35:58.527  5497  5534 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 11:35:58.600   933   951 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +443ms (total +814ms)
,09-21 11:35:58.630  5497  5497 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5497
,09-21 11:35:58.717  5497  5497 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 11:35:58.826  5497  5537 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -584316624
,09-21 11:35:58.830  5497  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 11:35:58.830  5497  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 11:35:58.830  5497  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 11:35:58.830  5497  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 11:35:58.830  5497  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 11:35:58.830  5497  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f196fe5 added. We now have 1 listener(s)
,09-21 11:35:58.832  5497  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-21 11:35:58.832  5497  5537 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:35:58.833  5497  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:35:58.833  5497  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 11:35:58.835  5497  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fd70c8 added. We now have 1 listener(s)
09-21 11:35:58.835  5497  5537 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:35:58.840   933  3001 D WifiService: New client listening to asynchronous messages
,09-21 11:35:58.840  5497  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 11:35:58.840  5497  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 11:35:58.840  5497  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 11:35:58.840  5497  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 11:35:58.840  5497  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-21 11:35:58.842  5497  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:35:58.842  5497  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 11:35:58.846  5497  5537 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:35:58.847  5497  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:35:58.847  5497  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-21 11:35:58.847  5497  5537 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:35:58.847  5497  5537 I io.jxcore.node.LifeCycleMonitor: start: OK
09-21 11:35:58.851  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:35:58.855  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:35:58.871  5497  5497 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 11:35:59.179  5497  5543 W jxcore-log: Initializing JXcore engine
09-21 11:35:59.180  5497  5543 W jxcore-log: JXcore engine is ready
,09-21 11:35:59.202  5543  5543 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12391 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-21 11:35:59.202  5543  5543 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13358]" dev="sockfs" ino=13358 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-21 11:35:59.202  5543  5543 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 11:35:59.202  5543  5543 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33342]" dev="sockfs" ino=33342 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 11:35:59.210  5497  5543 W jxcore-log: Starting JXcore engine
,09-21 11:35:59.259  5497  5543 W jxcore-log: Platform android
09-21 11:35:59.259  5497  5543 W jxcore-log: 
,09-21 11:35:59.259  5497  5543 W jxcore-log: Process ARCH arm
09-21 11:35:59.259  5497  5543 W jxcore-log: 
,09-21 11:35:59.357  5497  5543 I jxcore-log: JXcore Cordova bridge is ready!
09-21 11:35:59.357  5497  5543 I jxcore-log: 
,09-21 11:35:59.357  5497  5543 W jxcore-log: JXcore engine is started
,09-21 11:35:59.365  5497  5537 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 11:35:59.371  5497  5497 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 11:36:03.125   933  2994 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-21 11:36:09.212  5497  5543 I jxcore-log: 2016-09-21 15:36:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-21 11:36:09.212  5497  5543 I jxcore-log: 
,09-21 11:36:09.214  5497  5543 I jxcore-log: 2016-09-21 15:36:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-21 11:36:09.214  5497  5543 I jxcore-log: 
,09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:36:09.218  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:36:09.219  5497  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 11:36:09.221  5497  5543 I jxcore-log: 2016-09-21 15:36:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-21 11:36:09.221  5497  5543 I jxcore-log: 
,09-21 11:36:09.223  5497  5543 I jxcore-log: 2016-09-21 15:36:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-21 11:36:09.223  5497  5543 I jxcore-log: 
,09-21 11:36:09.480  5497  5543 I jxcore-log: Running unit tests
09-21 11:36:09.480  5497  5543 I jxcore-log: 
,09-21 11:36:09.481  5497  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:36:09.481  5497  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0038f0 added. We now have 2 listener(s)
,09-21 11:36:09.481  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:36:09.482  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:36:09.482  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:36:09.482  5497  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:36:09.482  5497  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4118e69 added. We now have 2 listener(s)
09-21 11:36:09.482  5497  5543 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:36:09.482  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 11:36:09.484  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:36:09.487  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:36:09.488  5497  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 11:36:09.488  5497  5543 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:36:09.489  5497  5543 D executeNativeTests: Running unit tests
,09-21 11:36:09.496  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:36:09.501  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:36:09.525  5497  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 11:36:09.525  5497  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351147f added. We now have 3 listener(s)
,09-21 11:36:09.526  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:36:09.526  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 11:36:09.526  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 11:36:09.526  5497  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:36:09.526  5497  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c added. We now have 3 listener(s)
,09-21 11:36:09.526  5497  5543 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:36:09.527  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 11:36:09.528  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:36:09.530  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:36:09.531  5497  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:09.532  5497  5543 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:36:09.533  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-21 11:36:09.533  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-21 11:36:09.533  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-21 11:36:09.533  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 11:36:09.534  5497  5543 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-21 11:36:09.534  5497  5543 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 11:36:09.534  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 11:36:09.534  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 11:36:09.534  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 11:36:09.534  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-21 11:36:09.534  5497  5543 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:36:09.534  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:36:09.535  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:36:09.535  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:36:09.535  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 11:36:09.535  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:36:09.535  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:36:09.535  5497  5543 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351147f removed from the list
09-21 11:36:09.535  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:09.535  5497  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c removed from the list
,09-21 11:36:09.546  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:36:09.551  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:36:09.551  5497  5543 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:36:09.551  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.552  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.552  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.552  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 11:36:09.552  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:36:09.552  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:09.552  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
09-21 11:36:09.553  5497  5543 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 11:36:09.553  5497  5543 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:36:09.553  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:36:09.554  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 11:36:09.554  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:36:09.554  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.554  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.554  5497  5543 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351147f not in the list
09-21 11:36:09.554  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-21 11:36:09.554  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
09-21 11:36:09.554  5497  5543 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:36:09.554  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.554  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:36:09.554  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.554  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.554  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:36:09.554  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:36:09.554  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:09.555  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
,09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 11:36:09.557  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 11:36:09.558  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-21 11:36:09.558  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 11:36:09.558  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 11:36:09.558  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 11:36:09.558  5497  5543 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 11:36:09.558  5497  5543 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:36:09.558  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-21 11:36:09.558  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:36:09.558  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:36:09.558  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.558  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.558  5497  5543 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351147f not in the list
09-21 11:36:09.558  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:09.558  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
09-21 11:36:09.558  5497  5543 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:36:09.558  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.558  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.558  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:09.558  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:36:09.559  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:36:09.559  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:36:09.559  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:09.559  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
09-21 11:36:09.559  5497  5543 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 11:36:09.560  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:36:09.562  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:36:09.563  5497  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:09.563  5497  5543 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:36:09.563  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:36:09.563  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: ,Start operation: Should affect listening to advertisements only
09-21 11:36:09.563  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:36:09.563  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:09.563  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:36:09.566  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:36:09.567  5497  5543 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:36:09.568  5497  5543 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 11:36:09.569  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:36:09.571  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 11:36:09.572  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:36:09.572  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 11:36:09.573  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-21 11:36:09.575  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-21 11:36:09.575  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 11:36:09.575  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:36:09.575  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:36:09.576  5497  5543 D BluetoothAdapter: STATE_ON
09-21 11:36:09.578  4420  4435 D BtGatt.GattService: registerClient() - UUID=ae982c45-bf8b-4ac6-b159-7f680f09c819
09-21 11:36:09.579  4420  4487 D BtGatt.GattService: onClientRegistered() - UUID=ae982c45-bf8b-4ac6-b159-7f680f09c819, clientIf=5
09-21 11:36:09.582  5497  5507 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 11:36:09.583  4420  4637 D BtGatt.GattService: start scan with filters
09-21 11:36:09.587  4420  4492 D BtGatt.ScanManager: handling starting scan
09-21 11:36:09.587  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:36:09.587  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:36:09.587  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:36:09.587  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 11:36:09.588  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:36:09.588  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:36:09.588  5497  5497 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:36:09.589  4420  4492 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bce678f
09-21 11:36:09.589  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 11:36:09.590  5497  5543 I io.jxcore.node.ConnectionHelper: start: OK
09-21 11:36:09.596  4420  4487 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:36:09.596  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:09.597  4420  4492 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:36:09.604  4420  4487 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 11:36:09.605  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:09.605  4420  4492 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:36:09.605  4420  4492 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:36:09.617  4420  4487 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 11:36:09.617  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:09.624  4420  4487 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:36:09.624  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:36:09.803   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-21 11:36:10.090  5497  5497 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-21 11:36:10.091  5497  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:36:10.091  5497  5497 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 11:36:12.835   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-21 11:36:12.841   933  3002 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-21 11:36:14.594  5497  5543 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 11:36:14.594  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:36:14.594  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 11:36:14.594  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:14.595  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-21 11:36:14.595  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-21 11:36:14.595  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:36:14.595  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 11:36:14.595  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:36:14.596  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-21 11:36:14.596  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-21 11:36:14.597  5497  5543 D BluetoothAdapter: STATE_ON
,09-21 11:36:14.598  4420  4435 D BtGatt.GattService: stopScan() - queue size =1
09-21 11:36:14.599  4420  4637 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:36:14.601  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:36:14.601  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-21 11:36:14.601  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 11:36:14.601  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:36:14.601  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 11:36:14.603  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 11:36:14.603  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:36:14.603  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:36:14.603  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:36:14.604  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:36:14.606  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:36:14.606  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:14.606  5497  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:36:14.606  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:36:14.606  4420  4420 D BtGatt.ScanManager: awakened up at time 211775
09-21 11:36:14.606  5497  5543 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351147f not in the list
09-21 11:36:14.606  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:36:14.606  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:14.606  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
09-21 11:36:14.606  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:36:14.607  5497  5543 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:36:14.607  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:36:14.614  4420  4487 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-21 11:36:14.614  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:14.615  4420  4492 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:36:14.617  5497  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:36:14.617  5497  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 11:36:14.626  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 11:36:14.627  4420  4487 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:36:14.627  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:14.627  4420  4492 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 11:36:14.628  5497  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:36:14.628  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 11:36:14.629  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-21 11:36:14.630  5497  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:36:14.635  5497  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 11:36:14.635  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:14.635  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:36:14.639  5497  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 11:36:14.639  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:36:14.640  5497  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:36:14.645  5497  5497 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 11:36:14.661  4420  4487 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-21 11:36:14.661  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:14.661  4420  4487 D BtGatt.GattService: current time is 211830621442
09-21 11:36:14.662  4420  4487 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -76, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -76, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -82, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -75, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -52, 11, 57, -70, 107, -17, 1, 0, -99, 34, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 81, 34, 97, 112, -14, -5, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-21 11:36:14.663  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-21 11:36:14.665  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-21 11:36:14.665  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-21 11:36:14.665  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-21 11:36:14.665  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-21 11:36:14.666  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-21 11:36:14.666  4420  4487 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-21 11:36:15.145  5497  5497 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 11:36:15.871   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-21 11:36:15.877   933  3002 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-21 11:36:19.611  5497  5543 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-21 11:36:19.617  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:36:19.628  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:36:19.634  5497  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 11:36:19.634  5497  5543 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:36:19.635  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-21 11:36:19.635  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 11:36:19.635  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:36:19.635  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:19.635  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 11:36:19.639  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:36:19.641  5497  5543 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 11:36:19.645  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:36:19.647  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 11:36:19.647  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:36:19.648  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:36:19.649  5497  5543 D BluetoothAdapter: STATE_ON
,09-21 11:36:19.652  4420  4433 D BtGatt.GattService: registerClient() - UUID=5c1de284-41e5-45e7-a0f2-5441d6930062
,09-21 11:36:19.653  4420  4487 D BtGatt.GattService: onClientRegistered() - UUID=5c1de284-41e5-45e7-a0f2-5441d6930062, clientIf=5
09-21 11:36:19.653  5497  5507 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 11:36:19.654  4420  4435 D BtGatt.GattService: start scan with filters
,09-21 11:36:19.662  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-21 11:36:19.663  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:36:19.663  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:36:19.663  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 11:36:19.663  4420  4492 D BtGatt.ScanManager: handling starting scan
09-21 11:36:19.666  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:36:19.666  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:36:19.667  5497  5497 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:36:19.669  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 11:36:19.673  5497  5543 I io.jxcore.node.ConnectionHelper: start: OK
09-21 11:36:19.674  4420  4487 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:36:19.674  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:19.674  4420  4492 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:36:19.675  5497  5543 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:36:19.675  5497  5543 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 11:36:19.675  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:36:19.675  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 11:36:19.676  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:19.676  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 11:36:19.676  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 11:36:19.676  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-21 11:36:19.676  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 11:36:19.676  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:36:19.676  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:36:19.676  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 11:36:19.677  5497  5543 D BluetoothAdapter: STATE_ON
09-21 11:36:19.677  4420  4433 D BtGatt.GattService: stopScan() - queue size =1
09-21 11:36:19.678  4420  4435 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:36:19.678  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:36:19.679  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:36:19.679  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 11:36:19.679  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:36:19.679  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 11:36:19.681  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:36:19.681  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:36:19.681  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:36:19.681  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:36:19.682  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:36:19.682  4420  4487 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-21 11:36:19.682  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:19.682  4420  4492 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:36:19.682  4420  4492 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:36:19.683  5497  5543 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:36:19.683  5497  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:36:19.683  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:19.683  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:36:19.683  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:19.683  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-21 11:36:19.683  5497  5543 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@351147f not in the list
09-21 11:36:19.683  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:19.683  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
09-21 11:36:19.683  5497  5543 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:36:19.683  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-21 11:36:19.692  5497  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:36:19.693  5497  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 11:36:19.696  4420  4487 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 11:36:19.696  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:36:19.698  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 11:36:19.699  5497  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-21 11:36:19.699  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-21 11:36:19.699  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:36:19.700  5497  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:36:19.702  5497  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-21 11:36:19.702  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:19.703  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:36:19.703  4420  4487 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:36:19.703  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:36:19.706  5497  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 11:36:19.706  5497  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:36:19.707  5497  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:36:19.709  5497  5543 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:36:19.709  5497  5497 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 11:36:19.710  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:36:19.711  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:36:19.711  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:36:19.711  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:36:19.711  4420  4487 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:36:19.711  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:19.711  4420  4492 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:36:19.711  5497  5543 D BluetoothAdapter: STATE_ON
09-21 11:36:19.712  5497  5543 D BluetoothLeScanner: could not find callback wrapper
09-21 11:36:19.712  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:36:19.712  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:36:19.712  5497  5543 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fe9c4c not in the list
,09-21 11:36:19.712  5497  5543 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 11:36:19.714  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:36:19.717  4420  4487 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:36:19.717  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:19.717  4420  4492 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:36:19.718  5497  5543 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:36:19.720  5497  5543 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:36:19.720  5497  5543 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:36:19.720  5497  5543 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:36:19.720  5497  5543 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-21 11:36:19.720  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:36:19.720  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:36:19.720  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:36:19.723  4420  4487 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 11:36:19.723  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:19.723  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:36:19.725  5497  5543 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:36:19.725  5497  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:36:19.728  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 11:36:19.728  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:36:19.728  5497  5543 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:36:19.729  5497  5543 D BluetoothAdapter: STATE_ON
09-21 11:36:19.730  4420  4637 D BtGatt.GattService: registerClient() - UUID=53668a95-2498-4e40-83d6-527b0d68c817
09-21 11:36:19.731  4420  4487 D BtGatt.GattService: onClientRegistered() - UUID=53668a95-2498-4e40-83d6-527b0d68c817, clientIf=5
09-21 11:36:19.731  5497  5507 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 11:36:19.732  4420  4645 D BtGatt.GattService: start scan with filters
,09-21 11:36:19.734  4420  4492 D BtGatt.ScanManager: handling starting scan
09-21 11:36:19.734  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:36:19.735  5497  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-21 11:36:19.735  5497  5543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:36:19.735  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 11:36:19.737  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 11:36:19.737  5497  5543 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:36:19.737  5497  5497 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:36:19.739  5497  5543 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 11:36:19.741  5497  5543 I io.jxcore.node.ConnectionHelper: start: OK
09-21 11:36:19.741  4420  4487 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:36:19.741  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:36:19.742  4420  4492 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:36:19.747  4420  4487 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-21 11:36:19.747  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:36:19.747  4420  4492 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:36:19.747  4420  4492 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-21 11:36:19.757  4420  4487 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-21 11:36:19.757  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:36:19.762  4420  4487 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:36:19.762  4420  4487 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:36:20.239  5497  5497 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-21 11:36:20.239  5497  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:36:20.239  5497  5497 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-21 11:36:21.266   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-21 11:36:21.266   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-21 11:36:21.918   933  3002 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-21 11:36:21.921   933  3002 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55

```
