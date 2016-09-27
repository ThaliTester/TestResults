#### Test 850469118f5d139_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 08:04:41.109   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-27 08:04:41.109   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 08:04:41.590  5589  5589 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 08:04:41.595  5589  5589 D AndroidRuntime: CheckJNI is OFF
09-27 08:04:41.618  5589  5589 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 08:04:41.652  5589  5589 I Radio-JNI: register_android_hardware_Radio DONE
09-27 08:04:41.667  5589  5589 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-27 08:04:41.676   926  3691 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 08:04:41.724   926  3691 I ActivityManager: Start proc 5598:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 08:04:41.729  5589  5589 D AndroidRuntime: Shutting down VM
,09-27 08:04:42.069   926  3734 I WindowManager: Screenshot max retries 4 of Token{1a43e2f ActivityRecord{950540e u0 com.test.thalitest/.MainActivity t2}} appWin=Window{bc6d6e6 u0 Starting com.test.thalitest} drawState=2
,09-27 08:04:42.132  5598  5598 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 08:04:42.168  5598  5598 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 08:04:42.193  5598  5598 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 705-725)
09-27 08:04:42.193  5598  5598 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 08:04:42.212  5598  5598 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cefa2a7}
,09-27 08:04:42.213  5598  5598 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 08:04:42.213  5598  5598 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-27 08:04:42.218  5598  5598 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-27 08:04:42.219  5598  5598 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 08:04:42.255  5598  5598 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 08:04:42.268  5598  5598 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-27 08:04:42.269  5598  5598 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 08:04:42.269  5598  5598 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 08:04:42.269  5598  5598 I Adreno  : Build Date                       : 12/06/15
09-27 08:04:42.269  5598  5598 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 08:04:42.269  5598  5598 I Adreno  : Local Branch                     : mybranch17112971
09-27 08:04:42.269  5598  5598 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 08:04:42.269  5598  5598 I Adreno  : Remote Branch                    : NONE
09-27 08:04:42.269  5598  5598 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 08:04:42.354   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@94cc235:true
,09-27 08:04:42.389   742   742 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33920]" dev="sockfs" ino=33920 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 08:04:42.389   742   742 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33920]" dev="sockfs" ino=33920 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 08:04:42.408  5598  5598 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 08:04:42.419  5598  5598 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 08:04:42.458  5598  5635 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-27 08:04:42.456  3147  3147 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30497]" dev="sockfs" ino=30497 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 08:04:42.456  3147  3147 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30497]" dev="sockfs" ino=30497 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 08:04:42.459  3384  3384 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15127]" dev="sockfs" ino=15127 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 08:04:42.459  3384  3384 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15127]" dev="sockfs" ino=15127 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 08:04:42.465  5598  5622 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 08:04:42.490  5598  5635 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 08:04:42.566   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +494ms (total +876ms)
,09-27 08:04:42.609  5598  5598 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5598
,09-27 08:04:42.705  5598  5598 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 08:04:42.850  5598  5637 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -583010000
,09-27 08:04:42.855  5598  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 08:04:42.855  5598  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 08:04:42.855  5598  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 08:04:42.855  5598  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 08:04:42.855  5598  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-27 08:04:42.855  5598  5637 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3231ac added. We now have 1 listener(s)
,09-27 08:04:42.857  5598  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 08:04:42.858  5598  5637 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 08:04:42.858  5598  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:04:42.859  5598  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-27 08:04:42.861  5598  5637 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f7967b added. We now have 1 listener(s)
,09-27 08:04:42.862  5598  5637 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:04:42.866   926  2950 D WifiService: New client listening to asynchronous messages
,09-27 08:04:42.867  5598  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:04:42.867  5598  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-27 08:04:42.867  5598  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 08:04:42.867  5598  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 08:04:42.867  5598  5637 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-27 08:04:42.869  5598  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:04:42.870  5598  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-27 08:04:42.875  5598  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:04:42.875  5598  5637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:04:42.875  5598  5637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 08:04:42.875  5598  5637 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:04:42.875  5598  5637 I io.jxcore.node.LifeCycleMonitor: start: OK
09-27 08:04:42.878  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:04:42.882  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:04:42.908  5598  5598 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 08:04:43.221  5598  5644 W jxcore-log: Initializing JXcore engine
09-27 08:04:43.221  5598  5644 W jxcore-log: JXcore engine is ready
,09-27 08:04:43.242  5644  5644 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11972 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-27 08:04:43.242  5644  5644 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14416]" dev="sockfs" ino=14416 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-27 08:04:43.242  5644  5644 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 08:04:43.242  5644  5644 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33175]" dev="sockfs" ino=33175 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 08:04:43.254  5598  5644 W jxcore-log: Starting JXcore engine
,09-27 08:04:43.312  5598  5644 W jxcore-log: Platform android
09-27 08:04:43.312  5598  5644 W jxcore-log: 
09-27 08:04:43.312  5598  5644 W jxcore-log: Process ARCH arm
09-27 08:04:43.312  5598  5644 W jxcore-log: 
,09-27 08:04:43.418  5598  5644 I jxcore-log: JXcore Cordova bridge is ready!
09-27 08:04:43.418  5598  5644 I jxcore-log: 
09-27 08:04:43.418  5598  5644 W jxcore-log: JXcore engine is started
,09-27 08:04:43.422  5598  5637 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 08:04:43.425  5598  5598 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 08:04:43.820   926  2949 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 08:04:50.452  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-27 08:04:50.452  5598  5644 I jxcore-log: 
,09-27 08:04:50.454  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-27 08:04:50.454  5598  5644 I jxcore-log: 
,09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:04:50.458  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:04:50.459  5598  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:04:50.461  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-27 08:04:50.461  5598  5644 I jxcore-log: 
,09-27 08:04:50.462  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-27 08:04:50.462  5598  5644 I jxcore-log: 
,09-27 08:04:50.701  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 08:04:50.701  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f98732 added. We now have 2 listener(s)
09-27 08:04:50.702  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 08:04:50.702  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:04:50.702  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 08:04:50.703  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:04:50.703  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51bfc83 added. We now have 2 listener(s)
09-27 08:04:50.703  5598  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:04:50.704  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:04:50.706  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:04:50.709  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:04:50.710  5598  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:04:50.710  5598  5644 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:04:50.710  5598  5644 D ExecuteNativeTests: Running unit tests
09-27 08:04:50.713  5598  5644 D BluetoothAdapter: enable(): BT is already enabled..!
,09-27 08:04:50.714   926  3384 D WifiService: setWifiEnabled: true pid=5598, uid=10077
09-27 08:04:50.715   926  3384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:04:50.716  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:04:50.722  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:04:51.111   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:04:52.112   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:04:53.114   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:04:54.115   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:04:54.558   926  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 08:04:55.117   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:04:56.118   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 08:04:57.607   926  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 08:05:00.721  5598  5644 I com.test.thalitest.ThaliTestRunner: Running UT
,09-27 08:05:00.791  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 08:05:00.791  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7ac41d added. We now have 3 listener(s)
09-27 08:05:00.792  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:00.792  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 08:05:00.792  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 08:05:00.792  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:05:00.792  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6748692 added. We now have 3 listener(s)
09-27 08:05:00.792  5598  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:05:00.793  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 08:05:00.796  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:05:00.800  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:05:00.801  5598  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:00.801  5598  5644 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:05:00.809  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:00.813  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-27 08:05:00.813  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 08:05:00.813  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:00.813  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 08:05:00.813  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:00.814  5598  5644 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-27 08:05:00.815  5598  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 08:05:00.815  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 08:05:00.815  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-27 08:05:00.815  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:00.815  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:00.815  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:00.816  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-27 08:05:00.817  5598  5644 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-27 08:05:00.818  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-27 08:05:00.819  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,09-27 08:05:00.819  5598  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 08:05:00.819  5598  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 08:05:00.820  5598  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-27 08:05:00.820  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-27 08:05:00.820  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:00.820  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 08:05:00.820  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:05:00.820  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:00.821  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 08:05:00.821  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:05:00.821  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-27 08:05:00.822  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-27 08:05:00.822  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 08:05:00.822  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:00.822  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:05:00.822  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-27 08:05:00.824  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:05:00.824  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:05:00.824  5598  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:00.826  5598  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 08:05:00.826  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:05:00.822  4576  4576 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33948]" dev="sockfs" ino=33948 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:05:00.827  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:05:00.827  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:05:00.822  4576  4576 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33948]" dev="sockfs" ino=33948 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:00.828  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 08:05:00.829  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:00.829  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-27 08:05:00.829  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:00.829  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:00.829  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 08:05:00.830  5598  5644 D BluetoothAdapter: STATE_ON
,09-27 08:05:00.833  4563  4578 D BtGatt.GattService: registerClient() - UUID=92da644c-451a-4f33-8923-615fd4708ffc
,09-27 08:05:00.833  4563  4650 D BtGatt.GattService: onClientRegistered() - UUID=92da644c-451a-4f33-8923-615fd4708ffc, clientIf=5
,09-27 08:05:00.834  5598  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 08:05:00.838  4563  4652 D BtGatt.AdvertiseManager: message : 0
,09-27 08:05:00.841  4563  4652 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 08:05:00.854  4563  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 08:05:00.860  4563  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 08:05:00.861  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 08:05:00.861  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 08:05:00.862  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 08:05:00.863  5598  5644 I io.jxcore.node.ConnectionHelper: start: OK
09-27 08:05:00.863  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:00.863  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-27 08:05:00.863  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:05:00.864  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 08:05:00.864  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 08:05:00.864  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 08:05:00.867  5598  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 08:05:00.867  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 08:05:01.119   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:01.366  5598  5644 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-27 08:05:01.367  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-27 08:05:01.368  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 08:05:01.369  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 08:05:01.369  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 08:05:01.369  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:05:01.369  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 08:05:01.370  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 08:05:01.370  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 08:05:01.370  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 08:05:01.370  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 08:05:01.370  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 08:05:01.370  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-27 08:05:01.371  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 08:05:01.371  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 08:05:01.371  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 08:05:01.371  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 08:05:01.371  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:05:01.372  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 08:05:01.372  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 08:05:01.372  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:05:01.372  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:05:01.372  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:05:01.372  5598  5646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:05:01.372  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 08:05:01.372  5598  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:05:01.373  5598  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:05:01.374  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:05:01.373  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 08:05:01.375  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:01.375  5598  5644 D BluetoothLeScanner: could not find callback wrapper
,09-27 08:05:01.375  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:05:01.375  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 08:05:01.376  4563  4652 D BtGatt.AdvertiseManager: message : 1
09-27 08:05:01.378  4563  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 08:05:01.390  4563  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 08:05:01.390  4563  4650 D BtGatt.GattService: Client app is not null!
09-27 08:05:01.392  4563  4807 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:05:01.392  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 08:05:01.393  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 08:05:01.393  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 08:05:01.393  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 08:05:01.393  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 08:05:01.395  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:01.395  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:05:01.395  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:05:01.396  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:05:01.399  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:05:01.399  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 08:05:01.399  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:01.399  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:01.399  5598  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 08:05:01.400  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:01.400  5598  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 08:05:01.401  5598  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 08:05:01.401  5598  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-27 08:05:01.401  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-27 08:05:01.409  4576  4576 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30513]" dev="sockfs" ino=30513 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:01.409  4576  4576 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30513]" dev="sockfs" ino=30513 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:05:01.401  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-27 08:05:01.401  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 08:05:01.401  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:05:01.402  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:01.403  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 08:05:01.403  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:05:01.403  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-27 08:05:01.404  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:05:01.404  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 08:05:01.404  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:01.404  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:05:01.405  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 08:05:01.405  5598  5649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:01.409  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:05:01.409  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:05:01.413  5598  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 08:05:01.414  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:05:01.415  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:05:01.415  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:05:01.417  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 08:05:01.417  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:01.417  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-27 08:05:01.417  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:01.418  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:01.418  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 08:05:01.419  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:01.423  4563  4578 D BtGatt.GattService: registerClient() - UUID=1a8eb30c-99e4-43d6-8aa5-65cd3feb8e4e
,09-27 08:05:01.423  4563  4650 D BtGatt.GattService: onClientRegistered() - UUID=1a8eb30c-99e4-43d6-8aa5-65cd3feb8e4e, clientIf=5
09-27 08:05:01.424  5598  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 08:05:01.425  4563  4652 D BtGatt.AdvertiseManager: message : 0
09-27 08:05:01.427  4563  4652 D BtGatt.AdvertiseManager: starting multi advertising
09-27 08:05:01.436  4563  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-27 08:05:01.443  4563  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-27 08:05:01.444  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 08:05:01.444  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:05:01.445  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:05:01.446  5598  5644 I io.jxcore.node.ConnectionHelper: start: OK
09-27 08:05:01.446  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:01.446  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 08:05:01.446  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:05:01.446  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 08:05:01.446  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 08:05:01.446  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 08:05:01.449  5598  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 08:05:01.449  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 08:05:01.950  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 08:05:01.950  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-27 08:05:01.950  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:05:01.951  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 08:05:01.951  5598  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 08:05:01.951  5598  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-27 08:05:01.951  5598  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-27 08:05:01.951  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-27 08:05:01.952  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-27 08:05:01.954  4563  4652 D BtGatt.AdvertiseManager: message : 1
,09-27 08:05:01.957  4563  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 08:05:01.974  4563  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 08:05:01.974  4563  4650 D BtGatt.GattService: Client app is not null!
,09-27 08:05:01.976  4563  4786 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 08:05:01.977  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:05:01.977  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 08:05:01.977  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:05:01.977  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 08:05:01.977  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:01.978  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-27 08:05:01.978  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:01.978  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:01.979  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 08:05:01.980  5598  5644 D BluetoothAdapter: STATE_ON
,09-27 08:05:01.987  4563  4786 D BtGatt.GattService: registerClient() - UUID=1c190719-0782-48f4-832c-c2797f8480c3
,09-27 08:05:01.989  4563  4650 D BtGatt.GattService: onClientRegistered() - UUID=1c190719-0782-48f4-832c-c2797f8480c3, clientIf=5
,09-27 08:05:01.989  5598  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 08:05:01.990  4563  4652 D BtGatt.AdvertiseManager: message : 0
,09-27 08:05:01.994  4563  4652 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 08:05:02.007  4563  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 08:05:02.013  4563  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-27 08:05:02.014  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-27 08:05:02.014  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 08:05:02.014  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:05:02.014  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:05:02.014  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:05:02.014  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 08:05:02.014  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:05:02.014  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 08:05:02.015  5598  5644 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 08:05:02.016  5598  5644 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 08:05:02.016  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 08:05:02.016  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 08:05:02.016  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 08:05:02.016  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 08:05:02.016  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:05:02.016  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:05:02.016  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 08:05:02.016  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:05:02.016  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:05:02.016  5598  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:05:02.016  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:05:02.016  5598  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:05:02.016  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:05:02.017  5598  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:05:02.017  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:05:02.017  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 08:05:02.017  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:02.017  5598  5644 D BluetoothLeScanner: could not find callback wrapper
09-27 08:05:02.017  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:05:02.017  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-27 08:05:02.018  4563  4652 D BtGatt.AdvertiseManager: message : 1
09-27 08:05:02.019  4563  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 08:05:02.025  4563  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 08:05:02.025  4563  4650 D BtGatt.GattService: Client app is not null!
,09-27 08:05:02.026  4563  4786 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 08:05:02.027  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:05:02.027  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 08:05:02.027  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 08:05:02.027  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 08:05:02.027  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-27 08:05:02.029  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:02.029  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:05:02.029  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:05:02.029  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:05:02.031  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 08:05:02.031  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 08:05:02.032  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:02.032  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:02.032  5598  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 08:05:02.032  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:02.033  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-27 08:05:02.033  5598  5644 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-27 08:05:02.036  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-27 08:05:02.037  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-27 08:05:02.037  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-27 08:05:02.037  5598  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-27 08:05:02.038  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-27 08:05:02.038  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-27 08:05:02.039  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-27 08:05:02.039  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:02.039  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:02.039  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 08:05:02.039  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 08:05:02.040  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-27 08:05:02.040  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:05:02.041  5598  5644 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 08:05:02.041  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-27 08:05:02.043  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:05:02.043  5598  5644 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-27 08:05:02.043  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 08:05:02.043  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 08:05:02.044  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 08:05:02.045  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 08:05:02.045  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-27 08:05:02.045  5598  5644 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 08:05:02.045  5598  5644 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-27 08:05:02.045  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:05:02.046  5598  5644 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 08:05:02.046  5598  5644 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-27 08:05:02.046  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:05:02.046  5598  5644 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 08:05:02.046  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-27 08:05:02.051  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-27 08:05:02.051  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-27 08:05:02.051  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-27 08:05:02.052  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-27 08:05:02.052  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-27 08:05:02.052  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-27 08:05:02.052  5598  5644 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 08:05:02.052  5598  5644 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-27 08:05:02.053  5598  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
09-27 08:05:02.054  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-27 08:05:02.054  5598  5644 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-27 08:05:02.055  5598  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-27 08:05:02.055  5598  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:02.055  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-27 08:05:02.055  5598  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-27 08:05:02.056  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-27 08:05:02.056  5598  5644 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-27 08:05:02.052  4576  4576 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33217]" dev="sockfs" ino=33217 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:02.056  5598  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-27 08:05:02.056  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 08:05:02.056  5598  5644 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-27 08:05:02.056  5598  5644 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 08:05:02.056  5598  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-27 08:05:02.056  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 08:05:02.056  5598  5644 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-27 08:05:02.056  5598  5644 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 08:05:02.056  5598  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 08:05:02.057  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 08:05:02.057  5598  5644 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-27 08:05:02.057  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-27 08:05:02.057  5598  5644 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-27 08:05:02.057  5598  5644 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-27 08:05:02.057  5598  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-27 08:05:02.057  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-27 08:05:02.058  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:02.058  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 08:05:02.058  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:05:02.058  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:02.052  4576  4576 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33217]" dev="sockfs" ino=33217 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:02.058  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 08:05:02.059  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:05:02.059  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 08:05:02.059  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:05:02.059  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 08:05:02.059  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:02.059  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:05:02.059  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 08:05:02.061  5598  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:02.062  4807  4807 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30537]" dev="sockfs" ino=30537 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:02.064  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:05:02.064  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 08:05:02.065  5598  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 08:05:02.062  4807  4807 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30537]" dev="sockfs" ino=30537 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:02.069  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:05:02.070  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:05:02.070  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:05:02.072  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 08:05:02.072  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:02.072  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-27 08:05:02.072  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:02.073  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:02.073  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 08:05:02.073  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:02.075  4563  4786 D BtGatt.GattService: registerClient() - UUID=9d9be4df-9162-40d2-b788-6f1043be17cb
09-27 08:05:02.076  4563  4650 D BtGatt.GattService: onClientRegistered() - UUID=9d9be4df-9162-40d2-b788-6f1043be17cb, clientIf=5
09-27 08:05:02.076  5598  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-27 08:05:02.077  4563  4652 D BtGatt.AdvertiseManager: message : 0
09-27 08:05:02.079  4563  4652 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 08:05:02.087  4563  4650 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-27 08:05:02.093  4563  4650 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-27 08:05:02.094  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 08:05:02.094  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:05:02.095  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:05:02.097  5598  5644 I io.jxcore.node.ConnectionHelper: start: OK
09-27 08:05:02.097  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:02.097  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 08:05:02.097  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:05:02.097  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 08:05:02.097  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 08:05:02.097  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 08:05:02.100  5598  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 08:05:02.100  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 08:05:02.120   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:02.598  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 08:05:02.599  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 08:05:02.599  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 08:05:02.599  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:05:02.599  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:05:02.600  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 08:05:02.600  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:05:02.600  5598  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-27 08:05:02.600  5598  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:05:02.600  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-27 08:05:02.600  5598  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:05:02.601  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-27 08:05:02.602  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 08:05:02.602  5598  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-27 08:05:02.604  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7ac41d removed from the list
09-27 08:05:02.605  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:05:02.605  5598  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
09-27 08:05:02.605  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:05:02.606  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-27 08:05:02.606  5598  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
09-27 08:05:02.606  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:05:02.606  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:05:02.606  4563  4784 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
,09-27 08:05:02.606  5598  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
09-27 08:05:02.607  5598  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
09-27 08:05:02.608  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:02.609  5598  5644 D BluetoothLeScanner: could not find callback wrapper
09-27 08:05:02.609  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:05:02.609  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 08:05:02.610  4563  4652 D BtGatt.AdvertiseManager: message : 1
09-27 08:05:02.611  4563  4652 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 08:05:02.624  4563  4650 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 08:05:02.624  4563  4650 D BtGatt.GattService: Client app is not null!
,09-27 08:05:02.625  4563  4578 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:05:02.626  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:05:02.626  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 08:05:02.626  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 08:05:02.627  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 08:05:02.627  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-27 08:05:02.628  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:05:02.629  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:05:02.629  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 08:05:02.630  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:05:02.631  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6748692 removed from the list
09-27 08:05:02.631  5598  5644 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:05:02.632  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:02.632  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:05:02.632  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:02.632  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:02.634  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
09-27 08:05:02.636  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:05:02.636  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:02.637  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 08:05:02.638  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:05:02.638  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 08:05:02.638  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:05:02.638  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:05:02.638  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 08:05:02.640  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,09-27 08:05:02.641  5598  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:02.641  5598  5644 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-27 08:05:02.641  5598  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 08:05:02.641  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 08:05:02.641  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:02.641  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 08:05:02.639  4576  4576 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31237]" dev="sockfs" ino=31237 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:02.639  4576  4576 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31237]" dev="sockfs" ino=31237 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:02.643  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-27 08:05:02.644  5598  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 08:05:02.650  5598  5644 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,09-27 08:05:02.651  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 08:05:02.651  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 08:05:02.651  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 08:05:02.651  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:05:02.652  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:05:02.652  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 08:05:02.652  5598  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:05:02.652  5598  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-27 08:05:02.652  5598  5644 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7ac41d not in the list
09-27 08:05:02.652  5598  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:05:02.652  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:05:02.652  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:05:02.652  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:05:02.652  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-27 08:05:02.652  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:05:02.652  5598  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:05:02.652  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:05:02.653  5598  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-27 08:05:02.654  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:05:02.655  5598  5644 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6748692 not in the list
09-27 08:05:02.655  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 08:05:02.655  5598  5644 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:05:02.655  5598  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:05:02.655  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:02.655  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:05:02.655  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:02.657  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-27 08:05:02.659  5598  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-27 08:05:02.659  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 08:05:02.659  5598  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-27 08:05:02.659  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 08:05:02.660  5598  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-27 08:05:02.660  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 08:05:02.660  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,09-27 08:05:02.661  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,09-27 08:05:02.663  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,09-27 08:05:02.664  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 08:05:02.664  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-27 08:05:02.665  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-27 08:05:02.665  5598  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-27 08:05:02.665  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 08:05:02.665  5598  5644 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-27 08:05:02.665  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 08:05:02.665  5598  5644 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-27 08:05:02.665  5598  5644 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-27 08:05:02.666  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-27 08:05:02.666  5598  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-27 08:05:02.666  5598  5644 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-27 08:05:02.667  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-27 08:05:02.667  5598  5644 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-27 08:05:02.667  5598  5644 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-27 08:05:02.667  5598  5644 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-27 08:05:02.667  5598  5644 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-27 08:05:02.668  5598  5644 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-27 08:05:02.668  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:05:02.668  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d27b842 added. We now have 3 listener(s)
,09-27 08:05:02.671  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 08:05:02.671  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:05:02.671  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:05:02.672  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 08:05:02.672  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919c053 added. We now have 3 listener(s)
09-27 08:05:02.672  5598  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 08:05:02.673  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:05:02.676  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:05:02.681  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:05:02.682  5598  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:02.683  5598  5644 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:05:02.684  5598  5644 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 08:05:02.684   926  3125 D WifiService: setWifiEnabled: true pid=5598, uid=10077
,09-27 08:05:02.684   926  3125 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:02.685  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:02.686  5598  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
09-27 08:05:02.689  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:02.689  5598  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,09-27 08:05:02.690  5598  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-27 08:05:02.693   926  3384 D WifiService: setWifiEnabled: false pid=5598, uid=10077
,09-27 08:05:02.693   926  3384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:02.696   926  2949 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-27 08:05:02.696   926  2949 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-27 08:05:02.696   926  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:05:02.697   926  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:05:02.704   926  5350 D DhcpClient: Clearing IP address
,09-27 08:05:02.704   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:05:02.714   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:02.721  3551  5405 V NativeCrypto: Read error: ssl=0x7f9f945e00: I/O error during system call, Connection timed out
,09-27 08:05:02.723  3551  5405 V NativeCrypto: SSL shutdown failed: ssl=0x7f9f945e00: I/O error during system call, Broken pipe
,09-27 08:05:02.725   926  3125 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-27 08:05:02.725   926  5348 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-27 08:05:02.727   926  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-27 08:05:02.727   926  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-27 08:05:02.728   926  5348 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-27 08:05:02.732   532   532 E Parcel  : Reading a NULL string not supported here.
09-27 08:05:02.733   926   926 D RttService: SCAN_AVAILABLE : 1
,09-27 08:05:02.734   926  3057 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 08:05:02.737   926  2951 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-27 08:05:02.738   926  5351 D DhcpClient: Receive thread stopped
09-27 08:05:02.739  3747  3887 W QCNEJ   : |CORE| network lost: 100
09-27 08:05:02.740  3747  3887 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 08:05:02.742   926  2949 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-27 08:05:02.749   926  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 08:05:02.774   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:05:02.793   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:05:02.794   506   920 D CommandListener: Clearing all IP addresses on wlan0
09-27 08:05:02.795   926  2951 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-27 08:05:02.795   506   920 D TetherController: Setting IP forward enable = 0
09-27 08:05:02.795   926  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:05:02.796   926  2949 D DhcpClient: doQuit
,09-27 08:05:02.796   926  2949 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 08:05:02.797   926  5350 D DhcpClient: onQuitting
09-27 08:05:02.797  3428  3428 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 08:05:02.798   926   943 D Tethering: MasterInitialState.processMessage what=3
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:02.808  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:02.811  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:02.811  3892  3892 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-27 08:05:02.813  5247  5247 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1ccea03 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-27 08:05:02.816  5012  5036 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 08:05:02.816  5012  5036 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 08:05:02.816  5012  5036 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 08:05:02.816  5012  5036 E SarControlService: no key has been found,reset the power
09-27 08:05:02.816  5012  5048 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 08:05:02.816  5012  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 08:05:02.817  5012  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:02.817  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:02.817  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:05:02.817  5037  5037 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 08:05:02.819  5012  5048 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 08:05:02.819  5012  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-27 08:05:02.821  3705  3705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 08:05:02.821  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:02.821  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f71abc1 HexData = [00000000ea03000000000000ffffffff]
09-27 08:05:02.821  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:05:02.821  5037  5051 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-27 08:05:02.823  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:05:02.823  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:02.826  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:02.819  5012  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 08:05:02.827  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-27 08:05:02.827  5037  5037 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 08:05:02.828  3705  3705 D SystemUpdateService: onCreate
09-27 08:05:02.829  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:02.831  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:02.833  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f71abc1 HexData = [00000000eb03000000000000ffffffff]
09-27 08:05:02.833  3428  3428 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 08:05:02.833  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:05:02.833  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:02.833  5037  5051 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-27 08:05:02.833  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:05:02.834  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 08:05:02.834  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:02.834  3705  3705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-27 08:05:02.836  3428  3428 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 08:05:02.837   506   913 W SocketClient: write error (Broken pipe)
,09-27 08:05:02.837   506   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-27 08:05:02.837   506   913 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 08:05:02.843  3705  3705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 08:05:02.848  3705  5375 I iu.UploadsManager: num queued entries: 0
,09-27 08:05:02.849  3705  5375 I iu.UploadsManager: num updated entries: 0
09-27 08:05:02.849  3705  5375 I iu.SyncManager: NEXT; no task
,09-27 08:05:02.850  3705  5674 I SystemUpdateService: active receiver: enabled
,09-27 08:05:02.852  3705  3705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-27 08:05:02.853  3705  3705 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 08:05:02.855  5377  5377 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:05:02.859  5377  5377 D SprintDMHelper: simOperator: 
09-27 08:05:02.859  5377  5377 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 08:05:02.880  3428  3428 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-27 08:05:02.881  4978  5676 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 08:05:02.883  3705  5674 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-27 08:05:02.885  3705  5674 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-27 08:05:02.885  3705  5674 I SystemUpdateService: now status is 0 (complete)
09-27 08:05:02.885  3705  5674 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 08:05:02.885  3705  5674 I SystemUpdateService: file has been verified
09-27 08:05:02.885  3705  5674 I SystemUpdateService: OTA package size = 21989297
,09-27 08:05:02.890  3705  5674 I SystemUpdateService: showing system update notification
,09-27 08:05:02.893   926  3384 I ActivityManager: Start proc 5677:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-27 08:05:02.898  3428  3428 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 08:05:02.898   506   913 W SocketClient: write error (Broken pipe)
09-27 08:05:02.898   506   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-27 08:05:02.898   506   913 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 08:05:02.911  3705  3705 D SystemUpdateService: onDestroy
,09-27 08:05:02.937  5677  5677 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-27 08:05:02.944   926  3798 I ActivityManager: Killing 4937:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-27 08:05:03.002   926  2949 D wifi    : In wifi stop Hal
,09-27 08:05:03.002  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:05:03.002   926  2949 D wifi    : halHandle = 0x7f89342f00, mVM = 0x7fa5a0d140, mCls = 0x100a02
,09-27 08:05:03.002   926  3427 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 08:05:03.002   926  3427 D WifiHAL : Got a signal to exit!!!
09-27 08:05:03.003   926  3427 I WifiHAL : Exit wifi_event_loop
09-27 08:05:03.003   926  2949 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-27 08:05:03.003   926  2949 E WifiHAL : Event processing terminated
09-27 08:05:03.003   926  2949 D wifi    : In wifi cleaned up handler
09-27 08:05:03.003   926  2949 I WifiHAL : Internal cleanup completed
09-27 08:05:03.005  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:03.005  4049  4201 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:05:03.007  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:03.009  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:03.027   506   913 W SocketClient: write error (Broken pipe)
,09-27 08:05:03.027   506   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 down'
09-27 08:05:03.027   506   913 W SocketListener: Error sending broadcast (Broken pipe)
,09-27 08:05:03.028   926  3427 D wifi    : set interface wlan0 flags (DOWN)
09-27 08:05:03.028   926  2949 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 08:05:03.120   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:03.156  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:05:03.200  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:03.204   926  3835 D WifiService: setWifiEnabled: true pid=5598, uid=10077
,09-27 08:05:03.204   926  3835 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:03.236   926   943 D Tethering: InitialState.processMessage what=4
,09-27 08:05:03.243   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 08:05:03.710   926  3834 D WifiService: setWifiEnabled: true pid=5598, uid=10077
,09-27 08:05:03.710   926  3834 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:03.897   506   920 E Netd    : netlink response contains error (No such file or directory)
,09-27 08:05:03.898   926  2951 E NetdConnector: NDC Command {113 network destroy 100} took too long (1102ms)
,09-27 08:05:03.899   926  2951 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-27 08:05:03.899   926  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 08:05:03.899   926  2937 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1096ms)
,09-27 08:05:03.900   506   920 D SoftapController: Softap fwReload - Ok
,09-27 08:05:03.900   926  2949 E NetdConnector: NDC Command {115 softap fwreload wlan0 STA} took too long (668ms)
,09-27 08:05:03.901   926  2934 E NetdConnector: NDC Command {116 bandwidth gettetherstats} took too long (655ms)
,09-27 08:05:03.901   506   920 D TetherController: Setting IP forward enable = 0
,09-27 08:05:03.906   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:03.906   506   920 D CommandListener: Trying to bring down wlan0
09-27 08:05:03.908   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:05:03.911   926  2949 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 08:05:04.121   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:04.213   926  3691 D WifiService: setWifiEnabled: true pid=5598, uid=10077
09-27 08:05:04.215   926  3691 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:04.516   926  2949 D wifi    : set interface wlan0 flags (UP)
,09-27 08:05:04.517   926  2949 I WifiHAL : Initializing wifi
,09-27 08:05:04.517   926  2949 I WifiHAL : Creating socket
,09-27 08:05:04.523   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 08:05:04.529   926  2949 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 08:05:04.529   926  2949 D wifi    : Did set static halHandle = 0x7f89342f00
09-27 08:05:04.529   926  2949 D wifi    : halHandle = 0x7f89342f00, mVM = 0x7fa5a0d140, mCls = 0x2016b6
09-27 08:05:04.530   926  2949 D wifi    : array field set
09-27 08:05:04.530   926  2949 I WifiNative-HAL: interface[0] = wlan0
,09-27 08:05:04.532   926  5697 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547762745088
09-27 08:05:04.532   926  5697 D wifi    : waitForHalEvents called, vm = 0x7fa5a0d140, obj = 0x2016b6, env = 0x7f89390780
,09-27 08:05:04.613  5698  5698 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 08:05:04.633   926  2949 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 08:05:04.638  5698  5698 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:05:04.646  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.649  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:04.650  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.668  5698  5698 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:05:04.668  5698  5698 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 08:05:04.683   926  2949 D WifiConfigStore: Loading config and enabling all networks 
,09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:04.690  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:04.692  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:04.693   926  2949 D WifiConfigStore: loaded 0 passpoint configs
09-27 08:05:04.693   926  2949 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 08:05:04.693   926  2949 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-27 08:05:04.694   926  2949 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-27 08:05:04.695   926  2949 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 08:05:04.695   926  2949 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 08:05:04.695   926  2949 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 08:05:04.695   926  2949 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:04.696  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:04.698  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:04.699   926  2949 D WifiNative-HAL: Setting external_sim to 1
09-27 08:05:04.699   926  2949 D wifi    : setting dfs flag to true, 0x7f8cef86e0
,09-27 08:05:04.700   926  2949 D WifiStateMachine: Setting OUI to DA-A1-19
,09-27 08:05:04.700  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 08:05:04.700   926  2949 D wifi    : setting scan oui 0x7f8cef86e0
09-27 08:05:04.700   926  2949 D WifiHAL : Sending mac address OUI
,09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:04.704  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:04.704   926  2949 E native  : do suspend false
,09-27 08:05:04.706  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:04.712   926   926 D RttService: SCAN_AVAILABLE : 3
,09-27 08:05:04.712   926  2949 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 08:05:04.712   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 08:05:04.712   926  3057 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 08:05:04.713   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:04.717   926  2943 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-27 08:05:04.717   926  2943 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 08:05:04.722  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.727  4563  4646 D BluetoothAdapterState: Current state: ON, message: 23
,09-27 08:05:04.727  4563  4646 D BluetoothAdapterProperties: Setting state to 13
09-27 08:05:04.727  4563  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 08:05:04.727  4563  4646 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 08:05:04.728  4563  4646 I BluetoothAdapterState: Entering PendingCommandState
09-27 08:05:04.729  4563  4563 D BluetoothMapService: onReceive
,09-27 08:05:04.730  4563  4563 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 08:05:04.730  4563  4563 D BluetoothMapService: STATE_TURNING_OFF
09-27 08:05:04.730  4563  4563 D BluetoothMapService: MAP Service closeService in
09-27 08:05:04.730  4563  4563 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 08:05:04.730  4563  4563 D ObexServerSockets0: shutdown(block = true)
09-27 08:05:04.730   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=243262 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
09-27 08:05:04.731  4563  4563 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:05:04.731  4563  4819 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-27 08:05:04.731  4563  4820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-27 08:05:04.731  4563  4563 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:05:04.732  4563  4784 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 08:05:04.732  4563  4563 I BtOppRfcommListener: stopping Accept Thread
09-27 08:05:04.733  4563  5260 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 08:05:04.733  4563  5260 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-27 08:05:04.734  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:04.734  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:04.736  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:04.736  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:04.737   926  2943 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 08:05:04.737   926  2943 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-27 08:05:04.739  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:04.739  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:04.740  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:05:04.740  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:04.743  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:04.743  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:04.744  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:04.744  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:04.747   926   939 I ActivityManager: Start proc 5702:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-27 08:05:04.748  4563  4650 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:05:04.748  4563  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 08:05:04.753  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.756  4563  4563 D HeadsetService: Received stop request...Stopping profile...
09-27 08:05:04.756  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.758   926   926 D BluetoothHeadset: Proxy object disconnected
09-27 08:05:04.758  3105  3116 D BluetoothHeadset: Proxy object disconnected
09-27 08:05:04.759  3105  3105 D HeadsetProfile: Bluetooth service disconnected
09-27 08:05:04.759   926   926 D BluetoothHeadset: Proxy object disconnected
09-27 08:05:04.759  3800  4005 D BluetoothHeadset: Proxy object disconnected
09-27 08:05:04.759  4563  4563 D A2dpService: Received stop request...Stopping profile...
09-27 08:05:04.759  4563  4792 D A2dpStateMachine: Exit Disconnected: -1
09-27 08:05:04.760  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:04.760   926   926 D BluetoothHeadset: Proxy object disconnected
09-27 08:05:04.761   926   926 D BluetoothA2dp: Proxy object disconnected
09-27 08:05:04.761  3105  3105 D BluetoothA2dp: Proxy object disconnected
09-27 08:05:04.761  4563  4563 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:04.761  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.761  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.762  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:04.766  4563  4563 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 08:05:04.766  4563  4563 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 08:05:04.766  4563  4766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:04.766  4563  4766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:04.766  4563  4766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:04.766  4563  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-27 08:05:04.766  4563  4650 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-27 08:05:04.767  4563  4563 D HidService: Received stop request...Stopping profile...
09-27 08:05:04.767  4563  4563 D HidService: Stopping Bluetooth HidService
09-27 08:05:04.768  3105  3105 D BluetoothInputDevice: Proxy object disconnected
09-27 08:05:04.768  4563  4563 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:04.768  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.768  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.768  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:04.768  3105  3105 D HidProfile: Bluetooth service disconnected
09-27 08:05:04.769  4563  4563 D HealthService: Received stop request...Stopping profile...
,09-27 08:05:04.774  4563  4766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-27 08:05:04.774  4563  4766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:04.774  4563  4766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:05:04.774  4563  4563 D PanService: Received stop request...Stopping profile...
09-27 08:05:04.774  4563  4766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 08:05:04.774  4563  4766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:05:04.775  4563  4766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-27 08:05:04.775  4563  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 08:05:04.775  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 08:05:04.775  3105  3105 D PanProfile: Bluetooth service disconnected
09-27 08:05:04.775  4563  4563 D BluetoothMapService: Received stop request...Stopping profile...
09-27 08:05:04.775  4563  4563 D BluetoothMapService: stop()
09-27 08:05:04.776  4563  4563 D BluetoothMapAppObserver: deinitObservers()
09-27 08:05:04.776  4563  4563 D BluetoothMapAppObserver: removeReceiver()
09-27 08:05:04.777  3105  3105 D BluetoothMap: Proxy object disconnected
09-27 08:05:04.777  3105  3105 D MapProfile: Bluetooth service disconnected
,09-27 08:05:04.777  4563  4563 D SapService: Received stop request...Stopping profile...
09-27 08:05:04.778  4563  4563 V SapService: stop()
09-27 08:05:04.778  4563  4563 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:04.779  4563  4563 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 08:05:04.779  4563  4563 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 08:05:04.779  4563  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isTurningOff()=true
,09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.779  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:04.779  4563  4563 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 08:05:04.780  4563  4650 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-27 08:05:04.780  4563  4563 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 08:05:04.780  4563  4563 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:04.780  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.780  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.780  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:04.780  4563  4563 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 08:05:04.781  4563  4563 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 08:05:04.782  4563  4563 D BluetoothMapService: MAP Service closeService in
09-27 08:05:04.782  4563  4563 V BluetoothAdapterState: isTurningOff()=true
,09-27 08:05:04.782  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.782  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.782  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:04.782  4563  4563 D BluetoothMapService: cleanup()
09-27 08:05:04.782  4563  4563 D BluetoothMapService: MAP Service closeService in
09-27 08:05:04.783  4563  4563 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:04.783  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:04.783  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:04.783  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:04.785  4563  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 08:05:04.785  4563  4646 D BluetoothAdapterProperties: Setting state to 15
09-27 08:05:04.785  4563  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 08:05:04.786  4563  4646 I BluetoothAdapterState: Entering BleOnState
09-27 08:05:04.786  3800  3827 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:04.786   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:04.786  3105  3952 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-27 08:05:04.787  3105  3117 D BluetoothPan: onBluetoothStateChange on: false
09-27 08:05:04.787  3105  3116 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:05:04.788   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:04.789  3105  3952 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 08:05:04.789   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:04.790  3105  3117 D BluetoothMap: onBluetoothStateChange: up=false
09-27 08:05:04.790   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:05:04.790  3105  3116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:04.791  4563  4646 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 08:05:04.791  4563  4646 D BluetoothAdapterProperties: Setting state to 16
,09-27 08:05:04.791  4563  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 08:05:04.792  4563  4646 D BluetoothAdapterProperties: onBleDisable
09-27 08:05:04.792  4563  4646 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:05:04.792  4563  4647 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 08:05:04.794  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:04.795  4563  4650 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:05:04.795  4563  4766 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 08:05:04.795  4563  4766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-27 08:05:04.796  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.797  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.799  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.801  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.803  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:04.808  5702  5702 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-27 08:05:04.819  5702  5702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:05:04.824   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a407539:true
,09-27 08:05:04.825  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:05:04.838   926   936 I ActivityManager: Start proc 5714:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-27 08:05:04.854  5702  5702 D LocalBluetoothProfileManager: Adding local MAP profile
,09-27 08:05:04.859  5702  5702 D BluetoothMap: Create BluetoothMap proxy object
,09-27 08:05:04.870  5702  5702 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-27 08:05:04.879  5714  5714 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-27 08:05:04.891  5702  5702 D DockEventReceiver: finishStartingService: stopping service
,09-27 08:05:04.893   926  3565 I ActivityManager: Killing 5247:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-27 08:05:05.001  4563  4650 I bt_hci  : shut_down
,09-27 08:05:05.007  4563  4655 D bt_hwcfg: hw_epilog_process
,09-27 08:05:05.007  4563  4655 I bt_vendor: low_power_mode_cb
,09-27 08:05:05.009  4563  4655 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-27 08:05:05.009  4563  4655 I bt_vendor: epilog_cb
09-27 08:05:05.009  4563  4655 I bt_hci  : epilog_finished_callback
,09-27 08:05:05.012  4563  4650 I bt_hci_h4: hal_close
,09-27 08:05:05.012  4563  4650 I bt_userial_vendor: device fd = 54 close
,09-27 08:05:05.070  5714  5714 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-27 08:05:05.070  5714  5714 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.070  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.071  5714  5714 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.071  5714  5714 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.071  5714  5714 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.k.d(PG:583)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.071  5714  5714 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.071  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.082  5714  5714 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.082  5714  5714 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 08:05:05.082  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 08:05:05.086  5702  5702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 08:05:05.092  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:05:05.106  5702  5702 D DockEventReceiver: finishStartingService: stopping service
09-27 08:05:05.107   926  3565 I ActivityManager: Killing 4660:com.android.providers.calendar/u0a1 (adj 15): empty #17
09-27 08:05:05.122   534   534 I ServiceManager: Waiting for service AtCmdFwd...
09-27 08:05:05.141  4563  4647 D bt_stack_manager: event_shut_down_stack finished.
09-27 08:05:05.141  4563  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-27 08:05:05.143  4563  4563 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:05:05.143  4563  4646 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 08:05:05.144  4563  4563 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 08:05:05.144  4563  4563 D BtGatt.GattService: stop()
09-27 08:05:05.144  4563  4563 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 08:05:05.146  4563  4563 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:05.146  4563  4563 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:05.146  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:05.146  4563  4563 V BluetoothAdapterState: isBleTurningOff()=true
09-27 08:05:05.146  4563  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 08:05:05.146  4563  4646 D BluetoothAdapterProperties: Setting state to 10
09-27 08:05:05.146  4563  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 08:05:05.147  4563  4646 I BluetoothAdapterState: Entering OffState
09-27 08:05:05.148   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-27 08:05:05.154  4563  4563 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 08:05:05.154  4563  4563 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 08:05:05.154  4563  4563 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 08:05:05.155  4563  4647 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 08:05:05.160  4563  4563 I art     : System.exit called, status: 0
,09-27 08:05:05.160  4563  4563 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 08:05:05.216   926  3384 I ActivityManager: Process com.android.bluetooth (pid 4563) has died
,09-27 08:05:05.227  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:05.240   926   943 I ActivityManager: Start proc 5747:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 08:05:05.306  5747  5747 D AdapterServiceConfig: Adding HeadsetService
,09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding A2dpService
09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding HidService
09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding HealthService
09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding PanService
09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding GattService
,09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding BluetoothMapService
09-27 08:05:05.307  5747  5747 D AdapterServiceConfig: Adding SapService
,09-27 08:05:05.317   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8e2306:true
,09-27 08:05:05.317  5747  5747 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 08:05:05.321  5747  5747 I bt_bluedroid: init
09-27 08:05:05.321  5747  5759 I BluetoothAdapterState: Entering OffState
,09-27 08:05:05.323  5747  5760 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 08:05:05.323  5747  5760 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 08:05:05.323  5747  5760 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 08:05:05.323  5747  5760 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 08:05:05.324  5747  5747 I bt_bluedroid: get_profile_interface socket
,09-27 08:05:05.325  5747  5763 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 08:05:05.326  5747  5747 I bt_bluedroid: get_profile_interface sdp
09-27 08:05:05.326  5747  5763 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 08:05:05.327  5714  5733 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-27 08:05:05.330  5747  5758 I bt_bluedroid: config_hci_snoop_log
,09-27 08:05:05.331   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-27 08:05:05.335  5747  5759 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 08:05:05.335  5747  5759 D BluetoothAdapterProperties: Setting state to 14
09-27 08:05:05.335  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-27 08:05:05.336  5747  5759 D BluetoothBondStateMachine: make
,09-27 08:05:05.338  5747  5764 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 08:05:05.341  5747  5759 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:05:05.342  5747  5747 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 08:05:05.344  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
09-27 08:05:05.344  5747  5747 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:05:05.345  5747  5747 D BtGatt.GattService: Received start request. Starting profile...
09-27 08:05:05.345  5747  5747 D BtGatt.GattService: start()
09-27 08:05:05.345  5747  5747 I bt_bluedroid: get_profile_interface gatt
,09-27 08:05:05.346  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:05.346  5747  5747 D BtGatt.AdvertiseManager: advertise manager created
,09-27 08:05:05.348   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6e3760:true
,09-27 08:05:05.350  5747  5747 V BluetoothAdapterState: isTurningOff()=false
,09-27 08:05:05.350  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:05.350  5747  5747 V BluetoothAdapterState: isBleTurningOn()=true
09-27 08:05:05.350  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:05.350  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 08:05:05.351  5747  5759 I bt_bluedroid: bt_bluedroid
09-27 08:05:05.351  5747  5760 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 08:05:05.351  5747  5760 I bt_hci  : start_up
,09-27 08:05:05.356  5747  5760 I bt_vendor: alloc value 0xf3e15871
,09-27 08:05:05.356  5747  5760 I bt_vendor: init
09-27 08:05:05.356  5747  5760 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 08:05:05.356  5747  5760 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 08:05:05.462  5770  5770 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 08:05:05.464  5747  5760 D bt_hci  : start_up starting async portion
09-27 08:05:05.465  5747  5768 I bt_hci  : event_finish_startup
09-27 08:05:05.465  5747  5768 I bt_hci_h4: hal_open
09-27 08:05:05.465  5747  5768 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-27 08:05:05.466  5747  5768 I bt_userial_vendor: device fd = 54 open
,09-27 08:05:05.479  5747  5768 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:05:05.481  5747  5768 D bt_hwcfg: Chipset BCM4358A3
,09-27 08:05:05.481  5747  5768 D bt_hwcfg: Target name = [BCM4358A3]
09-27 08:05:05.482  5747  5768 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 08:05:05.735  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 08:05:05.875  5747  5768 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 08:05:05.875  5747  5768 D bt_hwcfg: Settlement delay -- 100 ms
,09-27 08:05:05.875  5747  5768 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 08:05:05.999  5747  5768 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:05:05.999  5747  5768 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 08:05:06.001  5747  5768 I bt_hwcfg: vendor lib fwcfg completed
09-27 08:05:06.001  5747  5768 I bt_vendor: firmware callback
09-27 08:05:06.001  5747  5768 I bt_hci  : firmware_config_callback
,09-27 08:05:06.010  5747  5772 I bt_btu  : btu_task pending for preload complete event
09-27 08:05:06.010  5747  5772 I bt_btu_task: Bluetooth chip preload is complete
,09-27 08:05:06.011  5747  5772 I bt_btu  : btu_task received preload complete event
,09-27 08:05:06.017  5747  5772 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 08:05:06.017  5747  5772 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 08:05:06.017  5747  5772 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 08:05:06.017  5747  5772 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_A2D
,09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_BNEP
09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 08:05:06.018  5747  5772 I         : BTE_InitTraceLevels -- TRC_SDP
,09-27 08:05:06.019  5747  5772 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 08:05:06.019  5747  5772 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 08:05:06.019  5747  5772 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 08:05:06.019  5747  5772 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 08:05:06.102  5747  5772 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d93549
,09-27 08:05:06.102  5747  5772 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d93549 
,09-27 08:05:06.122   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 08:05:06.125  5747  5763 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 08:05:06.127  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 08:05:06.127  5747  5763 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 08:05:06.130  5747  5763 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 08:05:06.132  5747  5763 D BluetoothAdapterProperties: Scan Mode:20
,09-27 08:05:06.133  5747  5763 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 08:05:06.133  5747  5763 D bt_hci  : do_postload posting postload work item
09-27 08:05:06.133  5747  5768 I bt_hci  : event_postload
09-27 08:05:06.133  5747  5768 I bt_vendor: sco_config_cb
09-27 08:05:06.133  5747  5768 I bt_hci  : sco_config_callback postload finished.
09-27 08:05:06.136  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.137  5747  5763 D bt_bte_conf: Device ID record 1 : primary
09-27 08:05:06.137  5747  5763 D bt_bte_conf:   vendorId            = 000f
09-27 08:05:06.137  5747  5763 D bt_bte_conf:   vendorIdSource      = 0001
09-27 08:05:06.137  5747  5763 D bt_bte_conf:   product             = 1200
09-27 08:05:06.137  5747  5763 D bt_bte_conf:   version             = 1436
09-27 08:05:06.137  5747  5763 D bt_bte_conf:   clientExecutableURL = 
09-27 08:05:06.137  5747  5763 D bt_bte_conf:   serviceDescription  = 
09-27 08:05:06.138  5747  5763 D bt_bte_conf:   documentationURL    = 
09-27 08:05:06.138  5747  5763 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 08:05:06.139  5747  5760 D bt_stack_manager: event_start_up_stack finished
,09-27 08:05:06.140  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-27 08:05:06.140  5747  5759 D BluetoothAdapterProperties: Setting state to 15
,09-27 08:05:06.140  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 08:05:06.141  5747  5759 I BluetoothAdapterState: Entering BleOnState
09-27 08:05:06.142  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.143  5747  5768 I bt_vendor: low_power_mode_cb
09-27 08:05:06.144  5747  5759 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 08:05:06.144  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.144  5747  5759 D BluetoothAdapterProperties: Setting state to 11
09-27 08:05:06.144  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 08:05:06.149  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:06.149  5747  5747 D HeadsetService: Received start request. Starting profile...
09-27 08:05:06.150  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.152  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.152  5747  5747 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 08:05:06.153  5747  5747 D HeadsetStateMachine: make
09-27 08:05:06.153  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:06.162  5747  5759 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:05:06.162  5747  5747 D HeadsetStateMachine: max_hf_connections = 1
09-27 08:05:06.163  5747  5747 I bt_bluedroid: get_profile_interface handsfree
09-27 08:05:06.163  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 08:05:06.163  5747  5763 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,09-27 08:05:06.166  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:06.166  5747  5747 D A2dpService: Received start request. Starting profile...
,09-27 08:05:06.167  5747  5747 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 08:05:06.167  5747  5747 I bt_bluedroid: get_profile_interface avrcp
,09-27 08:05:06.172  5747  5747 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 08:05:06.172  5747  5747 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 08:05:06.172  5747  5747 D A2dpStateMachine: make
09-27 08:05:06.173  5747  5747 I bt_bluedroid: get_profile_interface a2dp
,09-27 08:05:06.173  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 08:05:06.175  5747  5781 D A2dpStateMachine: Enter Disconnected: -2
,09-27 08:05:06.175  5747  5747 I BluetoothHidServiceJni: classInitNative: succeeds
09-27 08:05:06.176  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:06.177  5747  5747 D HidService: Received start request. Starting profile...
,09-27 08:05:06.177  5747  5747 I bt_bluedroid: get_profile_interface hidhost
09-27 08:05:06.177  5702  5702 D BluetoothInputDevice: Proxy object connected
09-27 08:05:06.177  5747  5747 D HidService: setHidService(): set to: null
09-27 08:05:06.177  5747  5763 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d7456d
09-27 08:05:06.178  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 08:05:06.178  5747  5747 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 08:05:06.178  5702  5702 D HidProfile: Bluetooth service connected
09-27 08:05:06.178  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
09-27 08:05:06.179  5747  5747 D HealthService: Received start request. Starting profile...
,09-27 08:05:06.180  5747  5747 I bt_bluedroid: get_profile_interface health
09-27 08:05:06.181  5747  5747 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-27 08:05:06.181  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:06.182  5702  5702 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 08:05:06.182  5747  5747 D PanService: Received start request. Starting profile...
09-27 08:05:06.183  5747  5747 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 08:05:06.183  5747  5747 I bt_bluedroid: get_profile_interface pan
09-27 08:05:06.183  5702  5702 D PanProfile: Bluetooth service connected
09-27 08:05:06.183  5747  5763 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 08:05:06.186  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:06.187  5702  5702 D BluetoothMap: Proxy object connected
,09-27 08:05:06.188  5747  5747 D BluetoothMapService: Received start request. Starting profile...
09-27 08:05:06.188  5747  5747 D BluetoothMapService: start()
09-27 08:05:06.190  5747  5747 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-27 08:05:06.190  5747  5747 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 08:05:06.191  5747  5747 D BluetoothMapAppObserver: createReceiver()
09-27 08:05:06.192  5747  5747 D BluetoothMapAppObserver: initObservers()
09-27 08:05:06.192  5747  5747 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 08:05:06.197  5747  5747 V SapService: SapBinder()
09-27 08:05:06.197  5747  5747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
09-27 08:05:06.198  5702  5702 D MapProfile: Bluetooth service connected
09-27 08:05:06.198  5702  5702 D BluetoothMap: getConnectedDevices()
09-27 08:05:06.199  5747  5747 D SapService: Received start request. Starting profile...
09-27 08:05:06.199  5747  5747 V SapService: start()
09-27 08:05:06.201  5702  5702 D BluetoothMap: Bluetooth is Not enabled
09-27 08:05:06.201  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.201  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.201  5747  5779 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 08:05:06.201  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.201  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isTurningOff()=false
,09-27 08:05:06.202  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.202  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.203  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:06.204  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.204  5747  5747 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:06.204  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.205  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:06.205  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 08:05:06.205  5747  5759 D BluetoothAdapterProperties: ScanMode =  20
09-27 08:05:06.205  5747  5759 D BluetoothAdapterProperties: State =  11
,09-27 08:05:06.206  5747  5763 D BluetoothAdapterProperties: Scan Mode:21
,09-27 08:05:06.206  5747  5763 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-27 08:05:06.206  5747  5759 D BluetoothAdapterProperties: Setting state to 12
,09-27 08:05:06.206  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 08:05:06.207  5747  5759 I BluetoothAdapterState: Entering OnState
09-27 08:05:06.207  3800  3827 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 08:05:06.208   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:06.208  3105  3117 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 08:05:06.209  5598  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-27 08:05:06.210  3105  3117 D BluetoothPan: onBluetoothStateChange on: true
,09-27 08:05:06.211  3105  3105 D BluetoothInputDevice: Proxy object connected
,09-27 08:05:06.211  3105  3105 D HidProfile: Bluetooth service connected
,09-27 08:05:06.212  5598  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-27 08:05:06.213  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 08:05:06.213  3105  3105 D PanProfile: Bluetooth service connected
09-27 08:05:06.213  3105  3952 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:06.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:06.215   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:06.216  3105  3116 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 08:05:06.216  3105  3105 D BluetoothA2dp: Proxy object connected
09-27 08:05:06.217  5747  5747 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 08:05:06.217  5747  5747 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 08:05:06.218  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:06.219  5702  5713 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:05:06.219  5747  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:06.219   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:06.219  5702  5712 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 08:05:06.221  3105  3117 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:06.222  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:06.222  5747  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:05:06.224  3105  3105 D BluetoothMap: Proxy object connected
09-27 08:05:06.224  3105  3105 D MapProfile: Bluetooth service connected
09-27 08:05:06.224  5702  5713 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 08:05:06.224  3105  3105 D BluetoothMap: getConnectedDevices()
,09-27 08:05:06.225  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:06.225   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-27 08:05:06.226   926   926 D BluetoothA2dp: Proxy object connected
,09-27 08:05:06.226  5702  5712 D BluetoothPan: onBluetoothStateChange on: true
09-27 08:05:06.227  3105  3116 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:06.229  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:06.231   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 08:05:06.231  5747  5747 D ObexServerSockets: Succeed to create listening sockets 
09-27 08:05:06.231  5747  5747 D ObexServerSockets0: startAccept()
09-27 08:05:06.232  5747  5747 D ObexServerSockets0: prepareForNewConnect()
,09-27 08:05:06.233  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:06.234  5747  5747 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-27 08:05:06.234  5747  5747 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 08:05:06.235  5702  5702 D LocalBluetoothProfileManager: Adding local A2DP profile
09-27 08:05:06.235  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.237  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.237  5747  5788 D ObexServerSockets0: Accepting socket connection...
09-27 08:05:06.237  5747  5747 D BluetoothMapService: onReceive
09-27 08:05:06.237  5747  5787 D ObexServerSockets0: Accepting socket connection...
09-27 08:05:06.237  5747  5747 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 08:05:06.237  5747  5747 D BluetoothMapService: STATE_ON
09-27 08:05:06.237  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.239  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.239  5598  5644 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:05:06.239  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:05:06.239  5747  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:06.239  5702  5702 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-27 08:05:06.241  5598  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-27 08:05:06.242  5598  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-27 08:05:06.244  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.245  5747  5789 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 08:05:06.245  5747  5789 D BluetoothSdpJni: SDP Create record success - handle: 1
09-27 08:05:06.245  5747  5759 D BluetoothAdapterState: Current state: ON, message: 23
09-27 08:05:06.245  5747  5759 D BluetoothAdapterProperties: Setting state to 13
09-27 08:05:06.245  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 08:05:06.246  5747  5759 D BluetoothAdapterProperties: onBluetoothDisable()
09-27 08:05:06.247  5747  5759 I BluetoothAdapterState: Entering PendingCommandState
09-27 08:05:06.247  5702  5702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:05:06.247  5747  5763 D BluetoothAdapterProperties: Scan Mode:20
,09-27 08:05:06.248  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 08:05:06.249  5702  5702 D BluetoothA2dp: Proxy object connected
,09-27 08:05:06.250  5747  5747 D HeadsetService: Received stop request...Stopping profile...
09-27 08:05:06.252  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:06.252  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:06.253  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:06.253  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:06.254  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.254  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.254  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.254  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.255  5747  5747 D A2dpService: Received stop request...Stopping profile...
09-27 08:05:06.255  5747  5781 D A2dpStateMachine: Exit Disconnected: -1
09-27 08:05:06.256  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:06.256  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:06.256  5598  5598 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:06.256  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:06.256  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:05:06.257  5702  5702 D DockEventReceiver: finishStartingService: stopping service
,09-27 08:05:06.260   926   926 D BluetoothA2dp: Proxy object disconnected
09-27 08:05:06.260  3105  3105 D BluetoothA2dp: Proxy object disconnected
09-27 08:05:06.260  5702  5702 D BluetoothA2dp: Proxy object disconnected
,09-27 08:05:06.263  5747  5747 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-27 08:05:06.263  5747  5747 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 08:05:06.263  5747  5772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:06.263  5747  5772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:06.263  5747  5772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:06.263  5747  5747 D HidService: Received stop request...Stopping profile...
09-27 08:05:06.263  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 08:05:06.263  5747  5747 D HidService: Stopping Bluetooth HidService
09-27 08:05:06.263  5747  5763 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-27 08:05:06.264  3105  3105 D BluetoothInputDevice: Proxy object disconnected
09-27 08:05:06.264  3105  3105 D HidProfile: Bluetooth service disconnected
09-27 08:05:06.264  5702  5702 D BluetoothInputDevice: Proxy object disconnected
09-27 08:05:06.264  5702  5702 D HidProfile: Bluetooth service disconnected
,09-27 08:05:06.271  3105  3105 D BluetoothPbap: Proxy object connected
,09-27 08:05:06.271  5702  5702 D BluetoothPbap: Proxy object connected
09-27 08:05:06.271  3105  3105 D PbapServerProfile: Bluetooth service connected
09-27 08:05:06.272  5702  5702 D PbapServerProfile: Bluetooth service connected
09-27 08:05:06.272  5747  5747 D HealthService: Received stop request...Stopping profile...
,09-27 08:05:06.273  5747  5747 D PanService: Received stop request...Stopping profile...
09-27 08:05:06.273  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 08:05:06.273  3105  3105 D PanProfile: Bluetooth service disconnected
,09-27 08:05:06.273  5702  5702 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 08:05:06.274  5702  5702 D PanProfile: Bluetooth service disconnected
09-27 08:05:06.274  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.274  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.274  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.274  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:06.274  5747  5747 D BluetoothMapService: Received stop request...Stopping profile...
,09-27 08:05:06.274  5747  5747 D BluetoothMapService: stop()
09-27 08:05:06.275  5747  5747 D BluetoothMapAppObserver: deinitObservers()
09-27 08:05:06.275  5747  5747 D BluetoothMapAppObserver: removeReceiver()
09-27 08:05:06.276  3105  3105 D BluetoothMap: Proxy object disconnected
09-27 08:05:06.276  3105  3105 D MapProfile: Bluetooth service disconnected
09-27 08:05:06.276  5702  5702 D BluetoothMap: Proxy object disconnected
09-27 08:05:06.276  5702  5702 D MapProfile: Bluetooth service disconnected
,09-27 08:05:06.277  5747  5772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:06.277  5747  5772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:06.278  5747  5772 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:05:06.278  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 08:05:06.278  5747  5772 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 08:05:06.278  5747  5772 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 08:05:06.278  5747  5747 D SapService: Received stop request...Stopping profile...
09-27 08:05:06.278  5747  5772 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 08:05:06.278  5747  5747 V SapService: stop()
09-27 08:05:06.284  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.284  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.284  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.284  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.284  5747  5747 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 08:05:06.285  5747  5747 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 08:05:06.285  5747  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 08:05:06.285  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.285  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.285  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.285  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.285  5747  5747 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-27 08:05:06.285  5747  5763 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-27 08:05:06.286  5747  5747 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 08:05:06.286  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.286  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.286  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 08:05:06.286  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.286  5747  5747 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 08:05:06.286  5747  5747 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 08:05:06.287  5747  5747 D BluetoothMapService: MAP Service closeService in
09-27 08:05:06.288  5747  5747 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 08:05:06.288  5747  5747 D ObexServerSockets0: shutdown(block = true)
09-27 08:05:06.288  5747  5787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-27 08:05:06.289  5747  5747 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-27 08:05:06.289  5747  5788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 08:05:06.289  5747  5774 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-27 08:05:06.289  5747  5747 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 08:05:06.289  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.289  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.289  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.290  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.290  5747  5747 D BluetoothMapService: cleanup()
,09-27 08:05:06.290  5747  5747 D BluetoothMapService: MAP Service closeService in
09-27 08:05:06.290  5747  5747 V BluetoothAdapterState: isTurningOff()=true
09-27 08:05:06.290  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.291  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.291  5747  5747 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:06.291  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 08:05:06.291  5747  5759 D BluetoothAdapterProperties: Setting state to 15
09-27 08:05:06.291  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 08:05:06.292  5747  5759 I BluetoothAdapterState: Entering BleOnState
,09-27 08:05:06.298  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.299  3800  3830 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:06.299  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:06.300  5702  5702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:05:06.301  5702  5712 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:05:06.303   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:06.303  3105  3117 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 08:05:06.304  3105  3952 D BluetoothPan: onBluetoothStateChange on: false
09-27 08:05:06.304  3105  3116 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-27 08:05:06.305   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:06.305  3105  3117 D BluetoothPbap: onBluetoothStateChange: up=false
,09-27 08:05:06.306  5702  5713 D BluetoothMap: onBluetoothStateChange: up=false
09-27 08:05:06.306   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:06.307  5702  5712 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 08:05:06.307  3105  3952 D BluetoothMap: onBluetoothStateChange: up=false
09-27 08:05:06.308  5702  5713 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-27 08:05:06.308   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 08:05:06.309  5702  5712 D BluetoothPan: onBluetoothStateChange on: false
09-27 08:05:06.309  5702  5713 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:06.309  3105  3116 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 08:05:06.310  5747  5759 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 08:05:06.310  5747  5759 D BluetoothAdapterProperties: Setting state to 16
09-27 08:05:06.310  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 08:05:06.310  5747  5759 D BluetoothAdapterProperties: onBleDisable
09-27 08:05:06.310  5747  5759 I BluetoothAdapterState: Entering PendingCommandState
09-27 08:05:06.310  5747  5760 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 08:05:06.313  5747  5763 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:05:06.313  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:06.314  5747  5772 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-27 08:05:06.314  5747  5772 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 08:05:06.316  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 08:05:06.316  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:06.319  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:06.320  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:06.329  5702  5702 D DockEventReceiver: finishStartingService: stopping service
09-27 08:05:06.332  5702  5702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 08:05:06.336  5702  5702 D DockEventReceiver: finishStartingService: stopping service
,09-27 08:05:06.336  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:05:06.514  5747  5763 I bt_hci  : shut_down
,09-27 08:05:06.514  5747  5768 D bt_hwcfg: hw_epilog_process
09-27 08:05:06.515  5747  5768 I bt_vendor: low_power_mode_cb
,09-27 08:05:06.518  5747  5768 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-27 08:05:06.518  5747  5768 I bt_vendor: epilog_cb
09-27 08:05:06.518  5747  5768 I bt_hci  : epilog_finished_callback
,09-27 08:05:06.519  5747  5763 I bt_hci_h4: hal_close
09-27 08:05:06.519  5747  5763 I bt_userial_vendor: device fd = 54 close
,09-27 08:05:06.632  5747  5760 D bt_stack_manager: event_shut_down_stack finished.
,09-27 08:05:06.632  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 08:05:06.635  5747  5759 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-27 08:05:06.636  5747  5747 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 08:05:06.636  5747  5747 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 08:05:06.637  5747  5747 D BtGatt.GattService: stop()
09-27 08:05:06.637  5747  5747 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 08:05:06.639  5747  5747 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.639  5747  5747 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.639  5747  5747 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:06.639  5747  5747 V BluetoothAdapterState: isBleTurningOff()=true
09-27 08:05:06.639  5747  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 08:05:06.639  5747  5759 D BluetoothAdapterProperties: Setting state to 10
09-27 08:05:06.639  5747  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-27 08:05:06.640  5747  5759 I BluetoothAdapterState: Entering OffState
09-27 08:05:06.642   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-27 08:05:06.649  5747  5747 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 08:05:06.649  5747  5747 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 08:05:06.650  5747  5747 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 08:05:06.651  5747  5760 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 08:05:06.654  5747  5747 I art     : System.exit called, status: 0
,09-27 08:05:06.654  5747  5747 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 08:05:06.677   926  3834 I ActivityManager: Process com.android.bluetooth (pid 5747) has died
,09-27 08:05:06.746  5598  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:06.746  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:06.746  5598  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 08:05:06.746  5598  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:06.748  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:06.764   926   943 I ActivityManager: Start proc 5801:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 08:05:06.821  5801  5801 D AdapterServiceConfig: Adding HeadsetService
09-27 08:05:06.822  5801  5801 D AdapterServiceConfig: Adding A2dpService
09-27 08:05:06.822  5801  5801 D AdapterServiceConfig: Adding HidService
09-27 08:05:06.822  5801  5801 D AdapterServiceConfig: Adding HealthService
09-27 08:05:06.822  5801  5801 D AdapterServiceConfig: Adding PanService
09-27 08:05:06.822  5801  5801 D AdapterServiceConfig: Adding GattService
09-27 08:05:06.822  5801  5801 D AdapterServiceConfig: Adding BluetoothMapService
09-27 08:05:06.823  5801  5801 D AdapterServiceConfig: Adding SapService
,09-27 08:05:06.834   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@57dd27f:true
,09-27 08:05:06.834  5801  5801 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 08:05:06.837  5801  5801 I bt_bluedroid: init
09-27 08:05:06.837  5801  5813 I BluetoothAdapterState: Entering OffState
,09-27 08:05:06.839  5801  5814 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-27 08:05:06.839  5801  5814 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 08:05:06.839  5801  5814 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 08:05:06.839  5801  5814 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 08:05:06.839  5801  5801 I bt_bluedroid: get_profile_interface socket
,09-27 08:05:06.841  5801  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 08:05:06.841  5801  5801 I bt_bluedroid: get_profile_interface sdp
,09-27 08:05:06.842  5801  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 08:05:06.846  5801  5812 I bt_bluedroid: config_hci_snoop_log
09-27 08:05:06.847   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 08:05:06.851  5801  5813 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 08:05:06.851  5801  5813 D BluetoothAdapterProperties: Setting state to 14
,09-27 08:05:06.851  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-27 08:05:06.852  5801  5813 D BluetoothBondStateMachine: make
09-27 08:05:06.854  5801  5818 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 08:05:06.857  5801  5813 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:05:06.858  5801  5801 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-27 08:05:06.860  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
09-27 08:05:06.860  5801  5801 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 08:05:06.861  5801  5801 D BtGatt.GattService: Received start request. Starting profile...
09-27 08:05:06.861  5801  5801 D BtGatt.GattService: start()
09-27 08:05:06.861  5801  5801 I bt_bluedroid: get_profile_interface gatt
09-27 08:05:06.862  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
09-27 08:05:06.862  5801  5801 D BtGatt.AdvertiseManager: advertise manager created
,09-27 08:05:06.866  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:06.866  5801  5801 V BluetoothAdapterState: isTurningOn()=false
09-27 08:05:06.866  5801  5801 V BluetoothAdapterState: isBleTurningOn()=true
09-27 08:05:06.866  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:06.866  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 08:05:06.867  5801  5813 I bt_bluedroid: bt_bluedroid
,09-27 08:05:06.867  5801  5814 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 08:05:06.868  5801  5814 I bt_hci  : start_up
,09-27 08:05:06.873  5801  5814 I bt_vendor: alloc value 0xf3e15871
,09-27 08:05:06.873  5801  5814 I bt_vendor: init
09-27 08:05:06.873  5801  5814 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-27 08:05:06.873  5801  5814 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 08:05:06.985  5801  5814 D bt_hci  : start_up starting async portion
09-27 08:05:06.985  5801  5821 I bt_hci  : event_finish_startup
09-27 08:05:06.985  5801  5821 I bt_hci_h4: hal_open
09-27 08:05:06.985  5801  5821 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 08:05:06.982  5822  5822 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 08:05:06.988  5801  5821 I bt_userial_vendor: device fd = 54 open
,09-27 08:05:07.003  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:05:07.005  5801  5821 D bt_hwcfg: Chipset BCM4358A3
,09-27 08:05:07.005  5801  5821 D bt_hwcfg: Target name = [BCM4358A3]
09-27 08:05:07.006  5801  5821 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 08:05:07.254  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-27 08:05:07.410  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 08:05:07.411  5801  5821 D bt_hwcfg: Settlement delay -- 100 ms
,09-27 08:05:07.411  5801  5821 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 08:05:07.534  5801  5821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 08:05:07.534  5801  5821 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-27 08:05:07.536  5801  5821 I bt_hwcfg: vendor lib fwcfg completed
,09-27 08:05:07.536  5801  5821 I bt_vendor: firmware callback
,09-27 08:05:07.536  5801  5821 I bt_hci  : firmware_config_callback
,09-27 08:05:07.545  5801  5826 I bt_btu  : btu_task pending for preload complete event
,09-27 08:05:07.545  5801  5826 I bt_btu_task: Bluetooth chip preload is complete
,09-27 08:05:07.545  5801  5826 I bt_btu  : btu_task received preload complete event
,09-27 08:05:07.552  5801  5826 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 08:05:07.552  5801  5826 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 08:05:07.552  5801  5826 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 08:05:07.552  5801  5826 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_A2D
,09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_BNEP
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_PAN
,09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 08:05:07.553  5801  5826 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 08:05:07.554  5801  5826 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-27 08:05:07.554  5801  5826 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 08:05:07.633  5801  5826 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d93549
,09-27 08:05:07.634  5801  5826 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d93549 
,09-27 08:05:07.653  5801  5817 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 08:05:07.654  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 08:05:07.654  5801  5817 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-27 08:05:07.656  5801  5817 D BluetoothAdapterProperties: Name is: Nexus 6P
09-27 08:05:07.659  5801  5817 D BluetoothAdapterProperties: Scan Mode:20
09-27 08:05:07.659  5801  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 08:05:07.659  5801  5817 D bt_hci  : do_postload posting postload work item
,09-27 08:05:07.659  5801  5821 I bt_hci  : event_postload
09-27 08:05:07.659  5801  5821 I bt_vendor: sco_config_cb
09-27 08:05:07.659  5801  5821 I bt_hci  : sco_config_callback postload finished.
09-27 08:05:07.662  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:07.665  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:07.666  5801  5821 I bt_vendor: low_power_mode_cb
,09-27 08:05:07.667  5801  5817 D bt_bte_conf: Device ID record 1 : primary
,09-27 08:05:07.668  5801  5817 D bt_bte_conf:   vendorId            = 000f
09-27 08:05:07.668  5801  5817 D bt_bte_conf:   vendorIdSource      = 0001
09-27 08:05:07.668  5801  5817 D bt_bte_conf:   product             = 1200
09-27 08:05:07.668  5801  5817 D bt_bte_conf:   version             = 1436
09-27 08:05:07.668  5801  5817 D bt_bte_conf:   clientExecutableURL = 
09-27 08:05:07.668  5801  5817 D bt_bte_conf:   serviceDescription  = 
09-27 08:05:07.668  5801  5817 D bt_bte_conf:   documentationURL    = 
09-27 08:05:07.668  5801  5817 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 08:05:07.668  5801  5814 D bt_stack_manager: event_start_up_stack finished
09-27 08:05:07.669  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 08:05:07.669  5801  5813 D BluetoothAdapterProperties: Setting state to 15
09-27 08:05:07.669  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 08:05:07.671  5801  5813 I BluetoothAdapterState: Entering BleOnState
,09-27 08:05:07.674  5801  5813 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-27 08:05:07.674  5801  5813 D BluetoothAdapterProperties: Setting state to 11
09-27 08:05:07.674  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 08:05:07.678  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:07.680  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:07.682  5702  5713 D BluetoothHeadset: Proxy object connected
,09-27 08:05:07.683   926   926 D BluetoothHeadset: Proxy object connected
,09-27 08:05:07.683  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:07.683  3105  3952 D BluetoothHeadset: Proxy object connected
09-27 08:05:07.684   926   926 D BluetoothHeadset: Proxy object connected
09-27 08:05:07.684  3800  3827 D BluetoothHeadset: Proxy object connected
09-27 08:05:07.684  3105  3105 D HeadsetProfile: Bluetooth service connected
09-27 08:05:07.685   926   926 D BluetoothHeadset: Proxy object connected
09-27 08:05:07.685  5801  5801 D HeadsetService: Received start request. Starting profile...
09-27 08:05:07.687  5702  5702 D HeadsetProfile: Bluetooth service connected
09-27 08:05:07.687  5801  5801 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 08:05:07.688  5801  5801 D HeadsetStateMachine: make
,09-27 08:05:07.693  5801  5813 I BluetoothAdapterState: Entering PendingCommandState
,09-27 08:05:07.697  5801  5801 D HeadsetStateMachine: max_hf_connections = 1
,09-27 08:05:07.697  5801  5801 I bt_bluedroid: get_profile_interface handsfree
09-27 08:05:07.697  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 08:05:07.697  5801  5817 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-27 08:05:07.700  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:07.701  5801  5801 D A2dpService: Received start request. Starting profile...
09-27 08:05:07.701  5801  5801 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-27 08:05:07.701  5801  5801 I bt_bluedroid: get_profile_interface avrcp
,09-27 08:05:07.706  5801  5801 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 08:05:07.706  5801  5801 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 08:05:07.706  5801  5801 D A2dpStateMachine: make
09-27 08:05:07.707  5801  5801 I bt_bluedroid: get_profile_interface a2dp
,09-27 08:05:07.708  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-27 08:05:07.709  5801  5834 D A2dpStateMachine: Enter Disconnected: -2
,09-27 08:05:07.709  5801  5801 I BluetoothHidServiceJni: classInitNative: succeeds
09-27 08:05:07.710  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
09-27 08:05:07.710  5801  5801 D HidService: Received start request. Starting profile...
09-27 08:05:07.710  5801  5801 I bt_bluedroid: get_profile_interface hidhost
09-27 08:05:07.711  5801  5817 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d7456d
09-27 08:05:07.711  5801  5801 D HidService: setHidService(): set to: null
09-27 08:05:07.711  5801  5817 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 08:05:07.711  5801  5801 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 08:05:07.712  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:07.712  5801  5801 D HealthService: Received start request. Starting profile...
09-27 08:05:07.713  5801  5801 I bt_bluedroid: get_profile_interface health
09-27 08:05:07.714  5801  5801 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-27 08:05:07.715  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:07.715  5801  5801 D PanService: Received start request. Starting profile...
09-27 08:05:07.716  5801  5801 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 08:05:07.716  5801  5801 I bt_bluedroid: get_profile_interface pan
09-27 08:05:07.716  5801  5817 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 08:05:07.719  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:05:07.719  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:07.720  5801  5801 D BluetoothMapService: Received start request. Starting profile...
09-27 08:05:07.720  5801  5801 D BluetoothMapService: start()
,09-27 08:05:07.723  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-27 08:05:07.723  5801  5801 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 08:05:07.723  5801  5801 D BluetoothMapAppObserver: createReceiver()
09-27 08:05:07.724  5801  5801 D BluetoothMapAppObserver: initObservers()
09-27 08:05:07.724  5801  5801 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 08:05:07.731  5801  5801 V SapService: SapBinder()
,09-27 08:05:07.731  5801  5801 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:07.732  5801  5801 D SapService: Received start request. Starting profile...
,09-27 08:05:07.732  5801  5801 V SapService: start()
,09-27 08:05:07.735  5801  5801 V BluetoothAdapterState: isTurningOff()=false
,09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.736  5801  5832 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOn()=true
,09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOff()=false
,09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:07.736  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:07.737  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.737  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:07.737  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:07.737  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:07.737  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.737  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:07.738  5801  5801 V BluetoothAdapterState: isTurningOff()=false
09-27 08:05:07.738  5801  5801 V BluetoothAdapterState: isTurningOn()=true
09-27 08:05:07.739  5801  5801 V BluetoothAdapterState: isBleTurningOn()=false
09-27 08:05:07.739  5801  5801 V BluetoothAdapterState: isBleTurningOff()=false
09-27 08:05:07.739  5801  5813 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-27 08:05:07.739  5801  5813 D BluetoothAdapterProperties: ScanMode =  20
09-27 08:05:07.739  5801  5813 D BluetoothAdapterProperties: State =  11
09-27 08:05:07.742  5801  5817 D BluetoothAdapterProperties: Scan Mode:21
09-27 08:05:07.742  5801  5813 D BluetoothAdapterProperties: Setting state to 12
09-27 08:05:07.742  5801  5813 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 08:05:07.742  5801  5817 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 08:05:07.743  3800  5148 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:07.743  5702  5795 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:05:07.743  5801  5813 I BluetoothAdapterState: Entering OnState
09-27 08:05:07.745   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 08:05:07.745  3105  3117 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:07.746  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:07.748  3105  3952 D BluetoothPan: onBluetoothStateChange on: true
,09-27 08:05:07.749  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:07.750  3105  3117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:05:07.751  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 08:05:07.752   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:07.752  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:07.752  3105  3952 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 08:05:07.752  5801  5801 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-27 08:05:07.752  3105  3105 D BluetoothInputDevice: Proxy object connected
09-27 08:05:07.752  3105  3105 D HidProfile: Bluetooth service connected
09-27 08:05:07.753  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:07.753  5702  5702 D BluetoothA2dp: Proxy object connected
09-27 08:05:07.754  5702  5712 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:05:07.754  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:07.755  3105  3105 D BluetoothA2dp: Proxy object connected
09-27 08:05:07.756   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:07.756  5702  5795 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 08:05:07.756  5801  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:07.757  5801  5801 D ObexServerSockets: Succeed to create listening sockets 
09-27 08:05:07.757  5801  5801 D ObexServerSockets0: startAccept()
,09-27 08:05:07.757  5801  5801 D ObexServerSockets0: prepareForNewConnect()
09-27 08:05:07.757  3105  3117 D BluetoothMap: onBluetoothStateChange: up=true
09-27 08:05:07.759  5702  5713 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-27 08:05:07.759  5801  5801 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 08:05:07.759  5801  5801 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 08:05:07.759  5801  5841 D ObexServerSockets0: Accepting socket connection...
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:07.760  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:07.761  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
,09-27 08:05:07.761  3105  3105 D PanProfile: Bluetooth service connected
09-27 08:05:07.762   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 08:05:07.762  3105  3105 D BluetoothMap: Proxy object connected
09-27 08:05:07.762  3105  3105 D MapProfile: Bluetooth service connected
,09-27 08:05:07.762  3105  3105 D BluetoothMap: getConnectedDevices()
,09-27 08:05:07.762  5801  5842 D ObexServerSockets0: Accepting socket connection...
,09-27 08:05:07.762   926   926 D BluetoothA2dp: Proxy object connected
09-27 08:05:07.763  5702  5713 D BluetoothPan: onBluetoothStateChange on: true
09-27 08:05:07.763  5598  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:07.764  5598  5644 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,09-27 08:05:07.765   926  3124 D WifiService: setWifiEnabled: false pid=5598, uid=10077
09-27 08:05:07.765   926  3124 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 08:05:07.765  5702  5712 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:07.765  3105  3117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 08:05:07.766  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:07.766  5702  5702 D BluetoothInputDevice: Proxy object connected
09-27 08:05:07.766  5702  5702 D HidProfile: Bluetooth service connected
09-27 08:05:07.766   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 08:05:07.767   926   926 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-27 08:05:07.767  5801  5801 D BluetoothMapService: onReceive
09-27 08:05:07.767  5801  5801 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 08:05:07.767  5801  5801 D BluetoothMapService: STATE_ON
09-27 08:05:07.769  5702  5702 D BluetoothMap: Proxy object connected
09-27 08:05:07.769  5702  5702 D MapProfile: Bluetooth service connected
09-27 08:05:07.769  5702  5702 D BluetoothMap: getConnectedDevices()
09-27 08:05:07.769  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:07.772  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:07.773  5801  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:07.773  5702  5702 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 08:05:07.773  5702  5702 D PanProfile: Bluetooth service connected
09-27 08:05:07.774   926   926 D RttService: SCAN_AVAILABLE : 1
09-27 08:05:07.774   926  3057 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 08:05:07.775  5801  5843 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 08:05:07.775  5801  5843 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 08:05:07.778  5702  5702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 08:05:07.779   926  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:05:07.779   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:05:07.785   926  2949 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 08:05:07.786  5698  5698 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-27 08:05:07.787  3551  3551 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:07.793  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:07.794  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:07.797  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 08:05:07.798  3105  3105 D BluetoothPbap: Proxy object connected
09-27 08:05:07.798  3105  3105 D PbapServerProfile: Bluetooth service connected
09-27 08:05:07.799  5801  5801 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 08:05:07.799  5801  5801 D ObexServerSockets0: prepareForNewConnect()
09-27 08:05:07.799  5702  5702 D DockEventReceiver: finishStartingService: stopping service
09-27 08:05:07.800  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:07.800  5702  5702 D BluetoothPbap: Proxy object connected
09-27 08:05:07.800  5702  5702 D PbapServerProfile: Bluetooth service connected
,09-27 08:05:07.805  5698  5698 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-27 08:05:07.807  5801  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:05:07.821  5801  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:05:07.824  5801  5853 I BtOppRfcommListener: Accept thread started.
,09-27 08:05:07.828  5698  5698 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 08:05:07.838  5698  5698 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 08:05:07.940  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 08:05:07.940   926  2949 D wifi    : In wifi stop Hal
09-27 08:05:07.940   926  2949 D wifi    : halHandle = 0x7f89342f00, mVM = 0x7fa5a0d140, mCls = 0x2016b6
09-27 08:05:07.941   926  5697 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 08:05:07.941   926  5697 D WifiHAL : Got a signal to exit!!!
09-27 08:05:07.941   926  5697 I WifiHAL : Exit wifi_event_loop
09-27 08:05:07.942   926  2949 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-27 08:05:07.942   926  2949 E WifiHAL : Event processing terminated
09-27 08:05:07.942   926  2949 D wifi    : In wifi cleaned up handler
09-27 08:05:07.942   926  2949 I WifiHAL : Internal cleanup completed
,09-27 08:05:07.944  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:07.945  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:07.947  4049  4201 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 08:05:07.966   926  5697 D wifi    : set interface wlan0 flags (DOWN)
,09-27 08:05:07.966   926  2949 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 08:05:08.172   926   943 D Tethering: InitialState.processMessage what=4
,09-27 08:05:08.179   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:08.274  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:08.281  5598  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:08.284   926   936 D WifiService: setWifiEnabled: true pid=5598, uid=10077
,09-27 08:05:08.285   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-27 08:05:08.286  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:08.296   506   920 D SoftapController: Softap fwReload - Ok
,09-27 08:05:08.298   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:08.299   506   920 D CommandListener: Trying to bring down wlan0
,09-27 08:05:08.301   506   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 08:05:08.306   926  2949 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 08:05:08.798   926  3691 D WifiService: setWifiEnabled: true pid=5598, uid=10077
,09-27 08:05:08.804   926  3691 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:08.917   926  2949 D wifi    : set interface wlan0 flags (UP)
,09-27 08:05:08.917   926  2949 I WifiHAL : Initializing wifi
09-27 08:05:08.917   926  2949 I WifiHAL : Creating socket
,09-27 08:05:08.924   926  2949 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 08:05:08.925   926  2949 D wifi    : Did set static halHandle = 0x7f89342f00
09-27 08:05:08.925   926  2949 D wifi    : halHandle = 0x7f89342f00, mVM = 0x7fa5a0d140, mCls = 0xf52
09-27 08:05:08.925   926  2949 D wifi    : array field set
09-27 08:05:08.925   926  2949 I WifiNative-HAL: interface[0] = wlan0
09-27 08:05:08.929   926  5856 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547762745088
09-27 08:05:08.929   926  5856 D wifi    : waitForHalEvents called, vm = 0x7fa5a0d140, obj = 0xf52, env = 0x7f8e699fc0
,09-27 08:05:08.932   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 08:05:08.989  5857  5857 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 08:05:09.011  5857  5857 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:05:09.029   926  2949 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 08:05:09.038  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:09.042  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:09.054  5857  5857 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 08:05:09.055  5857  5857 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 08:05:09.068   926  2949 D WifiConfigStore: Loading config and enabling all networks 
,09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:09.074  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:09.076  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:09.080  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:09.081   926  2949 D WifiConfigStore: loaded 0 passpoint configs
09-27 08:05:09.081   926  2949 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 08:05:09.081   926  2949 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-27 08:05:09.082  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 08:05:09.082   926  2949 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-27 08:05:09.083   926  2949 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 08:05:09.084   926  2949 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 08:05:09.084   926  2949 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 08:05:09.084   926  2949 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 08:05:09.087   926  2949 D WifiNative-HAL: Setting external_sim to 1
,09-27 08:05:09.087  4978  4978 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 08:05:09.088   926  2949 D wifi    : setting dfs flag to true, 0x7f8bbde220
09-27 08:05:09.088   926  2949 D WifiStateMachine: Setting OUI to DA-A1-19
,09-27 08:05:09.089   926  2949 D wifi    : setting scan oui 0x7f8bbde220
09-27 08:05:09.089   926  2949 D WifiHAL : Sending mac address OUI
,09-27 08:05:09.093   926  2949 E native  : do suspend false
,09-27 08:05:09.100   926   926 D RttService: SCAN_AVAILABLE : 3
,09-27 08:05:09.101   926  2949 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 08:05:09.101   506   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 08:05:09.101   926  3057 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 08:05:09.102   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:09.105   926  2943 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
09-27 08:05:09.105   926  2943 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 08:05:09.114   926  2943 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 08:05:09.119   926  2943 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-27 08:05:09.119   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=247651 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:09.316  5598  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:09.321  5598  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:09.325  5598  5644 D BluetoothAdapter: enable(): BT is already enabled..!
09-27 08:05:09.326   926  3798 D WifiService: setWifiEnabled: true pid=5598, uid=10077
,09-27 08:05:09.326   926  3798 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 08:05:09.327  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 08:05:09.327  5598  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 08:05:09.328  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:05:09.328  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 08:05:09.328  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d27b842 removed from the list
09-27 08:05:09.328  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:05:09.328  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@919c053 removed from the list
09-27 08:05:09.329  5598  5644 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 08:05:09.329  5598  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 08:05:09.329  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 08:05:09.334  5598  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,09-27 08:05:09.338  5598  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-27 08:05:09.345  5598  5859 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-27 08:05:09.345  5598  5859 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 08:05:09.860  5598  5861 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-27 08:05:09.860  5598  5859 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-27 08:05:09.861  5598  5861 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:05:09.861  5598  5859 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:05:09.861  5598  5861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:05:09.861  5598  5859 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:05:09.862  5598  5859 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:05:09.862  5598  5861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:05:09.863  5598  5863 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Sender)
,09-27 08:05:09.864  5598  5859 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 08:05:09.864  5598  5861 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-27 08:05:09.865  5598  5864 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: OutgoingSocketThread/Sender)
,09-27 08:05:09.869  5598  5866 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
,09-27 08:05:09.869  5598  5865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Receiver)
,09-27 08:05:09.870  5598  5866 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
09-27 08:05:09.870  5598  5866 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 08:05:09.870  5598  5866 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 08:05:09.870  5598  5865 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: IncomingSocketThread/Receiver)
09-27 08:05:09.870  5598  5865 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 08:05:09.870  5598  5865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 08:05:10.349  5598  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-27 08:05:10.350  5598  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-27 08:05:10.353  5598  5644 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-27 08:05:10.357  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-27 08:05:10.358  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-27 08:05:10.360  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
09-27 08:05:10.360  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-27 08:05:10.362  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-27 08:05:10.366  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-27 08:05:10.366  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e15d4b5 Bundle[{}]
09-27 08:05:10.367  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,09-27 08:05:10.367  5598  5644 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 08:05:10.368  5598  5644 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-27 08:05:10.369  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-27 08:05:10.369  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-27 08:05:10.370  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-27 08:05:10.370  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-27 08:05:10.370  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,09-27 08:05:10.370  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-27 08:05:10.371  5598  5644 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
09-27 08:05:10.372  5598  5644 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-27 08:05:10.373  5598  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
09-27 08:05:10.375  5598  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-27 08:05:10.377  5598  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-27 08:05:10.378  5598  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,09-27 08:05:10.379  5598  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-27 08:05:10.380  5598  5644 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-27 08:05:10.382  5598  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-27 08:05:10.384  5598  5867 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-27 08:05:10.385  5598  5867 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 08:05:10.388  5598  5867 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-27 08:05:10.388  5598  5867 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:05:10.388  5598  5867 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:05:10.388  5598  5869 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-27 08:05:10.388  5598  5869 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 08:05:10.388  5598  5867 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 08:05:10.389  5598  5869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:05:10.389  5598  5867 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 08:05:10.390  5598  5870 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: OutgoingSocketThread/Sender)
,09-27 08:05:10.391  5598  5869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:05:10.392  5598  5871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: OutgoingSocketThread/Receiver)
09-27 08:05:10.392  5598  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: IncomingSocketThread/Sender)
09-27 08:05:10.392  5598  5869 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-27 08:05:10.392  5598  5871 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: OutgoingSocketThread/Receiver)
09-27 08:05:10.392  5598  5871 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 08:05:10.393  5598  5871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-27 08:05:10.393  5598  5873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: IncomingSocketThread/Receiver)
09-27 08:05:10.393  5598  5873 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: IncomingSocketThread/Receiver)
09-27 08:05:10.393  5598  5873 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 08:05:10.394  5598  5873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 08:05:10.889  5598  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-27 08:05:10.891  5598  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,09-27 08:05:10.893  5598  5644 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-27 08:05:10.897  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-27 08:05:10.899  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-27 08:05:10.901  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-27 08:05:10.901  5598  5644 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 188)
,09-27 08:05:10.903  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
09-27 08:05:10.903  5598  5644 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-27 08:05:10.904  5598  5644 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 189)
09-27 08:05:10.906  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-27 08:05:10.907  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-27 08:05:10.908  5598  5644 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,09-27 08:05:10.909  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 08:05:10.909  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17c2bc added. We now have 3 listener(s)
09-27 08:05:10.911  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:10.911  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 08:05:10.911  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 08:05:10.912  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 08:05:10.912  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb6245 added. We now have 3 listener(s)
09-27 08:05:10.912  5598  5644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 08:05:10.913  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 08:05:10.917  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 08:05:10.922  5598  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 08:05:10.925  5598  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 08:05:10.925  5598  5644 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 08:05:10.928  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 08:05:10.930  5598  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
09-27 08:05:10.930  5598  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-27 08:05:10.930  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 08:05:10.931  5598  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-27 08:05:10.931  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-27 08:05:10.931  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:10.931  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 08:05:10.931  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:05:10.931  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:05:10.932  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 08:05:10.933  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-27 08:05:10.933  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 08:05:10.933  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:05:10.933  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 08:05:10.933  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 08:05:10.933  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:10.933  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 08:05:10.934  5598  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 08:05:10.932  5812  5812 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[34824]" dev="sockfs" ino=34824 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 08:05:10.936  5812  5812 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34824]" dev="sockfs" ino=34824 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:05:10.939  5598  5874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 08:05:10.941  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 08:05:10.941  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:05:10.945  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:05:10.946  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 08:05:10.946  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 08:05:10.949  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 08:05:10.949  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:10.949  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-27 08:05:10.950  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:10.950  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:10.950  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-27 08:05:10.950  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:10.953  5801  5812 D BtGatt.GattService: registerClient() - UUID=6d7c9fcd-9055-4acc-b930-f5c142d8377a
09-27 08:05:10.955  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=6d7c9fcd-9055-4acc-b930-f5c142d8377a, clientIf=5
,09-27 08:05:10.956  5598  5727 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 08:05:10.958  5801  5819 D BtGatt.AdvertiseManager: message : 0
,09-27 08:05:10.960  5801  5819 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 08:05:10.971  5801  5817 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 08:05:10.977  5801  5817 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 08:05:10.978  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 08:05:10.978  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 08:05:10.980  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 08:05:10.981  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:10.981  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 08:05:10.981  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:05:10.981  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 08:05:10.981  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 08:05:10.981  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-27 08:05:10.984  5598  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 08:05:10.984  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 08:05:11.485  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 08:05:11.485  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:05:11.486  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:05:12.329   926  2949 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 08:05:12.330   926  2949 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-27 08:05:12.331   926  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:05:12.343   926  2949 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 08:05:12.376   926  2949 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 08:05:12.378  5857  5857 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 08:05:12.821  5857  5857 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 08:05:12.862  5857  5857 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 08:05:12.863  5857  5857 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 08:05:12.873   926  2949 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 08:05:12.873   926  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 08:05:12.873   926  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 08:05:12.892   926  2949 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 08:05:12.905   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:12.911   926  2949 D WifiStateMachine: Start Dhcp Watchdog 2
,09-27 08:05:12.918   926  5879 D DhcpClient: Receive thread started
,09-27 08:05:12.922   926  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:05:12.923   926  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 08:05:12.923   926  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-27 08:05:13.005   926  2949 E native  : do suspend false
,09-27 08:05:13.021   926  5878 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 08:05:13.034   926  5879 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172590, domain null
,09-27 08:05:13.035   926  5878 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172590 seconds
,09-27 08:05:13.037   926  5878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 08:05:13.059   926  5879 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 08:05:13.060   926  5878 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 08:05:13.063   506   920 D CommandListener: Setting iface cfg
,09-27 08:05:13.068   926  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 08:05:13.074   926  5878 D DhcpClient: Scheduling renewal in 86399s
,09-27 08:05:13.083   926  2949 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 08:05:13.085   926  2949 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 08:05:13.086   926  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-27 08:05:13.091   926  2949 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-27 08:05:13.094   926  2951 D ConnectivityService: Adding iface wlan0 to network 101
,09-27 08:05:13.134   926  2951 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 08:05:13.135   926  2951 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-27 08:05:13.138   926  2951 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-27 08:05:13.139   926  2951 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-27 08:05:13.140   926  2951 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-27 08:05:13.148   926  2951 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:05:13.153   926  2951 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-27 08:05:13.153   926  2951 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-27 08:05:13.153   926  2951 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-27 08:05:13.153   926  2951 D ConnectivityService:    accepting network in place of null
09-27 08:05:13.153   926  2949 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 08:05:13.153   926  2949 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 08:05:13.154   926  2951 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 08:05:13.167   926  5877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=251699, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 08:05:13.178   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:05:13.199   506   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 08:05:13.202   926  2951 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-27 08:05:13.202   926  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 08:05:13.202  3747  3887 W QCNEJ   : |CORE| network available: 101
,09-27 08:05:13.203   926  2951 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-27 08:05:13.206   926   943 D Tethering: MasterInitialState.processMessage what=3
09-27 08:05:13.207  3747  3887 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 08:05:13.209  3747  3887 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 08:05:13.209  3747  3887 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:05:13.215  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 08:05:13.218  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:13.218  5012  5036 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 08:05:13.218  5012  5036 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 08:05:13.218  5012  5036 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-27 08:05:13.218  5012  5036 E SarControlService: no key has been found,reset the power
,09-27 08:05:13.218  5012  5048 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-27 08:05:13.219  5012  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 08:05:13.219  5012  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 08:05:13.219  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:05:13.219  5037  5037 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 08:05:13.220  5012  5048 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-27 08:05:13.220  5012  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 08:05:13.221  5012  5048 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 08:05:13.222  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 08:05:13.223  3705  3705 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:05:13.224  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:05:13.225  5037  5037 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 08:05:13.227  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 08:05:13.229  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f71abc1 HexData = [00000000ec03000000000000ffffffff]
,09-27 08:05:13.230  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 08:05:13.230  5037  5051 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-27 08:05:13.230  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:05:13.230  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 08:05:13.232  3705  3705 D SystemUpdateService: onCreate
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 08:05:13.233  5598  5598 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 08:05:13.233  3892  3892 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-27 08:05:13.235  5598  5598 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 08:05:13.236  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@f71abc1 HexData = [00000000ed03000000000000ffffffff]
09-27 08:05:13.237  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 08:05:13.237  5037  5051 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-27 08:05:13.237  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 08:05:13.237  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 08:05:13.238  3705  3705 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 08:05:13.249  3705  3705 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 08:05:13.255  3705  5375 I iu.UploadsManager: num queued entries: 0
,09-27 08:05:13.255  3705  5375 I iu.UploadsManager: num updated entries: 0
09-27 08:05:13.255  3705  5375 I iu.SyncManager: NEXT; no task
,09-27 08:05:13.258  3705  5889 I SystemUpdateService: active receiver: enabled
,09-27 08:05:13.260  3705  3705 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-27 08:05:13.260   926  5876 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 08:05:13.261  3705  3705 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 08:05:13.263  5377  5377 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 08:05:13.267  5377  5377 D SprintDMHelper: simOperator: 
09-27 08:05:13.267  5377  5377 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 08:05:13.292  3705  5889 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 08:05:13.304  3705  5889 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-27 08:05:13.304  3705  5889 I SystemUpdateService: now status is 0 (complete)
09-27 08:05:13.304  3705  5889 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 08:05:13.304  3705  5889 I SystemUpdateService: file has been verified
09-27 08:05:13.305  3705  5889 I SystemUpdateService: OTA package size = 21989297
,09-27 08:05:13.309  3705  5889 I SystemUpdateService: showing system update notification
,09-27 08:05:13.318  3705  3705 D SystemUpdateService: onDestroy
,09-27 08:05:13.322   926  5876 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 12:05:13 GMT], X-Android-Received-Millis=[1474977913321], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474977913283]}
,09-27 08:05:13.322   926  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-27 08:05:13.323   926  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-27 08:05:13.323   926  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:05:13.324   926  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-27 08:05:13.386  4978  5894 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-27 08:05:14.203   926  2951 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-27 08:05:14.483  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-27 08:05:14.483  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 08:05:14.484  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 08:05:14.484  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 08:05:14.484  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:05:14.485  5598  5874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:05:14.485  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 08:05:14.485  5598  5874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:05:14.485  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-27 08:05:14.485  5598  5874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:05:14.485  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 08:05:14.485  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:05:14.485  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-27 08:05:14.486  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 08:05:14.486  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:05:14.486  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-27 08:05:14.489  5598  5644 D BluetoothAdapter: STATE_ON
,09-27 08:05:14.490  5598  5644 D BluetoothLeScanner: could not find callback wrapper
09-27 08:05:14.490  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-27 08:05:14.490  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 08:05:14.493  5801  5819 D BtGatt.AdvertiseManager: message : 1
,09-27 08:05:14.494  5801  5819 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 08:05:14.507  5801  5817 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 08:05:14.507  5801  5817 D BtGatt.GattService: Client app is not null!
09-27 08:05:14.508  5801  5844 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 08:05:14.509  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 08:05:14.509  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-27 08:05:14.509  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 08:05:14.510  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 08:05:14.510  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-27 08:05:14.512  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:14.512  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:05:14.512  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:05:14.513  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 08:05:14.516  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 08:05:14.516  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-27 08:05:14.516  5598  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-27 08:05:14.516  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:14.516  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:14.516  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 08:05:14.520  5598  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,09-27 08:05:14.520  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 08:05:14.522  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 08:05:14.522  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 08:05:14.523  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-27 08:05:14.523  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 08:05:14.523  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 08:05:14.528  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:05:14.529  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 08:05:14.534  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 08:05:14.535  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 08:05:14.535  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 08:05:14.542  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 08:05:14.543  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 08:05:14.544  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 08:05:14.545  5598  5644 D BluetoothAdapter: STATE_ON
,09-27 08:05:14.549  5801  5844 D BtGatt.GattService: registerClient() - UUID=9c8b0f72-2104-4eaf-a7fc-ebeb961f904c
,09-27 08:05:14.550  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=9c8b0f72-2104-4eaf-a7fc-ebeb961f904c, clientIf=5
09-27 08:05:14.550  5598  5608 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 08:05:14.552  5801  5811 D BtGatt.GattService: start scan with filters
,09-27 08:05:14.557  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 08:05:14.557  5801  5820 D BtGatt.ScanManager: handling starting scan
09-27 08:05:14.558  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 08:05:14.558  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-27 08:05:14.558  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 08:05:14.560  5801  5820 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aaab53e
,09-27 08:05:14.562  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 08:05:14.562  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:05:14.562  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 08:05:14.564  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 08:05:14.570  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-27 08:05:14.570  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:14.571  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 08:05:14.578  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 08:05:14.578  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:14.579  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:05:14.579  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 08:05:14.590  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 08:05:14.590  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:14.596  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-27 08:05:14.596  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:15.063  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 08:05:15.064  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:05:15.064  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:05:15.933   926  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:05:16.123   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:17.124   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:17.570  5598  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-27 08:05:17.570  5598  5644 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-27 08:05:17.571  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-27 08:05:17.572  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 08:05:17.572  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 08:05:17.575  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:17.577  5801  5844 D BtGatt.GattService: stopScan() - queue size =1
,09-27 08:05:17.580  5801  5811 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:05:17.581  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:05:17.581  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 08:05:17.581  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 08:05:17.582  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 08:05:17.582  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 08:05:17.582  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-27 08:05:17.586  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:17.589  5801  5801 D BtGatt.ScanManager: awakened up at time 256121
,09-27 08:05:17.594  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 08:05:17.594  5801  5811 D BtGatt.GattService: registerClient() - UUID=717c2f60-1931-43e1-b5b6-3b3413d74887
,09-27 08:05:17.594  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:17.595  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:05:17.597  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=717c2f60-1931-43e1-b5b6-3b3413d74887, clientIf=5
09-27 08:05:17.597  5598  5609 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 08:05:17.598  5801  5839 D BtGatt.GattService: start scan with filters
09-27 08:05:17.603  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 08:05:17.603  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-27 08:05:17.603  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:17.604  5598  5644 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-27 08:05:17.604  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 08:05:17.604  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 08:05:17.606  5812  5812 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31411]" dev="sockfs" ino=31411 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:05:17.606  5812  5812 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31411]" dev="sockfs" ino=31411 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-27 08:05:17.605  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 08:05:17.605  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 08:05:17.605  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:17.606  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 08:05:17.606  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 08:05:17.606  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 08:05:17.606  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 08:05:17.606  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 08:05:17.606  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 08:05:17.606  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 08:05:17.606  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 08:05:17.607  5598  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 08:05:17.607  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:17.607  5801  5844 D BtGatt.GattService: stopScan() - queue size =0
,09-27 08:05:17.608  5801  5811 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:05:17.609  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:05:17.609  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 08:05:17.609  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 08:05:17.609  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 08:05:17.609  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 08:05:17.609  5598  5902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-27 08:05:17.610  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:17.612  5598  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 08:05:17.614  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-27 08:05:17.614  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 08:05:17.614  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-27 08:05:17.614  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-27 08:05:17.614  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 08:05:17.614  5598  5644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-27 08:05:17.621  5598  5644 D BluetoothAdapter: STATE_ON
,09-27 08:05:17.623  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-27 08:05:17.623  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:17.624  5801  5817 D BtGatt.GattService: current time is 256156023834
09-27 08:05:17.624  5801  5817 D BtGatt.GattService: Batch record : [-4, 82, 120, -3, -117, 99, 1, -128, -70, 37, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 116, -43, -111, -91, -20, -29, 1, -128, -88, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -76, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -76, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -71, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 08:05:17.624  5801  5811 D BtGatt.GattService: registerClient() - UUID=b710a4b8-15e3-48e6-b3c7-c1b650d30689
09-27 08:05:17.625  5801  5820 D BtGatt.ScanManager: handling starting scan
09-27 08:05:17.625  5801  5817 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
09-27 08:05:17.626  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 08:05:17.626  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 08:05:17.626  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 08:05:17.627  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 08:05:17.627  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 3,5, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 08:05:17.627  5801  5817 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-27 08:05:17.627  5801  5817 E BtGatt.ContextMap: Context not found for ID 5
09-27 08:05:17.627  5801  5817 D BtGatt.GattService: onClientRegistered() - UUID=b710a4b8-15e3-48e6-b3c7-c1b650d30689, clientIf=5
09-27 08:05:17.628  5598  5608 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 08:05:17.629  5801  5819 D BtGatt.AdvertiseManager: message : 0
,09-27 08:05:17.633  5801  5817 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 08:05:17.633  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:17.633  5801  5820 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-27 08:05:17.633  5801  5819 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 08:05:17.638  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 08:05:17.638  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:17.639  5801  5820 D BtGatt.ScanManager: Starting BLE batch scan
09-27 08:05:17.639  5801  5820 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 08:05:17.648  5801  5817 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 08:05:17.657  5801  5817 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 08:05:17.657  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:17.662  5801  5817 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 08:05:17.662  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-27 08:05:17.662  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 08:05:17.664  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 08:05:17.665  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:17.665  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:17.665  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 08:05:17.665  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 08:05:17.665  5598  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-27 08:05:17.666  5598  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 08:05:17.666  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 08:05:17.668  5598  5598 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-27 08:05:17.668  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 08:05:17.669  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 08:05:17.669  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:17.675  5801  5817 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-27 08:05:17.675  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:17.676  5801  5820 D BtGatt.ScanManager: stopping BLe Batch
,09-27 08:05:17.680  5801  5817 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 08:05:17.681  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 08:05:17.681  5801  5820 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 08:05:17.686  5801  5817 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-27 08:05:17.686  5801  5817 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 08:05:18.125   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:18.169  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 08:05:18.170  5598  5598 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 08:05:18.170  5598  5598 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 08:05:18.964   926  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 08:05:19.126   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:19.755   926  2949 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 16 -> obsolete
,09-27 08:05:20.127   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 08:05:21.128   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 08:05:21.155   926  2951 D ConnectivityService: handlePromptUnvalidated 101
,09-27 08:05:21.169  5598  5644 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-27 08:05:21.170  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 08:05:21.170  5598  5644 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 08:05:21.170  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-27 08:05:21.170  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 08:05:21.171  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 08:05:21.171  5598  5902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 08:05:21.171  5598  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-27 08:05:21.171  5598  5902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 08:05:21.171  5598  5902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 08:05:21.171  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-27 08:05:21.172  5598  5598 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 08:05:21.172  5598  5644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c17c2bc removed from the list
,09-27 08:05:21.172  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 08:05:21.172  5598  5598 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 08:05:21.172  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 08:05:21.172  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-27 08:05:21.172  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 08:05:21.172  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 08:05:21.175  5598  5644 D BluetoothAdapter: STATE_ON
09-27 08:05:21.175  5598  5644 D BluetoothLeScanner: could not find callback wrapper
,09-27 08:05:21.175  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 08:05:21.175  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 08:05:21.177  5801  5819 D BtGatt.AdvertiseManager: message : 1
09-27 08:05:21.179  5801  5819 D BtGatt.AdvertiseManager: stop advertise for client 5
09-27 08:05:21.192  5801  5817 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-27 08:05:21.193  5801  5817 D BtGatt.GattService: Client app is not null!
09-27 08:05:21.194  5801  5831 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 08:05:21.195  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 08:05:21.195  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 08:05:21.195  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 08:05:21.195  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-27 08:05:21.195  5598  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 08:05:21.197  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:21.197  5598  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 08:05:21.197  5598  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 08:05:21.199  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 08:05:21.201  5598  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdb6245 removed from the list
,09-27 08:05:21.201  5598  5644 D io.jxcore.node.ConnectivityMonitor: stop
09-27 08:05:21.201  5598  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 08:05:21.201  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 08:05:21.202  5598  5598 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 08:05:21.202  5598  5598 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 08:05:21.204  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-27 08:05:21.205  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-27 08:05:21.205  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-27 08:05:21.205  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-27 08:05:21.205  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 08:05:21.205  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-27 08:05:21.206  5598  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 08:05:21.207  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
09-27 08:05:21.209  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-27 08:05:21.211  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,09-27 08:05:21.213  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,09-27 08:05:21.215  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,09-27 08:05:21.216  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-27 08:05:21.217  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
09-27 08:05:21.219  5598  5644 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
09-27 08:05:21.220  5598  5644 I StreamCopyingThreadTest: Starting test: testRun
,09-27 08:05:21.223  5598  5905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 202, name: My test thread name)
,09-27 08:05:21.703  5598  5598 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 08:05:22.892  5598  5905 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 202
,09-27 08:05:22.892  5598  5905 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 202, name: My test thread name)
09-27 08:05:22.893  5598  5905 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 202, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-27 08:05:23.228  5598  5644 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-27 08:05:23.232  5598  5907 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: My test thread name)
,09-27 08:05:23.232  5598  5907 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 204, thread name: My test thread name)
09-27 08:05:23.232  5598  5907 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-27 08:05:23.235  5598  5644 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-27 08:05:23.236  5598  5644 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 08:05:23.239  5598  5644 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-27 08:05:23.242  5598  5908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 208, name: My test thread name)
,09-27 08:05:23.243  5598  5908 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 208, thread name: My test thread name): Test exception.
09-27 08:05:23.243  5598  5908 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 208, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-27 08:05:23.248  5598  5644 I jxcore-log: *Native tests were executed*
09-27 08:05:23.248  5598  5644 I jxcore-log: 
,09-27 08:05:23.249  5598  5644 I jxcore-log: Total number of executed tests:  82
09-27 08:05:23.249  5598  5644 I jxcore-log: 
,09-27 08:05:23.249  5598  5644 I jxcore-log: Number of passed tests:  82
09-27 08:05:23.249  5598  5644 I jxcore-log: 
,09-27 08:05:23.250  5598  5644 I jxcore-log: Number of failed tests:  0
09-27 08:05:23.250  5598  5644 I jxcore-log: 
09-27 08:05:23.250  5598  5644 I jxcore-log: Number of ignored tests:  0
09-27 08:05:23.250  5598  5644 I jxcore-log: 
09-27 08:05:23.251  5598  5644 I jxcore-log: Total duration:  22456
09-27 08:05:23.251  5598  5644 I jxcore-log: 
09-27 08:05:23.251  5598  5644 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-27 08:05:23.251  5598  5644 I jxcore-log: 
,09-27 08:05:23.258  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.258  5598  5644 I jxcore-log: 
09-27 08:05:23.265  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.265  5598  5644 I jxcore-log: 
09-27 08:05:23.267  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.267  5598  5644 I jxcore-log: 
09-27 08:05:23.269  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 08:05:23.269  5598  5644 I jxcore-log: 
09-27 08:05:23.270  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 08:05:23.270  5598  5644 I jxcore-log: 
09-27 08:05:23.272  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 08:05:23.272  5598  5644 I jxcore-log: 
09-27 08:05:23.274  5598  5598 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-27 08:05:23.276  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.276  5598  5644 I jxcore-log: 
,09-27 08:05:23.279  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 08:05:23.279  5598  5644 I jxcore-log: 
09-27 08:05:23.280  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 08:05:23.280  5598  5644 I jxcore-log: 
09-27 08:05:23.281  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 08:05:23.281  5598  5644 I jxcore-log: 
,09-27 08:05:23.283  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-27 08:05:23.283  5598  5644 I jxcore-log: 
,09-27 08:05:23.284  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.284  5598  5644 I jxcore-log: 
,09-27 08:05:23.285  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.285  5598  5644 I jxcore-log: 
,09-27 08:05:23.286  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.286  5598  5644 I jxcore-log: 
09-27 08:05:23.287  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.287  5598  5644 I jxcore-log: 
09-27 08:05:23.289  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.289  5598  5644 I jxcore-log: 
09-27 08:05:23.289  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.289  5598  5644 I jxcore-log: 
09-27 08:05:23.290  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.290  5598  5644 I jxcore-log: 
09-27 08:05:23.290  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.290  5598  5644 I jxcore-log: 
09-27 08:05:23.291  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.291  5598  5644 I jxcore-log: 
,09-27 08:05:23.291  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.291  5598  5644 I jxcore-log: 
09-27 08:05:23.292  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.292  5598  5644 I jxcore-log: 
09-27 08:05:23.293  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.293  5598  5644 I jxcore-log: 
,09-27 08:05:23.295  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.295  5598  5644 I jxcore-log: 
09-27 08:05:23.295  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.295  5598  5644 I jxcore-log: 
,09-27 08:05:23.296  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.296  5598  5644 I jxcore-log: 
,09-27 08:05:23.297  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 08:05:23.297  5598  5644 I jxcore-log: 
,09-27 08:05:23.298  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 08:05:23.298  5598  5644 I jxcore-log: 
,09-27 08:05:23.299  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-27 08:05:23.299  5598  5644 I jxcore-log: 
09-27 08:05:23.300  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.300  5598  5644 I jxcore-log: 
09-27 08:05:23.301  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.301  5598  5644 I jxcore-log: 
09-27 08:05:23.301  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.301  5598  5644 I jxcore-log: 
,09-27 08:05:23.302  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-27 08:05:23.302  5598  5644 I jxcore-log: 
,09-27 08:05:23.303  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 08:05:23.303  5598  5644 I jxcore-log: 
09-27 08:05:23.304  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.304  5598  5644 I jxcore-log: 
09-27 08:05:23.305  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.305  5598  5644 I jxcore-log: 
,09-27 08:05:23.306  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-27 08:05:23.306  5598  5644 I jxcore-log: 
,09-27 08:05:23.307  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-27 08:05:23.307  5598  5644 I jxcore-log: 
,09-27 08:05:23.308  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-27 08:05:23.308  5598  5644 I jxcore-log: 
,09-27 08:05:23.309  5598  5644 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-27 08:05:23.309  5598  5644 I jxcore-log: 
,09-27 08:05:23.753  5909  5909 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-27 08:05:23.759  5909  5909 D AndroidRuntime: CheckJNI is OFF
,09-27 08:05:23.783  5909  5909 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-27 08:05:23.811  5909  5909 I Radio-JNI: register_android_hardware_Radio DONE
,09-27 08:05:23.828  5909  5909 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-27 08:05:23.834   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-27 08:05:23.834   926   939 I ActivityManager: Killing 5598:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-27 08:05:23.880   926  3125 I WindowState: WIN DEATH: Window{733a2a5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-27 08:05:23.880   926  3691 D GraphicsStats: Buffer count: 2
09-27 08:05:23.880   926  2950 D WifiService: Client connection lost with reason: 4
,09-27 08:05:23.966   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-27 08:05:23.966   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-27 08:05:23.967   926   939 E ActivityManager: Failure starting process com.test.thalitest
09-27 08:05:23.967   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-27 08:05:23.967   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:23.967   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:23.967   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 08:05:23.967   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-27 08:05:23.968   926   939 I ActivityManager:   Force finishing activity ActivityRecord{950540e u0 com.test.thalitest/.MainActivity t2}
,09-27 08:05:23.969   926   949 I art     : Starting a blocking GC Explicit
,09-27 08:05:23.974   926  3734 W ActivityManager: Spurious death for ProcessRecord{5df19ff 0:com.test.thalitest/u0a77}, curProc for 5598: null
,09-27 08:05:23.979   926   944 W WindowManager: Attempted to add application window with unknown token Token{1a43e2f ActivityRecord{950540e u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-27 08:05:23.979   926   944 W WindowManager: Token{1a43e2f ActivityRecord{950540e u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{1a43e2f ActivityRecord{950540e u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-27 08:05:23.979   926   944 W WindowManager: view not successfully added to wm, removing view
09-27 08:05:23.980   926   944 W WindowManager: Exception when adding starting window
09-27 08:05:23.980   926   944 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{84191f6 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-27 08:05:23.980   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-27 08:05:23.980   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-27 08:05:23.980   926   944 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-27 08:05:23.980   926   944 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-27 08:05:23.980   926   944 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-27 08:05:23.980   926   944 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:23.980   926   944 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:23.980   926   944 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 08:05:23.980   926   944 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-27 08:05:24.055   926   949 I art     : Explicit concurrent mark sweep GC freed 21629(1324KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.630ms total 85.348ms
,09-27 08:05:24.077   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-27 08:05:24.080  5909  5909 I art     : System.exit called, status: 0
,09-27 08:05:24.080  5909  5909 I AndroidRuntime: VM exiting with result code 0.
,09-27 08:05:24.086   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-27 08:05:24.096   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-27 08:05:24.100  3633  3633 I Keyboard.Facilitator: resetDictionaries() : en_US
09-27 08:05:24.103  5801  5801 D BluetoothMapAppObserver: onReceive
09-27 08:05:24.103  5801  5801 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-27 08:05:24.108   926  2915 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-27 08:05:24.114   926  2949 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,09-27 08:05:24.123  4049  4171 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-27 08:05:24.136  3633  5920 I Keyboard.Facilitator.DecoderInitializer: run()
,09-27 08:05:24.134  3370  5921 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-27 08:05:24.160  3800  3800 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-27 08:05:24.161  3551  3551 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-27 08:05:24.161  3551  3551 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-27 08:05:24.163  3633  5920 I Decoder : createOrResetDecoder
09-27 08:05:24.165   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-27 08:05:24.166    64    64 W kworker/2:2: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-27 08:05:24.169    64    64 W kworker/2:2: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 08:05:24.179  3836  3934 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-27 08:05:24.186  3705  5926 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-27 08:05:24.187  3705  5926 D AccountUtils: Clearing selected account for com.test.thalitest
,09-27 08:05:24.179    64    64 W kworker/2:2: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 08:05:24.193   926  3798 I ActivityManager: Start proc 5927:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-27 08:05:24.193  3836  3934 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-27 08:05:24.193  3836  3934 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3836
09-27 08:05:24.193  3836  3934 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:24.193  3836  3934 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 08:05:24.197   926  5936 E DropBoxManagerService: Can't write: system_app_crash
09-27 08:05:24.197   926  5936 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 08:05:24.197   926  5936 E DropBoxManagerService: 	... 5 more
,09-27 08:05:24.198   926  3734 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-27 08:05:24.204  3836  3934 I Process : Sending signal. PID: 3836 SIG: 9
,09-27 08:05:24.231  3370  3394 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj9D403B90C) - 
,09-27 08:05:24.240  3551  3551 I ConfigService: onCreate
,09-27 08:05:24.243  3551  5942 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 08:05:24.243  3551  5942 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-27 08:05:24.243  3551  5942 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-27 08:05:24.245  3551  5942 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-27 08:05:24.262  3705  5926 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-27 08:05:24.273  3633  5920 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-27 08:05:24.289  3705  5926 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:24.289  3705  5926 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:24.290  3705  5926 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-27 08:05:24.291  3705  5926 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-27 08:05:24.316  3370  3394 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-27 08:05:24.316  3370  3394 E AndroidRuntime: Process: android.process.acore, PID: 3370
09-27 08:05:24.316  3370  3394 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-27 08:05:24.316  3370  3394 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-27 08:05:24.336   926  3565 D GraphicsStats: Buffer count: 1
09-27 08:05:24.336   926   936 I WindowState: WIN DEATH: Window{d53462a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-27 08:05:24.341   926   937 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3836) has died
,09-27 08:05:24.342   926   937 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-27 08:05:24.342  3370  3394 I Process : Sending signal. PID: 3370 SIG: 9
,09-27 08:05:24.387  3705  5948 I GMPM-SVC: App measurement is starting up
,09-27 08:05:24.392  3705  5948 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-27 08:05:24.397  3705  5948 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-27 08:05:24.561   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
