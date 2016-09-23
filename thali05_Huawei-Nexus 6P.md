#### Test 85046911b09b63d_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 03:56:25.516   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 03:56:27.311  5429  5429 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 03:56:27.317  5429  5429 D AndroidRuntime: CheckJNI is OFF
09-23 03:56:27.348  5429  5429 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 03:56:27.384  5429  5429 I Radio-JNI: register_android_hardware_Radio DONE
09-23 03:56:27.399  5429  5429 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 03:56:27.402   928  3206 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 03:56:27.442   928  3206 I ActivityManager: Start proc 5439:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 03:56:27.457  5429  5429 D AndroidRuntime: Shutting down VM
,09-23 03:56:27.785   928  3766 I WindowManager: Screenshot max retries 4 of Token{809cce ActivityRecord{4049dc9 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{4ad3d01 u0 Starting com.test.thalitest} drawState=2
,09-23 03:56:27.852  5439  5439 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 03:56:27.885  5439  5439 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 03:56:27.952  5439  5439 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 1195-1258)
,09-23 03:56:27.952  5439  5439 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 03:56:27.976  5439  5439 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {54a93ab}
,09-23 03:56:27.976  5439  5439 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 03:56:27.976  5439  5439 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 03:56:27.980  5439  5439 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 03:56:27.981  5439  5439 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 03:56:28.032  5439  5439 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 03:56:28.043  5439  5439 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 03:56:28.043  5439  5439 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 03:56:28.043  5439  5439 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 03:56:28.043  5439  5439 I Adreno  : Build Date                       : 12/06/15
09-23 03:56:28.043  5439  5439 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 03:56:28.043  5439  5439 I Adreno  : Local Branch                     : mybranch17112971
09-23 03:56:28.043  5439  5439 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 03:56:28.043  5439  5439 I Adreno  : Remote Branch                    : NONE
09-23 03:56:28.043  5439  5439 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 03:56:28.080   928   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5c8732c:true
,09-23 03:56:28.104   405   405 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13983]" dev="sockfs" ino=13983 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 03:56:28.104   405   405 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[13983]" dev="sockfs" ino=13983 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 03:56:28.113  5439  5439 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 03:56:28.121  5439  5439 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 03:56:28.141   405   405 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31945]" dev="sockfs" ino=31945 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 03:56:28.141   405   405 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31945]" dev="sockfs" ino=31945 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 03:56:28.143  5439  5476 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 03:56:28.144  3432  3432 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32830]" dev="sockfs" ino=32830 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 03:56:28.144  3432  3432 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32830]" dev="sockfs" ino=32830 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 03:56:28.148  5439  5463 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 03:56:28.182  5439  5476 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 03:56:28.264   928   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +477ms (total +848ms)
,09-23 03:56:28.288  5439  5439 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5439
,09-23 03:56:28.377  5439  5439 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 03:56:28.510  5439  5479 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -582743760
,09-23 03:56:28.515  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 03:56:28.515  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 03:56:28.515  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 03:56:28.515  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 03:56:28.515  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 03:56:28.515  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8dfee0 added. We now have 1 listener(s)
,09-23 03:56:28.518  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 03:56:28.518  5439  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 03:56:28.519  5439  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 03:56:28.519  5439  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-23 03:56:28.521  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf5dc3f added. We now have 1 listener(s)
09-23 03:56:28.522  5439  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 03:56:28.526   928  2968 D WifiService: New client listening to asynchronous messages
,09-23 03:56:28.526  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 03:56:28.527  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 03:56:28.527  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 03:56:28.527  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 03:56:28.527  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 03:56:28.529  5439  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 03:56:28.529  5439  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 03:56:28.534  5439  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 03:56:28.534  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 03:56:28.534  5439  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-23 03:56:28.534  5439  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 03:56:28.535  5439  5479 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 03:56:28.536  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:56:28.539  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:56:28.550  5439  5439 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 03:56:28.838  5439  5485 W jxcore-log: Initializing JXcore engine
09-23 03:56:28.838  5439  5485 W jxcore-log: JXcore engine is ready
,09-23 03:56:28.861  5485  5485 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11776 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 03:56:28.861  5485  5485 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13502]" dev="sockfs" ino=13502 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 03:56:28.861  5485  5485 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 03:56:28.861  5485  5485 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31921]" dev="sockfs" ino=31921 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 03:56:28.869  5439  5485 W jxcore-log: Starting JXcore engine
,09-23 03:56:28.926  5439  5485 W jxcore-log: Platform android
09-23 03:56:28.926  5439  5485 W jxcore-log: 
09-23 03:56:28.926  5439  5485 W jxcore-log: Process ARCH arm
09-23 03:56:28.926  5439  5485 W jxcore-log: 
,09-23 03:56:29.031  5439  5485 I jxcore-log: JXcore Cordova bridge is ready!
09-23 03:56:29.031  5439  5485 I jxcore-log: 
,09-23 03:56:29.031  5439  5485 W jxcore-log: JXcore engine is started
,09-23 03:56:29.040  5439  5479 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 03:56:29.045  5439  5439 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 03:56:35.772  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 03:56:35.772  5439  5485 I jxcore-log: 
,09-23 03:56:35.774  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 03:56:35.774  5439  5485 I jxcore-log: 
,09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 03:56:35.778  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 03:56:35.779  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 03:56:35.781  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 03:56:35.781  5439  5485 I jxcore-log: 
,09-23 03:56:35.782  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 03:56:35.782  5439  5485 I jxcore-log: 
,09-23 03:56:36.145  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 03:56:36.145  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0c097b added. We now have 2 listener(s)
,09-23 03:56:36.146  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 03:56:36.146  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 03:56:36.146  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 03:56:36.146  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 03:56:36.146  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f25b398 added. We now have 2 listener(s)
,09-23 03:56:36.146  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 03:56:36.147  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 03:56:36.149  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 03:56:36.152  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 03:56:36.153  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 03:56:36.153  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 03:56:36.153  5439  5485 D ExecuteNativeTests: Running unit tests
09-23 03:56:36.154  5439  5485 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 03:56:36.155   928  3432 D WifiService: setWifiEnabled: true pid=5439, uid=10077
09-23 03:56:36.155   928  3432 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 03:56:36.159  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:56:36.165  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 03:56:37.481   928  2958 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 03:56:41.065   928  5188 D NetlinkSocketObserver: NeighborEvent{elapsedMs=184370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 03:56:45.518   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 03:56:46.162  5439  5485 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 03:56:46.191  5439  5485 I jxcore-log: *Native tests were executed*
09-23 03:56:46.191  5439  5485 I jxcore-log: 
,09-23 03:56:46.192  5439  5485 I jxcore-log: Total number of executed tests:  1
09-23 03:56:46.192  5439  5485 I jxcore-log: 
09-23 03:56:46.192  5439  5485 I jxcore-log: Number of passed tests:  1
09-23 03:56:46.192  5439  5485 I jxcore-log: 
09-23 03:56:46.192  5439  5485 I jxcore-log: Number of failed tests:  0
09-23 03:56:46.192  5439  5485 I jxcore-log: 
,09-23 03:56:46.192  5439  5485 I jxcore-log: Number of ignored tests:  0
09-23 03:56:46.192  5439  5485 I jxcore-log: 
09-23 03:56:46.193  5439  5485 I jxcore-log: Total duration:  2
09-23 03:56:46.193  5439  5485 I jxcore-log: 
09-23 03:56:46.193  5439  5485 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 03:56:46.193  5439  5485 I jxcore-log: 
09-23 03:56:46.196  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 03:56:46.196  5439  5485 I jxcore-log: 
,09-23 03:56:46.198  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 03:56:46.198  5439  5485 I jxcore-log: 
,09-23 03:56:46.228  5439  5439 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 03:56:46.519   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 03:56:46.787  5487  5487 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 03:56:46.810  5487  5487 D AndroidRuntime: CheckJNI is OFF
,09-23 03:56:46.839  5487  5487 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 03:56:46.867  5487  5487 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 03:56:46.883  5487  5487 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 03:56:46.893   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-23 03:56:46.893   928   941 I ActivityManager: Killing 5439:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 03:56:46.965   928  3766 I WindowState: WIN DEATH: Window{b64ff5c u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-23 03:56:46.966   928  2968 D WifiService: Client connection lost with reason: 4
09-23 03:56:46.966   928  3584 D GraphicsStats: Buffer count: 2
,09-23 03:56:47.017   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-23 03:56:47.017   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-23 03:56:47.018   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-23 03:56:47.018   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 03:56:47.018   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:56:47.018   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.018   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:56:47.018   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 03:56:47.019   928   941 I ActivityManager:   Force finishing activity ActivityRecord{4049dc9 u0 com.test.thalitest/.MainActivity t2}
09-23 03:56:47.020   928   954 I art     : Starting a blocking GC Explicit
,09-23 03:56:47.025   928  3206 W ActivityManager: Spurious death for ProcessRecord{61beade 0:com.test.thalitest/u0a77}, curProc for 5439: null
,09-23 03:56:47.033   928   947 W WindowManager: Failed looking up window
09-23 03:56:47.033   928   947 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@e00078 does not exist
09-23 03:56:47.033   928   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
09-23 03:56:47.033   928   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
09-23 03:56:47.033   928   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:3104)
09-23 03:56:47.033   928   947 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:198)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:5423)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1589)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1115)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6023)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:606)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.033   928   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:56:47.033   928   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 03:56:47.036   928   947 W WindowManager: Failed looking up window
09-23 03:56:47.036   928   947 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@e00078 does not exist
09-23 03:56:47.036   928   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
09-23 03:56:47.036   928   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
09-23 03:56:47.036   928   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
09-23 03:56:47.036   928   947 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
09-23 03:56:47.036   928   947 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
09-23 03:56:47.036   928   947 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
09-23 03:56:47.036   928   947 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
09-23 03:56:47.036   928   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:56:47.036   928   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.036   928   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:56:47.036   928   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 03:56:47.107   928   954 I art     : Explicit concurrent mark sweep GC freed 57030(4MB) AllocSpace objects, 22(568KB) LOS objects, 33% free, 28MB/43MB, paused 1.531ms total 85.713ms
,09-23 03:56:47.130   928   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 03:56:47.134  5487  5487 I art     : System.exit called, status: 0
09-23 03:56:47.134  5487  5487 I AndroidRuntime: VM exiting with result code 0.
,09-23 03:56:47.140   928   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 03:56:47.153   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-23 03:56:47.157  4453  4453 D BluetoothMapAppObserver: onReceive
,09-23 03:56:47.157  4453  4453 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-23 03:56:47.164  3607  3962 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-23 03:56:47.165  3400  3400 I Keyboard.Facilitator: resetDictionaries() : en_US
09-23 03:56:47.174   928  2934 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 03:56:47.191  3400  5498 I Keyboard.Facilitator.DecoderInitializer: run()
,09-23 03:56:47.216  3400  5498 I Decoder : createOrResetDecoder
,09-23 03:56:47.220  3506  3506 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 03:56:47.228  3586  3586 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-23 03:56:47.228  3586  3586 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 03:56:47.231    28    28 W kworker/2:1: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 03:56:47.234    28    28 W kworker/2:1: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 03:56:47.247    28    28 W kworker/2:1: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 03:56:47.244  3413  5501 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-23 03:56:47.252  3535  3665 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-23 03:56:47.252   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-23 03:56:47.252   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-23 03:56:47.253   928   940 E PackageManager: Failed to write settings, restoring backup
09-23 03:56:47.253   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-23 03:56:47.253   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-23 03:56:47.253   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-23 03:56:47.253   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-23 03:56:47.253   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-23 03:56:47.253   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:56:47.253   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.253   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 03:56:47.255  3911  5504 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-23 03:56:47.255  3911  5504 D AccountUtils: Clearing selected account for com.test.thalitest
09-23 03:56:47.256   928   941 E DropBoxManagerService: Can't write: system_server_wtf
09-23 03:56:47.256   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 03:56:47.256   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 03:56:47.256   928   941 E DropBoxManagerService: 	... 13 more
,09-23 03:56:47.266   928  3776 I ActivityManager: Start proc 5506:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-23 03:56:47.267  3535  3665 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-23 03:56:47.267  3535  3665 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3535
09-23 03:56:47.267  3535  3665 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.267  3535  3665 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 03:56:47.270   928  3152 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 03:56:47.272   928  5512 E DropBoxManagerService: Can't write: system_app_crash
09-23 03:56:47.272   928  5512 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 03:56:47.272   928  5512 E DropBoxManagerService: 	... 5 more
,09-23 03:56:47.275  3535  3665 I Process : Sending signal. PID: 3535 SIG: 9
,09-23 03:56:47.291  3413  3430 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjC86C3198A) - 
,09-23 03:56:47.292  3586  3586 I ConfigService: onCreate
09-23 03:56:47.292  3413  3430 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-23 03:56:47.292  3413  3430 E AndroidRuntime: Process: android.process.acore, PID: 3413
09-23 03:56:47.292  3413  3430 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.292  3413  3430 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 03:56:47.294   928  5521 E DropBoxManagerService: Can't write: system_app_crash
09-23 03:56:47.294   928  5521 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 03:56:47.294   928  5521 E DropBoxManagerService: 	... 5 more
,09-23 03:56:47.295  3586  5520 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 03:56:47.295  3586  5520 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 03:56:47.295  3586  5520 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-23 03:56:47.297  3586  5520 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-23 03:56:47.312  3400  5498 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-23 03:56:47.338  3911  5504 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-23 03:56:47.371  3911  5504 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.371  3911  5504 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-23 03:56:47.371  3911  5504 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 03:56:47.372  3911  5504 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-23 03:56:47.377  3413  5501 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-23 03:56:47.378  3413  5501 I Process : Sending signal. PID: 3413 SIG: 9
,09-23 03:56:47.406   928  2933 W InputDispatcher: channel '8c401db com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-23 03:56:47.406   928  2933 E InputDispatcher: channel '8c401db com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-23 03:56:47.407   928  3776 D GraphicsStats: Buffer count: 1
09-23 03:56:47.408   928  3776 I WindowState: WIN DEATH: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
09-23 03:56:47.408   928  3776 W InputDispatcher: Attempted to unregister already unregistered input channel '8c401db com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-23 03:56:47.423   928  3118 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3535) has died
09-23 03:56:47.424   928  3118 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-23 03:56:47.436   928   947 E WindowState: getStack: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{73d5130 token=Token{cdfbe73 ActivityRecord{fac5ae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,09-23 03:56:47.437   928   947 E WindowState: getStack: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{73d5130 token=Token{cdfbe73 ActivityRecord{fac5ae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
09-23 03:56:47.437   928   947 E WindowState: getStack: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{73d5130 token=Token{cdfbe73 ActivityRecord{fac5ae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
09-23 03:56:47.437   928   947 E WindowState: getStack: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{73d5130 token=Token{cdfbe73 ActivityRecord{fac5ae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-23 03:56:47.437   928   947 E WindowState: getStack: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{73d5130 token=Token{cdfbe73 ActivityRecord{fac5ae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-23 03:56:47.438   928   947 E WindowState: getStack: Window{8c401db u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{73d5130 token=Token{cdfbe73 ActivityRecord{fac5ae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,09-23 03:56:47.469  3911  5526 I GMPM-SVC: App measurement is starting up
09-23 03:56:47.473  3911  5526 E GMPM-SVC: AppMeasurementService not registered/enabled
09-23 03:56:47.474  3911  5526 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-23 03:56:47.489   928   939 I ActivityManager: Process android.process.acore (pid 3413) has died,
09-23 03:56:47.489   928   939 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-23 03:56:47.520   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 03:56:47.644   382   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
