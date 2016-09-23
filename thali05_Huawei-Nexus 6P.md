#### Test 863677671df66b8_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 08:35:19.900   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-23 08:35:19.900   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 08:35:20.371  5444  5444 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 08:35:20.377  5444  5444 D AndroidRuntime: CheckJNI is OFF
09-23 08:35:20.405  5444  5444 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 08:35:20.441  5444  5444 I Radio-JNI: register_android_hardware_Radio DONE
09-23 08:35:20.458  5444  5444 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 08:35:20.463   929  3434 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 08:35:20.509   929  3434 I ActivityManager: Start proc 5453:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 08:35:20.520  5444  5444 D AndroidRuntime: Shutting down VM
,09-23 08:35:20.855   929   940 I WindowManager: Screenshot max retries 4 of Token{7d52cd8 ActivityRecord{bd49fbb u0 com.test.thalitest/.MainActivity t2}} appWin=Window{4194b33 u0 Starting com.test.thalitest} drawState=4
,09-23 08:35:20.930  5453  5453 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 08:35:20.964  5453  5453 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 08:35:20.986  5453  5453 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 9751-9769)
,09-23 08:35:20.986  5453  5453 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 08:35:21.004  5453  5453 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8cbd396}
,09-23 08:35:21.005  5453  5453 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 08:35:21.005  5453  5453 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 08:35:21.009  5453  5453 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 08:35:21.010  5453  5453 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 08:35:21.054  5453  5453 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 08:35:21.069  5453  5453 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 08:35:21.069  5453  5453 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 08:35:21.069  5453  5453 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 08:35:21.069  5453  5453 I Adreno  : Build Date                       : 12/06/15
09-23 08:35:21.069  5453  5453 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 08:35:21.069  5453  5453 I Adreno  : Local Branch                     : mybranch17112971
09-23 08:35:21.069  5453  5453 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 08:35:21.069  5453  5453 I Adreno  : Remote Branch                    : NONE
09-23 08:35:21.069  5453  5453 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 08:35:21.117   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@abcc5c6:true
,09-23 08:35:21.152   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27506]" dev="sockfs" ino=27506 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 08:35:21.152   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[27506]" dev="sockfs" ino=27506 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 08:35:21.174  5453  5453 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 08:35:21.190  5453  5453 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 08:35:21.219  5453  5491 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 08:35:21.216   495   495 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32606]" dev="sockfs" ino=32606 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 08:35:21.216   495   495 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32606]" dev="sockfs" ino=32606 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 08:35:21.219  3116  3116 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28863]" dev="sockfs" ino=28863 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 08:35:21.222  3116  3116 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28863]" dev="sockfs" ino=28863 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 08:35:21.226  5453  5477 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 08:35:21.251  5453  5491 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 08:35:21.328   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +471ms (total +846ms)
,09-23 08:35:21.351  5453  5453 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5453
,09-23 08:35:21.437  5453  5453 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 08:35:21.561  5453  5494 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -583792336
,09-23 08:35:21.565  5453  5494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 08:35:21.565  5453  5494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 08:35:21.565  5453  5494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 08:35:21.565  5453  5494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 08:35:21.565  5453  5494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 08:35:21.565  5453  5494 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf809cf added. We now have 1 listener(s)
,09-23 08:35:21.567  5453  5494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-23 08:35:21.568  5453  5494 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 08:35:21.568  5453  5494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 08:35:21.568  5453  5494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 08:35:21.572  5453  5494 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aa1b3a added. We now have 1 listener(s)
09-23 08:35:21.572  5453  5494 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 08:35:21.576   929  2967 D WifiService: New client listening to asynchronous messages
,09-23 08:35:21.577  5453  5494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 08:35:21.577  5453  5494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 08:35:21.577  5453  5494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-23 08:35:21.577  5453  5494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 08:35:21.577  5453  5494 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 08:35:21.579  5453  5494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 08:35:21.579  5453  5494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 08:35:21.583  5453  5494 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:35:21.583  5453  5494 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 08:35:21.583  5453  5494 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 08:35:21.583  5453  5494 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 08:35:21.583  5453  5494 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 08:35:21.585  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:35:21.589  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:35:21.718  5453  5453 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 08:35:21.896  5453  5499 W jxcore-log: Initializing JXcore engine
,09-23 08:35:21.896  5453  5499 W jxcore-log: JXcore engine is ready
,09-23 08:35:21.919  5499  5499 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11563 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 08:35:21.919  5499  5499 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16408]" dev="sockfs" ino=16408 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 08:35:21.919  5499  5499 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 08:35:21.919  5499  5499 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31446]" dev="sockfs" ino=31446 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 08:35:21.933  5453  5499 W jxcore-log: Starting JXcore engine
,09-23 08:35:22.004  5453  5499 W jxcore-log: Platform android
09-23 08:35:22.004  5453  5499 W jxcore-log: 
,09-23 08:35:22.004  5453  5499 W jxcore-log: Process ARCH arm
09-23 08:35:22.004  5453  5499 W jxcore-log: 
,09-23 08:35:22.101  5453  5499 I jxcore-log: JXcore Cordova bridge is ready!
09-23 08:35:22.101  5453  5499 I jxcore-log: 
,09-23 08:35:22.101  5453  5499 W jxcore-log: JXcore engine is started
,09-23 08:35:22.120  5453  5494 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 08:35:22.126  5453  5453 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 08:35:22.399   929  2966 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 08:35:29.901   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 08:35:30.903   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 08:35:31.703  5453  5499 I jxcore-log: 2016-09-23 12:35:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 08:35:31.703  5453  5499 I jxcore-log: 
,09-23 08:35:31.705  5453  5499 I jxcore-log: 2016-09-23 12:35:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 08:35:31.705  5453  5499 I jxcore-log: 
,09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:35:31.709  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 08:35:31.710  5453  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 08:35:31.712  5453  5499 I jxcore-log: 2016-09-23 12:35:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 08:35:31.712  5453  5499 I jxcore-log: 
,09-23 08:35:31.714  5453  5499 I jxcore-log: 2016-09-23 12:35:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 08:35:31.714  5453  5499 I jxcore-log: 
,09-23 08:35:31.904   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 08:35:31.955  5453  5499 I jxcore-log: Running unit tests
09-23 08:35:31.955  5453  5499 I jxcore-log: 
,09-23 08:35:31.955  5453  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 08:35:31.956  5453  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@510fd17 added. We now have 2 listener(s)
,09-23 08:35:31.956  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 08:35:31.956  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 08:35:31.956  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 08:35:31.957  5453  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 08:35:31.957  5453  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c22f504 added. We now have 2 listener(s)
09-23 08:35:31.957  5453  5499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 08:35:31.957  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 08:35:31.959  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:35:31.962  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 08:35:31.963  5453  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:31.963  5453  5499 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 08:35:31.963  5453  5499 D executeNativeTests: Running unit tests
,09-23 08:35:31.970  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:35:31.975  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:35:32.003  5453  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 08:35:32.003  5453  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e4f2d2 added. We now have 3 listener(s)
09-23 08:35:32.003  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 08:35:32.004  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 08:35:32.004  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 08:35:32.004  5453  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 08:35:32.004  5453  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 added. We now have 3 listener(s)
,09-23 08:35:32.004  5453  5499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 08:35:32.004  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 08:35:32.006  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:35:32.009  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 08:35:32.011  5453  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 08:35:32.011  5453  5499 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 08:35:32.014  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-23 08:35:32.014  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 08:35:32.015  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 08:35:32.015  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 08:35:32.015  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 08:35:32.015  5453  5499 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-23 08:35:32.016  5453  5499 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-23 08:35:32.016  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 08:35:32.016  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 08:35:32.016  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 08:35:32.016  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 08:35:32.016  5453  5499 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 08:35:32.016  5453  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 08:35:32.016  5453  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 08:35:32.017  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 08:35:32.017  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:32.017  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 08:35:32.017  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 08:35:32.017  5453  5499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e4f2d2 removed from the list
,09-23 08:35:32.017  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 08:35:32.017  5453  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 removed from the list
09-23 08:35:32.018  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 08:35:32.018  5453  5499 D io.jxcore.node.ConnectivityMonitor: stop
09-23 08:35:32.018  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.019  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 08:35:32.019  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.019  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 08:35:32.019  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 08:35:32.019  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 08:35:32.019  5453  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 not in the list
09-23 08:35:32.020  5453  5499 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-23 08:35:32.020  5453  5499 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 08:35:32.021  5453  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 08:35:32.021  5453  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 08:35:32.021  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 08:35:32.021  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:32.021  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 08:35:32.021  5453  5499 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e4f2d2 not in the list
09-23 08:35:32.021  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 08:35:32.021  5453  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 not in the list
09-23 08:35:32.021  5453  5499 D io.jxcore.node.ConnectivityMonitor: stop
09-23 08:35:32.021  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 08:35:32.021  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.021  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:32.021  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.021  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 08:35:32.021  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 08:35:32.021  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 08:35:32.022  5453  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 not in the list
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 08:35:32.024  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 08:35:32.025  5453  5499 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 08:35:32.025  5453  5499 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 08:35:32.025  5453  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 08:35:32.025  5453  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 08:35:32.025  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 08:35:32.025  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:32.026  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.026  5453  5499 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e4f2d2 not in the list
09-23 08:35:32.026  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 08:35:32.026  5453  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 not in the list
09-23 08:35:32.026  5453  5499 D io.jxcore.node.ConnectivityMonitor: stop
09-23 08:35:32.026  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:32.026  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.026  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:32.026  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:32.026  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 08:35:32.026  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 08:35:32.026  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 08:35:32.026  5453  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 not in the list
09-23 08:35:32.027  5453  5499 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 08:35:32.028  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 08:35:32.030  5453  5499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 08:35:32.030  5453  5499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 08:35:32.030  5453  5499 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 08:35:32.031  5453  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 08:35:32.031  5453  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 08:35:32.031  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 08:35:32.031  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 08:35:32.031  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 08:35:32.033  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 08:35:32.033  5453  5499 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 08:35:32.033  5453  5499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 08:35:32.035  5453  5453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 08:35:32.037  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 08:35:32.037  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 08:35:32.038  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 08:35:32.039  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-23 08:35:32.040  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 08:35:32.040  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 08:35:32.040  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 08:35:32.040  5453  5499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 08:35:32.040  5453  5499 D BluetoothAdapter: STATE_ON
,09-23 08:35:32.042  4472  4684 D BtGatt.GattService: registerClient() - UUID=6fb198ce-8f3d-4dc2-9dfb-d8850785861d
,09-23 08:35:32.043  4472  4535 D BtGatt.GattService: onClientRegistered() - UUID=6fb198ce-8f3d-4dc2-9dfb-d8850785861d, clientIf=5
,09-23 08:35:32.044  5453  5464 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 08:35:32.044  4472  4704 D BtGatt.GattService: start scan with filters
,09-23 08:35:32.048  4472  4539 D BtGatt.ScanManager: handling starting scan
,09-23 08:35:32.048  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 08:35:32.048  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 08:35:32.048  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 08:35:32.048  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 08:35:32.051  4472  4539 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5026e9
,09-23 08:35:32.054  5453  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 08:35:32.054  5453  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 08:35:32.055  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 08:35:32.055  5453  5453 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 08:35:32.057  5453  5499 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 08:35:32.058  4472  4535 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 08:35:32.059  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 08:35:32.059  4472  4539 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 08:35:32.064  4472  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 08:35:32.064  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 08:35:32.064  4472  4539 D BtGatt.ScanManager: Starting BLE batch scan
09-23 08:35:32.064  4472  4539 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 08:35:32.073  4472  4535 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 08:35:32.073  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 08:35:32.078  4472  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 08:35:32.078  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 08:35:32.557  5453  5453 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 08:35:32.557  5453  5453 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 08:35:32.557  5453  5453 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 08:35:32.905   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 08:35:33.140   929  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 08:35:33.144   929  2971 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-23 08:35:33.906   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 08:35:34.907   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 08:35:36.162   929  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 08:35:36.168   929  2971 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-23 08:35:37.061  5453  5499 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 08:35:37.062  5453  5499 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 08:35:37.062  5453  5499 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 08:35:37.062  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:37.062  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 08:35:37.062  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-23 08:35:37.062  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 08:35:37.062  5453  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 08:35:37.062  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 08:35:37.063  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 08:35:37.063  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-23 08:35:37.064  5453  5499 D BluetoothAdapter: STATE_ON
09-23 08:35:37.065  4472  4684 D BtGatt.GattService: stopScan() - queue size =1
09-23 08:35:37.066  4472  4704 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 08:35:37.067  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 08:35:37.067  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 08:35:37.067  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-23 08:35:37.067  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 08:35:37.067  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 08:35:37.068  5453  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 08:35:37.069  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 08:35:37.069  5453  5499 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 08:35:37.069  5453  5499 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 08:35:37.069  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 08:35:37.071  5453  5499 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 08:35:37.071  5453  5499 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 08:35:37.071  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 08:35:37.071  5453  5499 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e4f2d2 not in the list
09-23 08:35:37.071  5453  5453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 08:35:37.071  5453  5499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 08:35:37.071  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 08:35:37.071  5453  5499 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e38fa3 not in the list
09-23 08:35:37.071  5453  5499 D io.jxcore.node.ConnectivityMonitor: stop
09-23 08:35:37.071  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 08:35:37.072  5453  5499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 08:35:37.076  4472  4472 D BtGatt.ScanManager: awakened up at time 235859
,09-23 08:35:37.081  5453  5453 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 08:35:37.082  5453  5453 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 08:35:37.082  4472  4535 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 08:35:37.082  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 08:35:37.082  4472  4539 D BtGatt.ScanManager: stopping BLe Batch
,09-23 08:35:37.088  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 08:35:37.090  5453  5453 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 08:35:37.090  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 08:35:37.090  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 08:35:37.091  4472  4535 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 08:35:37.091  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 08:35:37.091  5453  5453 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 08:35:37.091  4472  4539 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 08:35:37.097  5453  5453 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 08:35:37.097  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 08:35:37.097  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 08:35:37.102  5453  5453 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 08:35:37.102  5453  5453 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 08:35:37.103  5453  5453 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 08:35:37.106  5453  5453 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 08:35:37.114  4472  4535 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-23 08:35:37.114  4472  4535 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 08:35:37.115  4472  4535 D BtGatt.GattService: current time is 235898114708
09-23 08:35:37.115  4472  4535 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -72, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -74, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -75, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 08:35:37.117  4472  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 08:35:37.118  4472  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 08:35:37.119  4472  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 08:35:37.119  4472  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 08:35:37.119  4472  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 08:35:37.120  4472  4535 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-23 08:35:37.607  5453  5453 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false

```
