#### Test 8559402588149d6_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of system
09-19 10:10:46.443   924  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-19 10:10:46.736   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 10:10:48.549  5541  5541 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 10:10:48.555  5541  5541 D AndroidRuntime: CheckJNI is OFF
09-19 10:10:48.583  5541  5541 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 10:10:48.620  5541  5541 I Radio-JNI: register_android_hardware_Radio DONE
09-19 10:10:48.637  5541  5541 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-19 10:10:48.643   924  3782 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-19 10:10:48.680   924  3782 I ActivityManager: Start proc 5550:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-19 10:10:48.708  5541  5541 D AndroidRuntime: Shutting down VM
,09-19 10:10:49.033   924   935 I WindowManager: Screenshot max retries 4 of Token{c2b38ba ActivityRecord{101c5e5 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{b6bcc9d u0 Starting com.test.thalitest} drawState=2
,09-19 10:10:49.107  5550  5550 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-19 10:10:49.137  5550  5550 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-19 10:10:49.159  5550  5550 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 6887-6904)
,09-19 10:10:49.159  5550  5550 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-19 10:10:49.178  5550  5550 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fe25d5c}
,09-19 10:10:49.178  5550  5550 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-19 10:10:49.179  5550  5550 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-19 10:10:49.183  5550  5550 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-19 10:10:49.184  5550  5550 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-19 10:10:49.217  5550  5550 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-19 10:10:49.232  5550  5550 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-19 10:10:49.232  5550  5550 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 10:10:49.232  5550  5550 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-19 10:10:49.232  5550  5550 I Adreno  : Build Date                       : 12/06/15
09-19 10:10:49.232  5550  5550 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-19 10:10:49.232  5550  5550 I Adreno  : Local Branch                     : mybranch17112971
09-19 10:10:49.232  5550  5550 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-19 10:10:49.232  5550  5550 I Adreno  : Remote Branch                    : NONE
09-19 10:10:49.232  5550  5550 I Adreno  : Reconstruct Branch               : NOTHING
,09-19 10:10:49.273   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c8f255:true
,09-19 10:10:49.307   409   409 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26229]" dev="sockfs" ino=26229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 10:10:49.307   409   409 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26229]" dev="sockfs" ino=26229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 10:10:49.321  5550  5550 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-19 10:10:49.329  5550  5550 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-19 10:10:49.356  5550  5587 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-19 10:10:49.354   409   409 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30328]" dev="sockfs" ino=30328 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 10:10:49.354   409   409 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30328]" dev="sockfs" ino=30328 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 10:10:49.357   934   934 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26240]" dev="sockfs" ino=26240 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 10:10:49.357   934   934 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[26240]" dev="sockfs" ino=26240 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 10:10:49.362  5550  5574 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-19 10:10:49.383  5550  5587 I OpenGLRenderer: Initialized EGL, version 1.4
,09-19 10:10:49.454   924   942 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +416ms (total +799ms)
,09-19 10:10:49.464   924  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-19 10:10:49.499  5550  5550 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5550
,09-19 10:10:49.587  5550  5550 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-19 10:10:49.720  5550  5589 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -581437136
,09-19 10:10:49.723  5550  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-19 10:10:49.723  5550  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-19 10:10:49.723  5550  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-19 10:10:49.723  5550  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-19 10:10:49.723  5550  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-19 10:10:49.723  5550  5589 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5260dd added. We now have 1 listener(s)
,09-19 10:10:49.725  5550  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-19 10:10:49.726  5550  5589 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 10:10:49.726  5550  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 10:10:49.727  5550  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-19 10:10:49.728  5550  5589 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24df020 added. We now have 1 listener(s)
09-19 10:10:49.728  5550  5589 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 10:10:49.734   924  2897 D WifiService: New client listening to asynchronous messages
,09-19 10:10:49.734  5550  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 10:10:49.735  5550  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-19 10:10:49.735  5550  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-19 10:10:49.735  5550  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-19 10:10:49.735  5550  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-19 10:10:49.737  5550  5589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 10:10:49.737  5550  5589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-19 10:10:49.742  5550  5589 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 10:10:49.742  5550  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 10:10:49.742  5550  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-19 10:10:49.743  5550  5589 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 10:10:49.743  5550  5589 I io.jxcore.node.LifeCycleMonitor: start: OK
09-19 10:10:49.746  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 10:10:49.749  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 10:10:49.761  5550  5550 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-19 10:10:50.068  5550  5596 W jxcore-log: Initializing JXcore engine
09-19 10:10:50.068  5550  5596 W jxcore-log: JXcore engine is ready
,09-19 10:10:50.090  5596  5596 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1282 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-19 10:10:50.090  5596  5596 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13426]" dev="sockfs" ino=13426 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-19 10:10:50.090  5596  5596 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-19 10:10:50.090  5596  5596 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30305]" dev="sockfs" ino=30305 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-19 10:10:50.100  5550  5596 W jxcore-log: Starting JXcore engine
,09-19 10:10:50.148  5550  5596 W jxcore-log: Platform android
09-19 10:10:50.148  5550  5596 W jxcore-log: 
09-19 10:10:50.149  5550  5596 W jxcore-log: Process ARCH arm
09-19 10:10:50.149  5550  5596 W jxcore-log: 
,09-19 10:10:50.246  5550  5596 I jxcore-log: JXcore Cordova bridge is ready!
09-19 10:10:50.246  5550  5596 I jxcore-log: 
09-19 10:10:50.247  5550  5596 W jxcore-log: JXcore engine is started
,09-19 10:10:50.253  5550  5589 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-19 10:10:50.256  5550  5550 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-19 10:10:52.486   924  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-19 10:10:55.509   924  2898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-19 10:10:56.738   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 10:10:57.739   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 10:10:58.740   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 10:10:59.660  5550  5596 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-19 10:10:59.660  5550  5596 I jxcore-log: 
,09-19 10:10:59.662  5550  5596 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-19 10:10:59.662  5550  5596 I jxcore-log: 
,09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 10:10:59.665  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 10:10:59.667  5550  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 10:10:59.668  5550  5596 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-19 10:10:59.668  5550  5596 I jxcore-log: 
,09-19 10:10:59.670  5550  5596 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-19 10:10:59.670  5550  5596 I jxcore-log: 
,09-19 10:10:59.741   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 10:10:59.913  5550  5596 I jxcore-log: Running unit tests
09-19 10:10:59.913  5550  5596 I jxcore-log: 
,09-19 10:10:59.913  5550  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 10:10:59.913  5550  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256a81e added. We now have 2 listener(s)
,09-19 10:10:59.914  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 10:10:59.914  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 10:10:59.914  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-19 10:10:59.914  5550  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 10:10:59.914  5550  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b52e8ff added. We now have 2 listener(s)
09-19 10:10:59.914  5550  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 10:10:59.915  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 10:10:59.917  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 10:10:59.920  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 10:10:59.921  5550  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.921  5550  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 10:10:59.921  5550  5596 D executeNativeTests: Running unit tests
,09-19 10:10:59.928  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 10:10:59.933  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 10:10:59.962  5550  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 10:10:59.962  5550  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe46585 added. We now have 3 listener(s)
09-19 10:10:59.963  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 10:10:59.963  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 10:10:59.963  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-19 10:10:59.963  5550  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 10:10:59.963  5550  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda added. We now have 3 listener(s)
09-19 10:10:59.963  5550  5596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 10:10:59.963  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 10:10:59.965  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 10:10:59.967  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 10:10:59.968  5550  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.968  5550  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 10:10:59.969  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-19 10:10:59.969  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 10:10:59.969  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 10:10:59.969  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 10:10:59.970  5550  5596 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-19 10:10:59.970  5550  5596 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-19 10:10:59.970  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 10:10:59.970  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-19 10:10:59.970  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 10:10:59.970  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 10:10:59.970  5550  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 10:10:59.971  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 10:10:59.971  5550  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 10:10:59.971  5550  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 10:10:59.971  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 10:10:59.971  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 10:10:59.971  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 10:10:59.971  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 10:10:59.971  5550  5596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe46585 removed from the list
09-19 10:10:59.972  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:10:59.972  5550  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda removed from the list
,09-19 10:10:59.974  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 10:10:59.974  5550  5596 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 10:10:59.974  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.975  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 10:10:59.975  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.975  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 10:10:59.975  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 10:10:59.975  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:10:59.976  5550  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda not in the list
09-19 10:10:59.976  5550  5596 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-19 10:10:59.977  5550  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 10:10:59.977  5550  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 10:10:59.977  5550  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 10:10:59.977  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 10:10:59.977  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 10:10:59.977  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.977  5550  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe46585 not in the list
09-19 10:10:59.977  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:10:59.977  5550  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda not in the list
,09-19 10:10:59.977  5550  5596 D io.jxcore.node.ConnectivityMonitor: stop
09-19 10:10:59.977  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 10:10:59.977  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.977  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 10:10:59.977  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.978  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 10:10:59.978  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 10:10:59.978  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:10:59.978  5550  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda not in the list
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-19 10:10:59.980  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-19 10:10:59.981  5550  5596 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-19 10:10:59.981  5550  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 10:10:59.981  5550  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 10:10:59.981  5550  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 10:10:59.981  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 10:10:59.981  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 10:10:59.981  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.982  5550  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe46585 not in the list
09-19 10:10:59.982  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:10:59.982  5550  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda not in the list
09-19 10:10:59.982  5550  5596 D io.jxcore.node.ConnectivityMonitor: stop
09-19 10:10:59.982  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 10:10:59.982  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.982  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 10:10:59.982  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:10:59.982  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 10:10:59.982  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 10:10:59.982  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:10:59.982  5550  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda not in the list
09-19 10:10:59.983  5550  5596 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-19 10:10:59.984  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 10:10:59.986  5550  5596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 10:10:59.987  5550  5596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 10:10:59.987  5550  5596 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 10:10:59.987  5550  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 10:10:59.987  5550  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 10:10:59.987  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 10:10:59.987  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 10:10:59.987  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 10:10:59.989  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 10:10:59.990  5550  5550 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 10:10:59.991  5550  5596 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 10:10:59.991  5550  5596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 10:10:59.993  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-19 10:10:59.994  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 10:10:59.994  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 10:10:59.995  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-19 10:10:59.996  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-19 10:10:59.996  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-19 10:10:59.997  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 10:10:59.997  5550  5596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-19 10:10:59.997  5550  5596 D BluetoothAdapter: STATE_ON
09-19 10:10:59.999  4536  4550 D BtGatt.GattService: registerClient() - UUID=e16236ce-cf8d-4fd1-99b6-1dee1b59a1ac
09-19 10:11:00.000  4536  4597 D BtGatt.GattService: onClientRegistered() - UUID=e16236ce-cf8d-4fd1-99b6-1dee1b59a1ac, clientIf=5
09-19 10:11:00.000  5550  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-19 10:11:00.001  4536  4743 D BtGatt.GattService: start scan with filters
09-19 10:11:00.006  4536  4602 D BtGatt.ScanManager: handling starting scan
09-19 10:11:00.007  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 10:11:00.007  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-19 10:11:00.007  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 10:11:00.007  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-19 10:11:00.008  4536  4602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a6a09c7
09-19 10:11:00.009  5550  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 10:11:00.009  5550  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 10:11:00.009  5550  5550 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 10:11:00.009  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 10:11:00.011  5550  5596 I io.jxcore.node.ConnectionHelper: start: OK
09-19 10:11:00.015  4536  4597 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 10:11:00.015  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 10:11:00.015  4536  4602 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-19 10:11:00.022  4536  4597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-19 10:11:00.022  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 10:11:00.023  4536  4602 D BtGatt.ScanManager: Starting BLE batch scan
09-19 10:11:00.023  4536  4602 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-19 10:11:00.033  4536  4597 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-19 10:11:00.033  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 10:11:00.039  4536  4597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-19 10:11:00.039  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 10:11:00.510  5550  5550 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-19 10:11:00.511  5550  5550 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-19 10:11:00.511  5550  5550 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-19 10:11:00.742   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 10:11:01.743   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 10:11:03.493   924  2893 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 10:11:05.015  5550  5596 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 10:11:05.015  5550  5596 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 10:11:05.015  5550  5596 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 10:11:05.015  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 10:11:05.015  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-19 10:11:05.015  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-19 10:11:05.015  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 10:11:05.016  5550  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 10:11:05.016  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 10:11:05.016  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 10:11:05.017  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-19 10:11:05.018  5550  5596 D BluetoothAdapter: STATE_ON
09-19 10:11:05.019  4536  4743 D BtGatt.GattService: stopScan() - queue size =1
09-19 10:11:05.021  4536  4754 D BtGatt.GattService: unregisterClient() - clientIf=5
09-19 10:11:05.022  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-19 10:11:05.022  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 10:11:05.022  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 10:11:05.022  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 10:11:05.023  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 10:11:05.025  5550  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-19 10:11:05.026  4536  4536 D BtGatt.ScanManager: awakened up at time 262771
09-19 10:11:05.026  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-19 10:11:05.026  5550  5596 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 10:11:05.026  5550  5596 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 10:11:05.031  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 10:11:05.033  4536  4597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-19 10:11:05.033  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 10:11:05.034  4536  4602 D BtGatt.ScanManager: stopping BLe Batch
09-19 10:11:05.035  5550  5596 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 10:11:05.035  5550  5550 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 10:11:05.035  5550  5596 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 10:11:05.035  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 10:11:05.035  5550  5550 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 10:11:05.035  5550  5596 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe46585 not in the list
09-19 10:11:05.035  5550  5550 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 10:11:05.035  5550  5596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 10:11:05.035  5550  5596 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50befda not in the list
09-19 10:11:05.035  5550  5596 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 10:11:05.035  5550  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 10:11:05.042  4536  4597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 10:11:05.042  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 10:11:05.042  4536  4602 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-19 10:11:05.059  4536  4597 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-19 10:11:05.060  4536  4597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 10:11:05.060  4536  4597 D BtGatt.GattService: current time is 262805972839
09-19 10:11:05.060  4536  4597 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -78, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -75, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -95, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -94, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-19 10:11:05.061  4536  4597 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-19 10:11:05.063  4536  4597 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-19 10:11:05.063  4536  4597 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-19 10:11:05.064  4536  4597 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-19 10:11:05.064  4536  4597 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-19 10:11:05.064  4536  4597 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]

```
