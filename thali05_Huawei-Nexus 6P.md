#### Test 86955080ed241b1_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-28 09:44:42.023   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 09:44:42.023   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 09:44:42.543  5622  5622 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 09:44:42.548  5622  5622 D AndroidRuntime: CheckJNI is OFF
09-28 09:44:42.576  5622  5622 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 09:44:42.611  5622  5622 I Radio-JNI: register_android_hardware_Radio DONE
09-28 09:44:42.626  5622  5622 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-28 09:44:42.632   926  4761 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 09:44:42.666   926  4761 I ActivityManager: Start proc 5631:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 09:44:42.672  5622  5622 D AndroidRuntime: Shutting down VM
,09-28 09:44:43.012   926  3401 I WindowManager: Screenshot max retries 4 of Token{7fe7d6e ActivityRecord{9811ce9 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{b168021 u0 Starting com.test.thalitest} drawState=2
,09-28 09:44:43.073  5631  5631 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 09:44:43.106  5631  5631 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 09:44:43.130  5631  5631 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 599-617)
09-28 09:44:43.130  5631  5631 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 09:44:43.149  5631  5631 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b5a3d8}
,09-28 09:44:43.149  5631  5631 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 09:44:43.150  5631  5631 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 09:44:43.155  5631  5631 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-28 09:44:43.156  5631  5631 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 09:44:43.189  5631  5631 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 09:44:43.203  5631  5631 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 09:44:43.203  5631  5631 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 09:44:43.204  5631  5631 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 09:44:43.204  5631  5631 I Adreno  : Build Date                       : 12/06/15
09-28 09:44:43.204  5631  5631 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 09:44:43.204  5631  5631 I Adreno  : Local Branch                     : mybranch17112971
09-28 09:44:43.204  5631  5631 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 09:44:43.204  5631  5631 I Adreno  : Remote Branch                    : NONE
09-28 09:44:43.204  5631  5631 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 09:44:43.258   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7357ccc:true
,09-28 09:44:43.291   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15913]" dev="sockfs" ino=15913 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 09:44:43.291   403   403 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15913]" dev="sockfs" ino=15913 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 09:44:43.308  5631  5631 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 09:44:43.318  5631  5631 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 09:44:43.348  5631  5668 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-28 09:44:43.345  3439  3439 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33111]" dev="sockfs" ino=33111 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-28 09:44:43.345  3439  3439 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33111]" dev="sockfs" ino=33111 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 09:44:43.351  3776  3776 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24489]" dev="sockfs" ino=24489 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 09:44:43.351  3776  3776 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24489]" dev="sockfs" ino=24489 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 09:44:43.356  5631  5655 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 09:44:43.377  5631  5668 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 09:44:43.459   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +445ms (total +814ms)
,09-28 09:44:43.489  5631  5631 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5631
,09-28 09:44:43.546   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:44:43.576  5631  5631 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 09:44:43.700  5631  5671 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -560461520
,09-28 09:44:43.704  5631  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 09:44:43.704  5631  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 09:44:43.704  5631  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 09:44:43.704  5631  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 09:44:43.704  5631  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-28 09:44:43.704  5631  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fd6529 added. We now have 1 listener(s)
,09-28 09:44:43.706  5631  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-28 09:44:43.707  5631  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:44:43.707  5631  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 09:44:43.707  5631  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-28 09:44:43.710  5631  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7bc9dc added. We now have 1 listener(s)
09-28 09:44:43.710  5631  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:44:43.716   926  2981 D WifiService: New client listening to asynchronous messages
,09-28 09:44:43.716  5631  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 09:44:43.716  5631  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 09:44:43.716  5631  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 09:44:43.716  5631  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-28 09:44:43.716  5631  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-28 09:44:43.718  5631  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:44:43.718  5631  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 09:44:43.721  5631  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:44:43.721  5631  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:44:43.721  5631  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-28 09:44:43.722  5631  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:44:43.722  5631  5671 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 09:44:43.724  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:43.727  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:43.741  5631  5631 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 09:44:44.040  5631  5677 W jxcore-log: Initializing JXcore engine
09-28 09:44:44.040  5631  5677 W jxcore-log: JXcore engine is ready
,09-28 09:44:44.065  5677  5677 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12904 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-28 09:44:44.065  5677  5677 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13336]" dev="sockfs" ino=13336 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-28 09:44:44.065  5677  5677 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-28 09:44:44.065  5677  5677 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32235]" dev="sockfs" ino=32235 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 09:44:44.075  5631  5677 W jxcore-log: Starting JXcore engine
,09-28 09:44:44.134  5631  5677 W jxcore-log: Platform android
09-28 09:44:44.134  5631  5677 W jxcore-log: 
,09-28 09:44:44.135  5631  5677 W jxcore-log: Process ARCH arm
09-28 09:44:44.135  5631  5677 W jxcore-log: 
,09-28 09:44:44.232  5631  5677 I jxcore-log: JXcore Cordova bridge is ready!
09-28 09:44:44.232  5631  5677 I jxcore-log: 
,09-28 09:44:44.232  5631  5677 W jxcore-log: JXcore engine is started
,09-28 09:44:44.243  5631  5671 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 09:44:44.249  5631  5631 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 09:44:52.024   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:44:53.026   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:44:54.028   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:44:54.029  5631  5677 I jxcore-log: 2016-09-28 13:44:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 09:44:54.029  5631  5677 I jxcore-log: 
,09-28 09:44:54.030  5631  5677 I jxcore-log: 2016-09-28 13:44:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 09:44:54.030  5631  5677 I jxcore-log: 
,09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:44:54.034  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:44:54.036  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:44:54.037  5631  5677 I jxcore-log: 2016-09-28 13:44:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 09:44:54.037  5631  5677 I jxcore-log: 
,09-28 09:44:54.039  5631  5677 I jxcore-log: 2016-09-28 13:44:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 09:44:54.039  5631  5677 I jxcore-log: 
,09-28 09:44:54.291  5631  5677 I jxcore-log: 2016-09-28 13:44:54 - DEBUG UnitTest_app: 'Running unit tests'
09-28 09:44:54.291  5631  5677 I jxcore-log: 
,09-28 09:44:54.291  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 09:44:54.291  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7718ff0 added. We now have 2 listener(s)
09-28 09:44:54.292  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:44:54.292  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 09:44:54.292  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:44:54.292  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:44:54.292  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d59969 added. We now have 2 listener(s)
09-28 09:44:54.292  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:44:54.293  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 09:44:54.294  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:44:54.296  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:44:54.298  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:44:54.299  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:44:54.300  5631  5677 D executeNativeTests: Running unit tests
,09-28 09:44:54.305  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:54.310  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:54.336  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 09:44:54.336  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f added. We now have 3 listener(s)
09-28 09:44:54.336  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:44:54.336  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:44:54.336  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:44:54.336  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:44:54.336  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c added. We now have 3 listener(s)
,09-28 09:44:54.337  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:44:54.337  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 09:44:54.338  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:44:54.341  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:44:54.341  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:44:54.342  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:44:54.343  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 09:44:54.343  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:44:54.343  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:44:54.343  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:44:54.344  5631  5677 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-28 09:44:54.344  5631  5677 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-28 09:44:54.344  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 09:44:54.344  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:44:54.344  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:44:54.344  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:44:54.344  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:44:54.345  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:44:54.345  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:44:54.345  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:44:54.345  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:54.345  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:44:54.345  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:44:54.345  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f removed from the list
09-28 09:44:54.345  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:44:54.345  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c removed from the list
,09-28 09:44:54.350  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:54.353  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:54.353  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:44:54.353  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.354  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:44:54.354  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:44:54.355  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:44:54.355  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:44:54.355  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:44:54.355  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:44:54.356  5631  5677 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-28 09:44:54.356  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:44:54.356  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:44:54.356  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:44:54.356  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:44:54.356  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:54.356  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.356  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:44:54.356  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:44:54.356  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:44:54.356  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:44:54.356  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:54.356  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.356  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:54.356  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.357  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:44:54.357  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:44:54.357  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:44:54.357  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:44:54.359  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 09:44:54.359  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 09:44:54.359  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 09:44:54.359  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-28 09:44:54.359  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 09:44:54.359  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 09:44:54.360  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 09:44:54.360  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:44:54.360  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:44:54.360  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:44:54.361  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:44:54.361  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:54.361  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.361  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:44:54.361  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:44:54.361  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:44:54.361  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:44:54.361  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:54.361  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.361  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:44:54.361  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:44:54.361  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:44:54.361  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:44:54.361  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:44:54.361  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:44:54.362  5631  5677 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 09:44:54.363  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:44:54.365  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:44:54.366  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:44:54.366  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:44:54.366  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:44:54.366  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:44:54.367  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:44:54.367  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:44:54.367  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:44:54.368  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:44:54.368  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:44:54.370  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:44:54.372  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:44:54.372  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:44:54.373  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:44:54.373  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 09:44:54.374  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-28 09:44:54.375  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-28 09:44:54.375  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 09:44:54.375  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:44:54.375  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 09:44:54.376  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:44:54.378  4575  4818 D BtGatt.GattService: registerClient() - UUID=b0886aba-4246-4759-88e5-7124481e8b1a
,09-28 09:44:54.378  4575  4659 D BtGatt.GattService: onClientRegistered() - UUID=b0886aba-4246-4759-88e5-7124481e8b1a, clientIf=5
,09-28 09:44:54.379  5631  5641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 09:44:54.380  4575  4799 D BtGatt.GattService: start scan with filters
09-28 09:44:54.383  4575  4663 D BtGatt.ScanManager: handling starting scan
09-28 09:44:54.383  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 09:44:54.384  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:44:54.384  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:44:54.384  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 09:44:54.385  4575  4663 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:44:54.386  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 09:44:54.386  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:44:54.386  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:44:54.387  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 09:44:54.388  5631  5677 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 09:44:54.392  4575  4659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:44:54.392  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:44:54.392  4575  4663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 09:44:54.398  4575  4659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 09:44:54.398  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:44:54.398  4575  4663 D BtGatt.ScanManager: Starting BLE batch scan
09-28 09:44:54.399  4575  4663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 09:44:54.408  4575  4659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 09:44:54.408  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:44:54.414  4575  4659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 09:44:54.414  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:44:54.887  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 09:44:54.887  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:44:54.888  5631  5631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:44:55.029   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:44:56.030   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:44:57.030   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 09:44:57.280   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 09:44:57.291   926  2982 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-28 09:44:59.392  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:44:59.392  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 09:44:59.393  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 09:44:59.393  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:59.393  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 09:44:59.393  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-28 09:44:59.393  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:44:59.393  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-28 09:44:59.393  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 09:44:59.394  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:44:59.394  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 09:44:59.395  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:44:59.396  4575  4818 D BtGatt.GattService: stopScan() - queue size =1
09-28 09:44:59.398  4575  4799 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 09:44:59.401  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:44:59.401  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:44:59.401  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 09:44:59.401  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:44:59.402  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 09:44:59.404  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:44:59.405  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:44:59.405  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:44:59.406  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:44:59.406  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:44:59.406  4575  4575 D BtGatt.ScanManager: awakened up at time 236894
09-28 09:44:59.408  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:44:59.408  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:44:59.408  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:44:59.408  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:44:59.408  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
,09-28 09:44:59.408  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:44:59.408  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:44:59.408  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:44:59.408  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:44:59.408  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:44:59.408  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:44:59.415  4575  4659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 09:44:59.415  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:44:59.415  4575  4663 D BtGatt.ScanManager: stopping BLe Batch
09-28 09:44:59.417  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 09:44:59.417  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:44:59.425  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:44:59.427  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:44:59.427  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:44:59.427  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:44:59.427  4575  4659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:44:59.427  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:44:59.428  4575  4663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 09:44:59.428  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:44:59.432  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:44:59.433  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:44:59.433  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:44:59.438  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:44:59.439  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:44:59.440  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:44:59.443  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:44:59.453  4575  4659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 09:44:59.454  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:44:59.454  4575  4659 D BtGatt.GattService: current time is 236941723023
09-28 09:44:59.454  4575  4659 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -71, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -76, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -80, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -73, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -74, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-28 09:44:59.456  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 09:44:59.458  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 09:44:59.458  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 09:44:59.458  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 09:44:59.459  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 09:44:59.459  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-28 09:44:59.945  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:45:00.309   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 09:45:00.312   926  2982 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-28 09:45:02.032   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:03.034   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:04.035   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:04.413  5631  5677 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 09:45:04.420  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:04.431  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:45:04.435  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:04.436  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 09:45:04.436  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:45:04.436  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:45:04.436  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:45:04.437  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:04.437  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:45:04.442  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:04.444  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 09:45:04.449  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:04.454  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 09:45:04.454  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-28 09:45:04.454  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 09:45:04.456  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:04.459  4575  4595 D BtGatt.GattService: registerClient() - UUID=7da9587c-37f5-4f34-b5e2-e53d968d1f1a
09-28 09:45:04.460  4575  4659 D BtGatt.GattService: onClientRegistered() - UUID=7da9587c-37f5-4f34-b5e2-e53d968d1f1a, clientIf=5
,09-28 09:45:04.461  5631  5641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 09:45:04.461  4575  4818 D BtGatt.GattService: start scan with filters
,09-28 09:45:04.466  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 09:45:04.466  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:45:04.466  4575  4663 D BtGatt.ScanManager: handling starting scan
,09-28 09:45:04.466  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:45:04.466  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 09:45:04.471  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:45:04.471  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:45:04.471  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 09:45:04.474  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 09:45:04.477  4575  4659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:45:04.477  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.477  4575  4663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 09:45:04.480  5631  5677 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 09:45:04.484  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:04.484  5631  5677 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 09:45:04.484  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:04.484  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 09:45:04.484  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:04.484  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 09:45:04.484  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:45:04.484  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:45:04.485  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:45:04.485  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:45:04.485  4575  4659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 09:45:04.485  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-28 09:45:04.485  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 09:45:04.485  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.485  4575  4663 D BtGatt.ScanManager: Starting BLE batch scan
,09-28 09:45:04.485  4575  4663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 09:45:04.486  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:04.487  4575  4595 D BtGatt.GattService: stopScan() - queue size =1
,09-28 09:45:04.488  4575  4818 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 09:45:04.488  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:04.488  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:45:04.488  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 09:45:04.489  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:45:04.489  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 09:45:04.490  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:45:04.490  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:04.490  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:45:04.490  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:45:04.491  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:04.493  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:45:04.493  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:45:04.493  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:04.494  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:45:04.494  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:04.494  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:45:04.494  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:04.494  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:04.494  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:04.494  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:04.494  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:45:04.501  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 09:45:04.501  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:45:04.502  4575  4659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 09:45:04.502  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.505  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:45:04.506  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:45:04.506  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:45:04.506  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:45:04.507  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:04.508  4575  4659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 09:45:04.508  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:45:04.510  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 09:45:04.510  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:04.510  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:45:04.513  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:45:04.513  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:45:04.514  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:04.516  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:45:04.516  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:04.516  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:04.517  4575  4659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 09:45:04.517  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.517  4575  4663 D BtGatt.ScanManager: stopping BLe Batch
09-28 09:45:04.518  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:04.518  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:04.518  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:04.519  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:04.519  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:04.519  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:04.519  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:04.519  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:04.519  5631  5677 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 09:45:04.521  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:04.524  4575  4659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:45:04.524  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.524  4575  4663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:04.525  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:04.526  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:04.527  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:45:04.527  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:45:04.527  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:45:04.527  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:45:04.527  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:04.527  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:45:04.529  4575  4659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 09:45:04.529  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.530  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:04.531  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:45:04.533  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:04.534  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 09:45:04.534  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:45:04.534  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 09:45:04.535  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:04.537  4575  4597 D BtGatt.GattService: registerClient() - UUID=b3784650-b32e-4705-9b34-caba4195eab1
09-28 09:45:04.537  4575  4659 D BtGatt.GattService: onClientRegistered() - UUID=b3784650-b32e-4705-9b34-caba4195eab1, clientIf=5
09-28 09:45:04.538  5631  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 09:45:04.538  4575  4799 D BtGatt.GattService: start scan with filters
09-28 09:45:04.540  4575  4663 D BtGatt.ScanManager: handling starting scan
09-28 09:45:04.542  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 09:45:04.542  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:45:04.542  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:45:04.542  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 09:45:04.547  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:45:04.547  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:45:04.547  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:45:04.547  4575  4659 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:45:04.547  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.548  4575  4663 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 09:45:04.548  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 09:45:04.551  5631  5677 I io.jxcore.node.ConnectionHelper: start: OK
09-28 09:45:04.553  4575  4659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 09:45:04.553  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.553  4575  4663 D BtGatt.ScanManager: Starting BLE batch scan
09-28 09:45:04.553  4575  4663 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 09:45:04.562  4575  4659 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 09:45:04.562  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:04.567  4575  4659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 09:45:04.567  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:45:05.036   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:05.049  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 09:45:05.049  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:45:05.049  5631  5631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:45:06.037   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:07.037   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 09:45:09.551  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:09.551  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:45:09.552  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 09:45:09.552  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:09.552  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:45:09.552  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:45:09.552  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 09:45:09.553  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:45:09.553  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:45:09.553  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-28 09:45:09.553  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 09:45:09.555  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:09.558  4575  4595 D BtGatt.GattService: stopScan() - queue size =1
,09-28 09:45:09.560  4575  4818 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 09:45:09.561  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:45:09.561  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:45:09.561  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 09:45:09.562  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:45:09.562  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 09:45:09.565  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:45:09.565  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:09.566  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:45:09.566  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:45:09.569  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:09.570  4575  4575 D BtGatt.ScanManager: awakened up at time 247057
09-28 09:45:09.571  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:45:09.571  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:09.572  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:45:09.579  4575  4659 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 09:45:09.579  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:09.579  4575  4663 D BtGatt.ScanManager: stopping BLe Batch
,09-28 09:45:09.582  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:45:09.582  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:45:09.587  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:45:09.587  4575  4659 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:45:09.588  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:45:09.588  4575  4663 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 09:45:09.588  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:45:09.588  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:45:09.588  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:45:09.589  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:45:09.592  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 09:45:09.592  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:09.592  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:45:09.594  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:45:09.595  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:45:09.595  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:09.597  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:45:09.602  4575  4659 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-28 09:45:09.602  4575  4659 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:45:09.602  4575  4659 D BtGatt.GattService: current time is 247089873201
09-28 09:45:09.602  4575  4659 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -77, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -74, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 09:45:09.602  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 09:45:09.603  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 09:45:09.603  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 09:45:09.603  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 09:45:09.603  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 09:45:09.603  4575  4659 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 09:45:10.097  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:45:10.097  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:10.097  5631  5631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:45:14.573  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:14.573  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.573  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.574  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:45:14.574  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.574  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:14.574  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.574  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.574  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:45:14.575  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.575  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.577  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.577  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:14.579  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.580  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.580  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:45:14.582  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.582  5631  5677 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:45:14.582  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.582  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.582  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.584  5631  5677 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-28 09:45:14.585  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:14.586  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.586  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 09:45:14.586  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.586  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:14.587  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.587  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.587  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.587  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.587  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.587  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.587  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.588  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:14.588  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.590  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.590  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.590  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:14.591  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.591  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.591  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:45:14.591  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.591  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.593  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 09:45:14.593  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.593  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:45:14.593  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.593  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.593  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.593  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.593  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
,09-28 09:45:14.593  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.594  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.594  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.594  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:14.594  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.594  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.594  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.595  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.595  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.595  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:45:14.596  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.596  5631  5677 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:45:14.596  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.596  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.596  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.597  5631  5677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-28 09:45:14.597  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:14.598  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.598  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.598  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.598  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.598  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.598  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.598  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:45:14.598  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.598  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.598  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.598  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.598  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:14.598  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.600  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.600  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.600  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:14.601  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.601  5631  5677 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:45:14.601  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.601  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.601  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.602  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 09:45:14.602  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.602  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.602  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.603  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.603  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.603  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.603  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
,09-28 09:45:14.603  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.603  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.603  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.603  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.603  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.603  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.603  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:14.605  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.605  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.605  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:45:14.606  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.606  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.606  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.606  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.606  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.607  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 09:45:14.607  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:45:14.607  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:45:14.607  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 09:45:14.607  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-28 09:45:14.608  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:45:14.608  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 09:45:14.608  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:45:14.608  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 09:45:14.608  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.608  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.608  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 09:45:14.608  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.608  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.608  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.608  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.608  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.609  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.609  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:45:14.609  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.609  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.609  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.609  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.610  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.610  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.610  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:45:14.611  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:45:14.611  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.611  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.611  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.611  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.612  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:45:14.612  5631  5677 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-28 09:45:14.612  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 09:45:14.615  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:45:14.616  5631  5677 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 09:45:14.616  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 09:45:14.617  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 09:45:14.617  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 09:45:14.618  5631  5677 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 09:45:14.618  5631  5677 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-28 09:45:14.618  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:45:14.618  5631  5677 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 09:45:14.618  5631  5677 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-28 09:45:14.618  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:45:14.618  5631  5677 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 09:45:14.618  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-28 09:45:14.621  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-28 09:45:14.622  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-28 09:45:14.622  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-28 09:45:14.623  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 09:45:14.623  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-28 09:45:14.623  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 09:45:14.623  5631  5677 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 09:45:14.624  5631  5677 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 09:45:14.624  5631  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-28 09:45:14.624  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.625  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.625  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.625  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.625  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.625  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.625  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-28 09:45:14.626  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.626  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.626  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.626  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.626  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.626  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.626  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.626  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.626  5631  5679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
,09-28 09:45:14.627  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.628  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.628  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:14.628  5631  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:14.628  4818  4818 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33129]" dev="sockfs" ino=33129 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 09:45:14.628  4818  4818 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33129]" dev="sockfs" ino=33129 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 09:45:14.628  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.629  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.629  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.629  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:45:14.629  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.630  5631  5677 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 09:45:14.630  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.630  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.630  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.630  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.630  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:14.630  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.631  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.631  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.631  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.631  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.631  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.631  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.631  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.631  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.632  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.632  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.632  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:14.632  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:45:14.633  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.633  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.633  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.633  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.633  5631  5677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 09:45:14.634  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.634  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.634  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:14.634  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:45:14.634  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.634  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.634  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.634  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.634  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.634  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.634  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.634  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.634  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:14.634  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.635  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.635  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.636  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:14.636  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.636  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.636  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.636  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.636  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.637  5631  5677 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 09:45:14.637  5631  5677 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 09:45:14.637  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-28 09:45:14.637  5631  5677 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 09:45:14.637  5631  5677 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 09:45:14.637  5631  5677 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 09:45:14.637  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 09:45:14.638  5631  5677 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-28 09:45:14.638  5631  5677 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 09:45:14.638  5631  5677 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 09:45:14.638  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 09:45:14.638  5631  5677 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 09:45:14.638  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:14.638  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:14.638  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 09:45:14.638  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.638  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.638  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.638  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.638  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.638  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.638  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.638  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.638  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.638  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.638  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:14.639  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:14.640  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:14.640  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:14.640  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:14.640  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:14.640  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:14.640  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.641  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:14.641  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:14.641  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.641  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:14.641  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:14.641  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:14.641  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:45:14.641  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:14.641  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:14.641  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:17.038   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:18.039   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:18.460   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 09:45:19.040   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:19.642  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:45:19.643  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.643  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:45:19.643  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.643  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.643  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.644  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:19.644  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:19.644  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:19.644  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:19.644  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.644  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.645  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.645  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.645  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.645  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:45:19.645  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.646  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.646  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.646  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.650  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:19.650  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:19.650  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:19.652  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:45:19.653  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:19.653  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:19.653  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:45:19.653  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:45:19.657  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 09:45:19.658  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:45:19.662  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 09:45:19.664  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 09:45:19.664  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 09:45:19.665  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 09:45:19.665  5631  5631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-28 09:45:19.666  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-28 09:45:19.667  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:19.667  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 09:45:19.667  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 09:45:19.667  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 09:45:19.667  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.668  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 09:45:19.668  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.668  5631  5631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 09:45:19.668  5631  5680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:45:19.668  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.668  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:45:19.668  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:45:19.668  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 09:45:19.668  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:45:19.670  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:19.670  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:19.670  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:19.670  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:19.671  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:45:19.671  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.671  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.674  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:45:19.674  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.674  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:45:19.675  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:19.675  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:19.675  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:45:19.675  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:19.675  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:19.675  5631  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-28 09:45:19.675  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:19.675  5631  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 09:45:19.675  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.675  5631  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-28 09:45:19.675  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:19.676  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.676  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.676  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:45:19.676  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:19.676  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.676  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:19.671  4799  4799 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29684]" dev="sockfs" ino=29684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 09:45:19.671  4799  4799 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29684]" dev="sockfs" ino=29684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 09:45:19.682  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:45:19.682  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:45:19.689  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:45:19.691  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 09:45:19.691  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:45:19.691  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:45:19.692  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.695  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:19.696  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.697  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:19.697  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:19.697  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:19.698  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:19.698  5631  5677 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:45:19.698  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:19.698  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.698  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:45:19.698  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.698  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:45:19.698  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:45:19.700  5631  5677 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-28 09:45:19.700  5631  5677 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 09:45:19.700  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 09:45:19.701  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:45:19.701  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 09:45:19.701  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:19.701  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:45:19.701  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:19.701  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:19.701  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.701  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:19.701  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.701  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.701  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:45:19.702  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:19.702  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.702  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:45:19.704  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:45:19.704  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:45:19.705  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.710  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:45:19.710  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:19.711  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.711  5631  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-28 09:45:19.712  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:45:19.712  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:19.712  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:45:19.713  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:19.713  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:19.713  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:19.713  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.714  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
,09-28 09:45:19.718  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:45:19.719  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:19.719  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:19.719  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:19.719  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.719  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:19.719  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.719  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.719  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.720  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:19.720  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.720  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.720  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:19.720  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.721  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:45:19.721  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:19.721  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:45:19.722  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:45:19.722  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:19.723  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:19.723  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.723  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.724  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:45:19.724  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:45:19.724  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:45:19.724  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:45:19.724  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:19.724  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.724  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e577f not in the list
09-28 09:45:19.724  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.724  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.725  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:19.725  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.725  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.725  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:19.725  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:19.726  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:45:19.726  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:45:19.726  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:45:19.727  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:45:19.727  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:45:19.727  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:45:19.727  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:19.727  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae234c not in the list
09-28 09:45:19.728  5631  5677 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-28 09:45:19.728  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 09:45:19.728  5631  5677 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 09:45:19.728  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-28 09:45:19.729  5631  5677 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-28 09:45:19.729  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-28 09:45:19.731  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-28 09:45:19.731  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-28 09:45:19.732  5631  5677 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-28 09:45:19.732  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 09:45:19.732  5631  5677 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-28 09:45:19.732  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 09:45:19.732  5631  5677 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-28 09:45:19.732  5631  5677 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-28 09:45:19.733  5631  5677 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 09:45:19.733  5631  5677 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-28 09:45:19.733  5631  5677 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-28 09:45:19.733  5631  5677 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-28 09:45:19.734  5631  5677 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 09:45:19.734  5631  5677 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-28 09:45:19.735  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 09:45:19.735  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a470b2 added. We now have 3 listener(s)
09-28 09:45:19.735  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:45:19.737  5631  5677 D BluetoothAdapter: enable(): BT is already enabled..!
,09-28 09:45:19.737   926   936 D WifiService: setWifiEnabled: true pid=5631, uid=10077
09-28 09:45:19.737   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:45:19.757  4575  4764 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-28 09:45:19.757  4575  4794 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-28 09:45:19.758  5631  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,09-28 09:45:20.041   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:20.211  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:45:21.042   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:21.491   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 09:45:22.043   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 09:45:23.550   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:45:24.517   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 09:45:24.742  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 09:45:24.743  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a066803 added. We now have 4 listener(s)
09-28 09:45:24.743  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:45:24.758  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:45:24.759  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a066803 removed from the list
09-28 09:45:24.759  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:45:24.759  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:24.759  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:24.761  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:45:24.761  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbd6380 added. We now have 4 listener(s)
,09-28 09:45:24.761  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:45:24.764  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:45:24.765  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbd6380 removed from the list
09-28 09:45:24.765  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:24.765  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:45:24.765  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:24.767  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:45:24.767  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f48db9 added. We now have 4 listener(s)
09-28 09:45:24.767  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:45:24.772   926   937 D WifiService: setWifiEnabled: false pid=5631, uid=10077
,09-28 09:45:24.772   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:45:24.777   926  2980 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 09:45:24.777   926  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 09:45:24.778   926  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:45:24.778   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:45:24.786  4575  4655 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 09:45:24.786  4575  4655 D BluetoothAdapterProperties: Setting state to 13
09-28 09:45:24.787  4575  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-28 09:45:24.787  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:45:24.788  4575  4655 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 09:45:24.788  4575  4655 I BluetoothAdapterState: Entering PendingCommandState
09-28 09:45:24.793  4575  4575 D BluetoothMapService: onReceive
09-28 09:45:24.794  4575  4575 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 09:45:24.794  4575  4575 D BluetoothMapService: STATE_TURNING_OFF
09-28 09:45:24.794  4575  4575 D BluetoothMapService: MAP Service closeService in
09-28 09:45:24.794  4575  4575 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 09:45:24.794  4575  4575 D ObexServerSockets0: shutdown(block = true)
09-28 09:45:24.795  4575  4575 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-28 09:45:24.795  4575  4820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-28 09:45:24.797  4575  4575 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:45:24.797  4575  4794 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 09:45:24.798  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.798  4575  4821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:24.798  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:24.799  4575  4575 I BtOppRfcommListener: stopping Accept Thread
09-28 09:45:24.800   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-28 09:45:24.800  4575  5312 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-28 09:45:24.800   926  5382 D DhcpClient: Clearing IP address
09-28 09:45:24.800  4575  5312 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 09:45:24.802  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.803  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:24.803  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 09:45:24.807  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:24.810   507   920 D CommandListener: Setting iface cfg
,09-28 09:45:24.811  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:24.813  3557  5454 V NativeCrypto: Read error: ssl=0x7f91358700: I/O error during system call, Connection timed out
09-28 09:45:24.815  3557  5454 V NativeCrypto: SSL shutdown failed: ssl=0x7f91358700: I/O error during system call, Broken pipe
09-28 09:45:24.815  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:24.816  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:24.816   926  5383 D DhcpClient: Receive thread stopped
09-28 09:45:24.817  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.817  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:24.818   926  3776 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-28 09:45:24.819   926  5380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-28 09:45:24.822  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:24.822  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:24.823  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.823  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:24.825   926   939 I ActivityManager: Start proc 5684:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-28 09:45:24.826  4575  4659 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:45:24.826  4575  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 09:45:24.826   926  5380 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-28 09:45:24.827   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-28 09:45:24.827   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-28 09:45:24.828   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 09:45:24.828  4575  4575 D HeadsetService: Received stop request...Stopping profile...
,09-28 09:45:24.831   926   926 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:24.831   926   926 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:24.831   926   926 D BluetoothHeadset: Proxy object disconnected
,09-28 09:45:24.832  3105  3118 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:24.832  3105  3105 D HeadsetProfile: Bluetooth service disconnected
09-28 09:45:24.833  3759  3992 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:24.833   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 09:45:24.833   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-28 09:45:24.834  4575  4575 D A2dpService: Received stop request...Stopping profile...
09-28 09:45:24.834  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:24.834  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:45:24.835  4575  4810 D A2dpStateMachine: Exit Disconnected: -1
,09-28 09:45:24.836  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:45:24.836  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:24.837   533   533 E Parcel  : Reading a NULL string not supported here.
09-28 09:45:24.839  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.839  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:24.840   926   926 D RttService: SCAN_AVAILABLE : 1
09-28 09:45:24.840  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.840  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:24.841   926  3046 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 09:45:24.844  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.844  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:24.845  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.845  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:24.846   926  2982 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-28 09:45:24.847   926   926 D BluetoothA2dp: Proxy object disconnected
09-28 09:45:24.847  3105  3105 D BluetoothA2dp: Proxy object disconnected
09-28 09:45:24.848  3721  3871 W QCNEJ   : |CORE| network lost: 100
09-28 09:45:24.848  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.848  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.848  3721  3871 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.848  5631,  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.848  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:24.848  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.848  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.848  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.849  4575  4575 D HidService: Received stop request...Stopping profile...
09-28 09:45:24.849   926  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 09:45:24.849  4575  4575 D HidService: Stopping Bluetooth HidService
09-28 09:45:24.856  4575  4575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 09:45:24.856  4575  4575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 09:45:24.856  4575  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:24.856  4575  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:24.856  4575  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:24.856  4575  4659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 09:45:24.856  4575  4659 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 09:45:24.857  4575  4575 D HealthService: Received stop request...Stopping profile...
09-28 09:45:24.858  4575  4575 D PanService: Received stop request...Stopping profile...
09-28 09:45:24.859  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.859  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.859  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.859  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.863  4575  4659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 09:45:24.863  4575  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:24.863  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.863  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.863  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.863  4575  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:24.863  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.863  4575  4764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:45:24.863  4575  4764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:45:24.863  4575  4764 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:45:24.863  4575  4764 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:45:24.863  4575  4575 D BluetoothMapService: Received stop request...Stopping profile...
09-28 09:45:24.864  4575  4575 D BluetoothMapService: stop()
09-28 09:45:24.864   926  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:45:24.864  4575  4575 D BluetoothMapAppObserver: deinitObservers()
09-28 09:45:24.864  4575  4575 D BluetoothMapAppObserver: removeReceiver()
09-28 09:45:24.866  4575  4575 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 09:45:24.866  4575  4575 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 09:45:24.866  4575  4659 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 09:45:24.866  4575  4575 D SapService: Received stop request...Stopping profile...
09-28 09:45:24.866  4575  4575 V SapService: stop()
09-28 09:45:24.867  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.867  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.867  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.867  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.868  4575  4575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 09:45:24.868  4575  4659 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 09:45:24.868  4575  4575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 09:45:24.868  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.868  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.868  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.868  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.869  4575  4575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 09:45:24.869  4575  4575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 09:45:24.869  4575  4575 D BluetoothMapService: MAP Service closeService in
09-28 09:45:24.870  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.870  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.870  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.870  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.870  3105  3105 D BluetoothInputDevice: Proxy object disconnected
09-28 09:45:24.870  4575  4575 D BluetoothMapService: cleanup()
09-28 09:45:24.870  3105  3105 D HidProfile: Bluetooth service disconnected
09-28 09:45:24.870  4575  4575 D BluetoothMapService: MAP Service closeService in
09-28 09:45:24.870  4575  4575 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:24.870  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 09:45:24.870  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:24.870  3105  3105 D PanProfile: Bluetooth service disconnected
09-28 09:45:24.871  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:24.871  4575  4575 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:24.871  3105  3105 D BluetoothMap: Proxy object disconnected
09-28 09:45:24.871  3105  3105 D MapProfile: Bluetooth service disconnected
09-28 09:45:24.871  4575  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 09:45:24.871  4575  4655 D BluetoothAdapterProperties: Setting state to 15
09-28 09:45:24.871  4575  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 09:45:24.871  4575  4655 I BluetoothAdapterState: Entering BleOnState
09-28 09:45:24.882   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 09:45:24.883  3105  3118 D BluetoothPan: onBluetoothStateChange on: false
,09-28 09:45:24.884  3105  3967 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:24.884   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:45:24.885  3759  4105 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:24.885   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:24.885  3105  3119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:45:24.886   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:24.886  3105  3905 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 09:45:24.887  3105  3118 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 09:45:24.888  3105  3967 D BluetoothMap: onBluetoothStateChange: up=false
09-28 09:45:24.890   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:24.891  4575  4655 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 09:45:24.891  4575  4655 D BluetoothAdapterProperties: Setting state to 16
09-28 09:45:24.891  4575  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 09:45:24.891  4575  4655 D BluetoothAdapterProperties: onBleDisable
09-28 09:45:24.891  4575  4655 I BluetoothAdapterState: Entering PendingCommandState
09-28 09:45:24.892  4575  4656 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 09:45:24.893  4575  4659 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:45:24.894  4575  4764 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 09:45:24.894  4575  4764 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:24.895  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.895  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:24.899  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:24.900  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:24.902  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:24.904  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:24.906  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:24.907   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 09:45:24.907   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-28 09:45:24.908   507   920 D TetherController: Setting IP forward enable = 0
09-28 09:45:24.910   926  2982 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-28 09:45:24.910   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 09:45:24.911   926   943 D Tethering: MasterInitialState.processMessage what=3
,09-28 09:45:24.914  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:24.914   926  2980 D DhcpClient: doQuit
09-28 09:45:24.915   926  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 09:45:24.915   926  5382 D DhcpClient: onQuitting
,09-28 09:45:24.916  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:24.916  3432  3432 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-28 09:45:24.917  4933  4933 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-28 09:45:24.917  5296  5296 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d65f644 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-28 09:45:24.919  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.920  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:24.920  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.920  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:45:24.921  5041  5072 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 09:45:24.921  5041  5072 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-28 09:45:24.921  5041  5072 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 09:45:24.921  5041  5072 E SarControlService: no key has been found,reset the power
,09-28 09:45:24.921  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-28 09:45:24.921  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:45:24.921  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:45:24.922  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:45:24.922  5073  5073 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-28 09:45:24.922  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.923  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:45:24.923  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:45:24.923  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:45:24.923  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:45:24.924  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.924  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:24.924  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:45:24.925  5073  5073 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:45:24.926  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:24.926  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:24.927  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:24.927  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:24.927  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000ea03000000000000ffffffff]
09-28 09:45:24.927  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:45:24.927  5073  5088 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 09:45:24.928  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:24.929  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:45:24.929  5041  5051 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:45:24.931  5684  5684 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-28 09:45:24.937  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000eb03000000000000ffffffff]
09-28 09:45:24.937  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:45:24.937  5073  5088 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-28 09:45:24.938  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:45:24.938  5041  5052 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 09:45:24.941  3432  3432 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 09:45:24.946  3432  3432 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 09:45:24.951  5684  5684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 09:45:24.959   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c44b9bc:true
,09-28 09:45:24.960  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:45:24.969   507   920 E Netd    : netlink response contains error (No such file or directory)
,09-28 09:45:24.969   507   920 D TetherController: Setting IP forward enable = 0
09-28 09:45:24.970   926  2982 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 09:45:24.970   926  2982 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 09:45:24.976   926   937 I ActivityManager: Start proc 5714:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 09:45:24.983  3432  3432 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 09:45:24.985  5684  5684 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 09:45:24.987  5684  5684 D BluetoothMap: Create BluetoothMap proxy object
,09-28 09:45:24.993  5684  5684 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 09:45:25.009  5714  5714 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 09:45:25.012  5684  5684 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:45:25.016  3432  3432 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 09:45:25.018   926  3188 I ActivityManager: Killing 4974:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 09:45:25.099  4575  4659 I bt_hci  : shut_down
,09-28 09:45:25.104  4575  4665 D bt_hwcfg: hw_epilog_process
,09-28 09:45:25.104  4575  4665 I bt_vendor: low_power_mode_cb
,09-28 09:45:25.106  4575  4665 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 09:45:25.107  4575  4665 I bt_vendor: epilog_cb
,09-28 09:45:25.107  4575  4665 I bt_hci  : epilog_finished_callback
09-28 09:45:25.109  4575  4659 I bt_hci_h4: hal_close
,09-28 09:45:25.109  4575  4659 I bt_userial_vendor: device fd = 54 close
,09-28 09:45:25.121  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:45:25.121   926  2980 D wifi    : In wifi stop Hal
09-28 09:45:25.121   926  2980 D wifi    : halHandle = 0x7f7ad91680, mVM = 0x7f9740d140, mCls = 0x100a02
09-28 09:45:25.122   926  3431 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 09:45:25.122   926  3431 D WifiHAL : Got a signal to exit!!!
,09-28 09:45:25.122   926  3431 I WifiHAL : Exit wifi_event_loop
09-28 09:45:25.122   926  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-28 09:45:25.122   926  2980 E WifiHAL : Event processing terminated
09-28 09:45:25.123   926  2980 D wifi    : In wifi cleaned up handler
09-28 09:45:25.123   926  2980 I WifiHAL : Internal cleanup completed
09-28 09:45:25.123  4074  4192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 09:45:25.124  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:25.127  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:25.128  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:25.144   926  3431 D wifi    : set interface wlan0 flags (DOWN)
,09-28 09:45:25.145   926  2980 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 09:45:25.192  5714  5714 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 09:45:25.192  5714  5714 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.192  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.193  5714  5714 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.193  5714  5714 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.193  5714  5714 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.193  5714  5714 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.193  5714  5714 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.193  5714  5714 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 09:45:25.193  5714  5714 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 09:45:25.209  5684  5684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 09:45:25.218  4575  4656 D bt_stack_manager: event_shut_down_stack finished.
09-28 09:45:25.219  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:45:25.219  4575  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-28 09:45:25.219  5684  5684 D DockEventReceiver: finishStartingService: stopping service
09-28 09:45:25.221  4575  4575 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 09:45:25.221  4575  4655 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 09:45:25.221  4575  4575 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 09:45:25.221  4575  4575 D BtGatt.GattService: stop()
09-28 09:45:25.221  4575  4575 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 09:45:25.223   926  3402 I ActivityManager: Killing 5410:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-28 09:45:25.252  4575  4575 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:25.253  4575  4575 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:25.253  4575  4575 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:25.253  4575  4575 V BluetoothAdapterState: isBleTurningOff()=true
09-28 09:45:25.253  4575  4655 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 09:45:25.253  4575  4655 D BluetoothAdapterProperties: Setting state to 10
09-28 09:45:25.253  4575  4655 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 09:45:25.253  4575  4655 I BluetoothAdapterState: Entering OffState
09-28 09:45:25.254   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-28 09:45:25.259  4575  4575 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-28 09:45:25.260  4575  4575 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 09:45:25.260  4575  4575 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 09:45:25.261  4575  4656 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-28 09:45:25.264  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 09:45:25.270  3834  3834 D SystemUpdateService: onCreate
09-28 09:45:25.274  4575  4656 D bt_stack_manager: event_clean_up_stack finished.
09-28 09:45:25.274  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 09:45:25.283  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 09:45:25.288  4575  4575 I art     : System.exit called, status: 0
,09-28 09:45:25.288  4575  4575 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 09:45:25.300  3834  5408 I iu.UploadsManager: num queued entries: 0
,09-28 09:45:25.300  3834  5408 I iu.UploadsManager: num updated entries: 0
09-28 09:45:25.301  3834  5408 I iu.SyncManager: NEXT; no task
,09-28 09:45:25.311  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:45:25.312  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:45:25.314  3834  5747 I SystemUpdateService: active receiver: enabled
,09-28 09:45:25.324   926  3188 I ActivityManager: Start proc 5750:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-28 09:45:25.330   926  3803 I ActivityManager: Process com.android.bluetooth (pid 4575) has died
,09-28 09:45:25.333  3834  5747 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:45:25.347   926   943 D Tethering: InitialState.processMessage what=4
,09-28 09:45:25.349   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 09:45:25.356  5750  5750 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-28 09:45:25.359  5750  5750 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:45:25.365  5750  5750 D SprintDMHelper: simOperator: 
,09-28 09:45:25.365  5750  5750 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 09:45:25.376  5015  5762 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 09:45:25.389   926   936 I ActivityManager: Start proc 5763:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 09:45:25.393  3834  5747 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 09:45:25.393  3834  5747 I SystemUpdateService: now status is 0 (complete)
09-28 09:45:25.393  3834  5747 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:45:25.393  3834  5747 I SystemUpdateService: file has been verified
09-28 09:45:25.393  3834  5747 I SystemUpdateService: OTA package size = 21989297
,09-28 09:45:25.415  3834  5747 I SystemUpdateService: showing system update notification
,09-28 09:45:25.421  5763  5763 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 09:45:25.433   926  3798 I ActivityManager: Killing 5296:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 09:45:25.469  3834  3834 D SystemUpdateService: onDestroy
,09-28 09:45:25.471   926  3402 I ActivityManager: Killing 4669:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 09:45:25.597  5714  5736 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 09:45:25.609   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f75869:true
,09-28 09:45:29.806   926  3402 D WifiService: setWifiEnabled: true pid=5631, uid=10077
,09-28 09:45:29.806   926  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:45:29.814   507   920 D SoftapController: Softap fwReload - Ok
,09-28 09:45:29.819   507   920 D CommandListener: Setting iface cfg
,09-28 09:45:29.819   507   920 D CommandListener: Trying to bring down wlan0
,09-28 09:45:29.822   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-28 09:45:29.827   926  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 09:45:30.397   926  2980 D wifi    : set interface wlan0 flags (UP)
09-28 09:45:30.398   926  2980 I WifiHAL : Initializing wifi
,09-28 09:45:30.398   926  2980 I WifiHAL : Creating socket
09-28 09:45:30.400   926  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-28 09:45:30.400   926  2980 D wifi    : Did set static halHandle = 0x7f7ad91680
09-28 09:45:30.400   926  2980 D wifi    : halHandle = 0x7f7ad91680, mVM = 0x7f9740d140, mCls = 0x194e
09-28 09:45:30.400   926  2980 D wifi    : array field set
09-28 09:45:30.400   926  2980 I WifiNative-HAL: interface[0] = wlan0
09-28 09:45:30.402   926  5780 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547521894016
09-28 09:45:30.402   926  5780 D wifi    : waitForHalEvents called, vm = 0x7f9740d140, obj = 0x194e, env = 0x7f7adab140
,09-28 09:45:30.403   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 09:45:30.467  5781  5781 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 09:45:30.482  5781  5781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:45:30.491  5781  5781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:45:30.491  5781  5781 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 09:45:30.503   926  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 09:45:30.505  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:30.506  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:30.506  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:30.506  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:30.506  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:45:30.507  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:30.507  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:30.507  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:30.507  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:45:30.511   926  2980 D WifiConfigStore: Loading config and enabling all networks 
09-28 09:45:30.511  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:30.511  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:45:30.511  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:30.511  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:30.513  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:30.513  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:30.522   926  2980 D WifiConfigStore: loaded 0 passpoint configs
,09-28 09:45:30.523   926  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 09:45:30.523   926  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 09:45:30.524   926  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 09:45:30.526   926  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 09:45:30.526   926  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 09:45:30.526   926  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 09:45:30.526   926  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 09:45:30.530   926  2980 D WifiNative-HAL: Setting external_sim to 1
,09-28 09:45:30.530  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 09:45:30.530   926  2980 D wifi    : setting dfs flag to true, 0x7f7deef320
09-28 09:45:30.531   926  2980 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 09:45:30.531   926  2980 D wifi    : setting scan oui 0x7f7deef320
09-28 09:45:30.531   926  2980 D WifiHAL : Sending mac address OUI
,09-28 09:45:30.535   926  2980 E native  : do suspend false
,09-28 09:45:30.542   926   926 D RttService: SCAN_AVAILABLE : 3
,09-28 09:45:30.542   926  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 09:45:30.542   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 09:45:30.542   926  3046 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 09:45:30.543   507   920 D CommandListener: Setting iface cfg
,09-28 09:45:30.547   926  2977 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-28 09:45:30.547   926  2977 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 09:45:30.556   926  2977 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 09:45:30.556   926  2977 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62,
,09-28 09:45:30.563   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268050 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-28 09:45:33.718  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:45:33.724  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:45:33.730  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:45:33.734  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:45:33.795   926  2980 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 09:45:33.796   926  2980 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-28 09:45:33.797   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:45:33.809   926  2980 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 09:45:33.843   926  2980 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 09:45:33.845  5781  5781 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 09:45:34.289  5781  5781 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 09:45:34.335  5781  5781 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 09:45:34.337  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 09:45:34.359   926  2980 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 09:45:34.359   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 09:45:34.359   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 09:45:34.380   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:45:34.392   507   920 D CommandListener: Setting iface cfg
,09-28 09:45:34.400   926  2980 D WifiStateMachine: Start Dhcp Watchdog 2
,09-28 09:45:34.407   926  5789 D DhcpClient: Receive thread started
,09-28 09:45:34.411   926  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 09:45:34.411   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 09:45:34.411   926  2982 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-28 09:45:34.492   926  2980 E native  : do suspend false
,09-28 09:45:34.505   926  5788 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 09:45:34.525   926  5789 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
,09-28 09:45:34.526   926  5788 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
09-28 09:45:34.527   926  5788 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 09:45:34.541   926  5789 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 09:45:34.542   926  5788 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 09:45:34.546   507   920 D CommandListener: Setting iface cfg
,09-28 09:45:34.553   926  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 09:45:34.556   926  5788 D DhcpClient: Scheduling renewal in 86399s
,09-28 09:45:34.566   926  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 09:45:34.567   926  2980 D WifiConfigStore: No blacklist allowed without epno enabled
09-28 09:45:34.568   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-28 09:45:34.573   926  2982 D ConnectivityService: Adding iface wlan0 to network 101
09-28 09:45:34.571   926  2980 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 09:45:34.625   926  2982 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 09:45:34.625   926  2982 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-28 09:45:34.627   926  2982 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-28 09:45:34.629   926  2982 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 09:45:34.632   926  2982 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 09:45:34.641   926  2982 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 09:45:34.646   926  2982 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-28 09:45:34.646   926  2982 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-28 09:45:34.646   926  2982 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-28 09:45:34.646   926  2980 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-28 09:45:34.646   926  2982 D ConnectivityService:    accepting network in place of null
09-28 09:45:34.646   926  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:45:34.647   926  2982 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 09:45:34.661   926  5787 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272148, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:45:34.676   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:45:34.704   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:45:34.708   926  2982 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-28 09:45:34.708  3721  3871 W QCNEJ   : |CORE| network available: 101
,09-28 09:45:34.709   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 09:45:34.710   926  2982 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-28 09:45:34.710   926   943 D Tethering: MasterInitialState.processMessage what=3
09-28 09:45:34.713  3721  3871 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-28 09:45:34.715  3721  3871 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 09:45:34.715  3721  3871 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 09:45:34.716  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:34.716  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:34.716  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.716  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:45:34.718  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:34.718  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:34.718  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.718  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:34.722  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:45:34.722  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:45:34.722  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.723  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:45:34.723  5041  5072 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 09:45:34.724  5041  5072 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:45:34.724  5041  5072 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 09:45:34.724  5041  5072 E SarControlService: no key has been found,reset the power
09-28 09:45:34.724  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 09:45:34.724  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:45:34.724  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:45:34.725  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:45:34.725  5073  5073 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:45:34.725   926  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
09-28 09:45:34.726  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:45:34.726  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:45:34.726  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:45:34.727  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:45:34.727  5073  5073 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:45:34.728  4933  4933 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-28 09:45:34.730  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 09:45:34.733  3834  3834 D SystemUpdateService: onCreate
09-28 09:45:34.736  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 09:45:34.742  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000ec03000000000000ffffffff]
09-28 09:45:34.743  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:45:34.743  5073  5088 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 09:45:34.743  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:45:34.743  5041  5051 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:45:34.744  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000ed03000000000000ffffffff]
09-28 09:45:34.744  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:45:34.744  5073  5088 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-28 09:45:34.745  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:45:34.745  5041  5052 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 09:45:34.746  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-28 09:45:34.747  3834  5408 I iu.UploadsManager: num queued entries: 0
09-28 09:45:34.748  3834  5408 I iu.UploadsManager: num updated entries: 0
09-28 09:45:34.748  3834  5408 I iu.SyncManager: NEXT; no task
,09-28 09:45:34.756  3834  5799 I SystemUpdateService: active receiver: enabled
09-28 09:45:34.759  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-28 09:45:34.760  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-28 09:45:34.762  5750  5750 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-28 09:45:34.765  5750  5750 D SprintDMHelper: simOperator: 
09-28 09:45:34.766  5750  5750 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-28 09:45:34.785  3834  5799 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:45:34.795   926  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 13:45:34 GMT], X-Android-Received-Millis=[1475070334795], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475070334760]}
,09-28 09:45:34.796   926  2982 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 09:45:34.796   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-28 09:45:34.796   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 09:45:34.798   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 09:45:34.799  3834  5799 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 09:45:34.799  3834  5799 I SystemUpdateService: now status is 0 (complete)
09-28 09:45:34.799  3834  5799 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:45:34.799  3834  5799 I SystemUpdateService: file has been verified
09-28 09:45:34.799  3834  5799 I SystemUpdateService: OTA package size = 21989297
,09-28 09:45:34.805  3834  5799 I SystemUpdateService: showing system update notification
,09-28 09:45:34.812   926  3140 D WifiService: setWifiEnabled: false pid=5631, uid=10077
,09-28 09:45:34.812   926  3140 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:45:34.814   926  2980 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 09:45:34.814   926  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 09:45:34.814   926  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 09:45:34.814   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:45:34.817  3834  3834 D SystemUpdateService: onDestroy
,09-28 09:45:34.825   926  5788 D DhcpClient: Clearing IP address
,09-28 09:45:34.826   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-28 09:45:34.827   507   920 D CommandListener: Setting iface cfg
09-28 09:45:34.828   926  5789 D DhcpClient: Receive thread stopped
09-28 09:45:34.833  3557  5800 V NativeCrypto: SSL handshake aborted: ssl=0x7f7c3b2000: I/O error during system call, Connection timed out
09-28 09:45:34.837   926  3401 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-28 09:45:34.837   926  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-28 09:45:34.838   926  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-28 09:45:34.842   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 09:45:34.842   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-28 09:45:34.847   926   926 D RttService: SCAN_AVAILABLE : 1
09-28 09:45:34.847   926  3046 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 09:45:34.848   533   533 E Parcel  : Reading a NULL string not supported here.
09-28 09:45:34.851   926  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 09:45:34.851   926  2982 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-28 09:45:34.851   926  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:45:34.853  3721  3871 W QCNEJ   : |CORE| network lost: 101
09-28 09:45:34.854  3721  3871 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 09:45:34.855  5015  5803 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-28 09:45:34.857   926  5786 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.16.206 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
09-28 09:45:34.871  5015  5803 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-28 09:45:34.871  5015  5803 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-28 09:45:34.875   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:45:34.894   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:45:34.894   507   920 D CommandListener: Clearing all IP addresses on wlan0
09-28 09:45:34.894   926  2982 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 09:45:34.895   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:45:34.898   926   943 D Tethering: MasterInitialState.processMessage what=3
,09-28 09:45:34.899  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:34.899  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:34.899  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.900  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:45:34.900   926  2980 D DhcpClient: doQuit
09-28 09:45:34.900   926  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 09:45:34.900   926  5788 D DhcpClient: onQuitting
09-28 09:45:34.901  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.901  5781  5781 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:34.901  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:34.901  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:45:34.901  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:45:34.902  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:34.902  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:34.902  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.903  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:34.904  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:34.904  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:34.904  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 09:45:34.904  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:34.906  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:34.906  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:34.906  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:34.906  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:34.907  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:34.904  4933  4933 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-28 09:45:34.909  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 09:45:34.911  5041  5072 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 09:45:34.911  5041  5072 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:45:34.911  5041  5072 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-28 09:45:34.911  5041  5072 E SarControlService: no key has been found,reset the power
09-28 09:45:34.911  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 09:45:34.911  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 09:45:34.911  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:45:34.912  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:45:34.912  5073  5073 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:45:34.913  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:45:34.913  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:45:34.913  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 09:45:34.913  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 09:45:34.914  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:45:34.914  5073  5073 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:45:34.917  3834  3834 D SystemUpdateService: onCreate
09-28 09:45:34.918  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000ee03000000000000ffffffff]
09-28 09:45:34.918  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:45:34.918  5073  5088 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-28 09:45:34.919  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:45:34.919  5041  5052 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:45:34.919  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 09:45:34.921  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000ef03000000000000ffffffff]
09-28 09:45:34.921  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:45:34.921  5073  5088 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-28 09:45:34.922  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:45:34.922  5041  5051 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 09:45:34.924  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 09:45:34.928  3834  5817 I SystemUpdateService: active receiver: enabled
,09-28 09:45:34.933  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 09:45:34.937  3834  5408 I iu.UploadsManager: num queued entries: 0
,09-28 09:45:34.938  3834  5408 I iu.UploadsManager: num updated entries: 0
09-28 09:45:34.938  3834  5408 I iu.SyncManager: NEXT; no task
,09-28 09:45:34.941  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:45:34.942  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:45:34.944  5750  5750 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:45:34.948   507   920 E Netd    : netlink response contains error (No such file or directory)
,09-28 09:45:34.948  5750  5750 D SprintDMHelper: simOperator: 
09-28 09:45:34.949  5750  5750 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-28 09:45:34.950   926  2982 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 09:45:34.951  3834  5817 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-28 09:45:34.954  5781  5781 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 09:45:34.959  5015  5821 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 09:45:34.960  3834  5817 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 09:45:34.960  3834  5817 I SystemUpdateService: now status is 0 (complete)
09-28 09:45:34.960  3834  5817 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-28 09:45:34.960  3834  5817 I SystemUpdateService: file has been verified
09-28 09:45:34.963  3834  5817 I SystemUpdateService: OTA package size = 21989297
,09-28 09:45:34.967  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 09:45:34.976  3834  5817 I SystemUpdateService: showing system update notification
,09-28 09:45:34.986  3834  3834 D SystemUpdateService: onDestroy
,09-28 09:45:35.071   926  2980 D wifi    : In wifi stop Hal
,09-28 09:45:35.071   926  2980 D wifi    : halHandle = 0x7f7ad91680, mVM = 0x7f9740d140, mCls = 0x194e
,09-28 09:45:35.073   926  5780 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 09:45:35.073   926  5780 D WifiHAL : Got a signal to exit!!!
09-28 09:45:35.073   926  5780 I WifiHAL : Exit wifi_event_loop
09-28 09:45:35.074  4074  4192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:45:35.076   926  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-28 09:45:35.076   926  2980 E WifiHAL : Event processing terminated
09-28 09:45:35.076  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:35.077   926  2980 D wifi    : In wifi cleaned up handler
,09-28 09:45:35.077   926  2980 I WifiHAL : Internal cleanup completed
09-28 09:45:35.078  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:35.080  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:35.081  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 09:45:35.110   926  5780 D wifi    : set interface wlan0 flags (DOWN)
,09-28 09:45:35.111   926  2980 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 09:45:35.316   926   943 D Tethering: InitialState.processMessage what=4
,09-28 09:45:35.323   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 09:45:35.710   926  2982 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 09:45:37.044   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:38.045   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:39.046   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:39.849   926   943 I ActivityManager: Start proc 5825:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 09:45:39.925  5825  5825 D AdapterServiceConfig: Adding HeadsetService
,09-28 09:45:39.925  5825  5825 D AdapterServiceConfig: Adding A2dpService
09-28 09:45:39.925  5825  5825 D AdapterServiceConfig: Adding HidService
09-28 09:45:39.925  5825  5825 D AdapterServiceConfig: Adding HealthService
09-28 09:45:39.926  5825  5825 D AdapterServiceConfig: Adding PanService
09-28 09:45:39.926  5825  5825 D AdapterServiceConfig: Adding GattService
,09-28 09:45:39.926  5825  5825 D AdapterServiceConfig: Adding BluetoothMapService
09-28 09:45:39.926  5825  5825 D AdapterServiceConfig: Adding SapService
,09-28 09:45:39.937   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f883d74:true
,09-28 09:45:39.937  5825  5825 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 09:45:39.940  5825  5825 I bt_bluedroid: init
,09-28 09:45:39.940  5825  5837 I BluetoothAdapterState: Entering OffState
,09-28 09:45:39.942  5825  5838 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 09:45:39.942  5825  5838 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 09:45:39.942  5825  5838 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 09:45:39.942  5825  5838 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 09:45:39.943  5825  5825 I bt_bluedroid: get_profile_interface socket
,09-28 09:45:39.944  5825  5841 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 09:45:39.945  5825  5825 I bt_bluedroid: get_profile_interface sdp
,09-28 09:45:39.946  5825  5841 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 09:45:39.950  5825  5836 I bt_bluedroid: config_hci_snoop_log
,09-28 09:45:39.951   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 09:45:39.956  5825  5837 D BluetoothAdapterState: Current state: OFF, message: 0
09-28 09:45:39.956  5825  5837 D BluetoothAdapterProperties: Setting state to 14
09-28 09:45:39.956  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 09:45:39.958  5825  5837 D BluetoothBondStateMachine: make
,09-28 09:45:39.959  5825  5842 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 09:45:39.962  5825  5837 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:45:39.963  5825  5825 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 09:45:39.966  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:39.966  5825  5825 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 09:45:39.967  5825  5825 D BtGatt.GattService: Received start request. Starting profile...
09-28 09:45:39.967  5825  5825 D BtGatt.GattService: start()
09-28 09:45:39.967  5825  5825 I bt_bluedroid: get_profile_interface gatt
09-28 09:45:39.968  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:39.968  5825  5825 D BtGatt.AdvertiseManager: advertise manager created
,09-28 09:45:39.973  5825  5825 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:45:39.973  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:39.973  5825  5825 V BluetoothAdapterState: isBleTurningOn()=true
09-28 09:45:39.973  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:39.973  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 09:45:39.975  5825  5837 I bt_bluedroid: bt_bluedroid
09-28 09:45:39.975  5825  5838 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-28 09:45:39.975  5825  5838 I bt_hci  : start_up
,09-28 09:45:39.980  5825  5838 I bt_vendor: alloc value 0xf41c9871
09-28 09:45:39.980  5825  5838 I bt_vendor: init
09-28 09:45:39.980  5825  5838 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 09:45:39.980  5825  5838 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 09:45:40.047   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:40.092  5825  5838 D bt_hci  : start_up starting async portion
,09-28 09:45:40.093  5825  5845 I bt_hci  : event_finish_startup
,09-28 09:45:40.093  5825  5845 I bt_hci_h4: hal_open
09-28 09:45:40.091  5846  5846 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 09:45:40.093  5825  5845 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-28 09:45:40.096  5825  5845 I bt_userial_vendor: device fd = 54 open
,09-28 09:45:40.110  5825  5845 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 09:45:40.113  5825  5845 D bt_hwcfg: Chipset BCM4358A3
,09-28 09:45:40.113  5825  5845 D bt_hwcfg: Target name = [BCM4358A3]
09-28 09:45:40.113  5825  5845 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 09:45:40.498  5825  5845 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 09:45:40.499  5825  5845 D bt_hwcfg: Settlement delay -- 100 ms
09-28 09:45:40.499  5825  5845 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 09:45:40.633  5825  5845 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 09:45:40.633  5825  5845 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 09:45:40.635  5825  5845 I bt_hwcfg: vendor lib fwcfg completed
09-28 09:45:40.635  5825  5845 I bt_vendor: firmware callback
09-28 09:45:40.635  5825  5845 I bt_hci  : firmware_config_callback
,09-28 09:45:40.644  5825  5848 I bt_btu  : btu_task pending for preload complete event
,09-28 09:45:40.644  5825  5848 I bt_btu_task: Bluetooth chip preload is complete
09-28 09:45:40.645  5825  5848 I bt_btu  : btu_task received preload complete event
,09-28 09:45:40.651  5825  5848 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 09:45:40.651  5825  5848 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 09:45:40.651  5825  5848 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 09:45:40.651  5825  5848 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_A2D
,09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_BNEP
09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_PAN
,09-28 09:45:40.652  5825  5848 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 09:45:40.653  5825  5848 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 09:45:40.653  5825  5848 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 09:45:40.653  5825  5848 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 09:45:40.653  5825  5848 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 09:45:40.734  5825  5848 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4147549
,09-28 09:45:40.734  5825  5848 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4147549 
,09-28 09:45:40.750  5825  5841 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 09:45:40.751  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 09:45:40.751  5825  5841 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 09:45:40.754  5825  5841 D BluetoothAdapterProperties: Name is: Nexus 6P
09-28 09:45:40.756  5825  5841 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:45:40.757  5825  5841 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 09:45:40.757  5825  5841 D bt_hci  : do_postload posting postload work item
09-28 09:45:40.757  5825  5845 I bt_hci  : event_postload
09-28 09:45:40.757  5825  5845 I bt_vendor: sco_config_cb
09-28 09:45:40.757  5825  5845 I bt_hci  : sco_config_callback postload finished.
,09-28 09:45:40.762  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:40.763  5825  5841 D bt_bte_conf: Device ID record 1 : primary
,09-28 09:45:40.763  5825  5841 D bt_bte_conf:   vendorId            = 000f
09-28 09:45:40.763  5825  5841 D bt_bte_conf:   vendorIdSource      = 0001
09-28 09:45:40.763  5825  5841 D bt_bte_conf:   product             = 1200
09-28 09:45:40.763  5825  5841 D bt_bte_conf:   version             = 1436
09-28 09:45:40.764  5825  5841 D bt_bte_conf:   clientExecutableURL = 
09-28 09:45:40.764  5825  5841 D bt_bte_conf:   serviceDescription  = 
09-28 09:45:40.764  5825  5841 D bt_bte_conf:   documentationURL    = 
09-28 09:45:40.764  5825  5841 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 09:45:40.764  5825  5838 D bt_stack_manager: event_start_up_stack finished
,09-28 09:45:40.767  5825  5845 I bt_vendor: low_power_mode_cb
,09-28 09:45:40.768  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:40.771  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:40.771  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 09:45:40.771  5825  5837 D BluetoothAdapterProperties: Setting state to 15
09-28 09:45:40.772  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 09:45:40.773  5825  5837 I BluetoothAdapterState: Entering BleOnState
,09-28 09:45:40.778  5825  5837 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-28 09:45:40.778  5825  5837 D BluetoothAdapterProperties: Setting state to 11
09-28 09:45:40.778  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 09:45:40.787  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:40.792  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:40.792  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:40.792  5825  5825 D HeadsetService: Received start request. Starting profile...
09-28 09:45:40.794  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:40.795  5825  5825 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 09:45:40.795  5825  5825 D HeadsetStateMachine: make
,09-28 09:45:40.805  5825  5837 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:45:40.805  5825  5825 D HeadsetStateMachine: max_hf_connections = 1
09-28 09:45:40.806  5825  5825 I bt_bluedroid: get_profile_interface handsfree
09-28 09:45:40.806  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 09:45:40.806  5825  5841 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-28 09:45:40.810  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:40.811  5825  5825 D A2dpService: Received start request. Starting profile...
09-28 09:45:40.811  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:45:40.812  5825  5825 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 09:45:40.812  5825  5825 I bt_bluedroid: get_profile_interface avrcp
,09-28 09:45:40.818  5825  5825 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 09:45:40.818  5825  5825 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 09:45:40.818  5825  5825 D A2dpStateMachine: make
,09-28 09:45:40.820  5825  5825 I bt_bluedroid: get_profile_interface a2dp
,09-28 09:45:40.821  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 09:45:40.823  5825  5856 D A2dpStateMachine: Enter Disconnected: -2
,09-28 09:45:40.823  5825  5825 I BluetoothHidServiceJni: classInitNative: succeeds
,09-28 09:45:40.824  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:40.825  5684  5684 D BluetoothInputDevice: Proxy object connected
,09-28 09:45:40.825  5825  5825 D HidService: Received start request. Starting profile...
09-28 09:45:40.826  5825  5825 I bt_bluedroid: get_profile_interface hidhost
09-28 09:45:40.826  5825  5825 D HidService: setHidService(): set to: null
09-28 09:45:40.826  5825  5841 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf412856d
09-28 09:45:40.826  5684  5684 D HidProfile: Bluetooth service connected
09-28 09:45:40.826  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 09:45:40.826  5825  5825 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 09:45:40.827  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:40.828  5825  5825 D HealthService: Received start request. Starting profile...
,09-28 09:45:40.829  5825  5825 I bt_bluedroid: get_profile_interface health
,09-28 09:45:40.830  5825  5825 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 09:45:40.831  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:40.832  5825  5825 D PanService: Received start request. Starting profile...
09-28 09:45:40.832  5684  5684 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:45:40.832  5825  5825 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 09:45:40.832  5825  5825 I bt_bluedroid: get_profile_interface pan
09-28 09:45:40.832  5684  5684 D PanProfile: Bluetooth service connected
09-28 09:45:40.832  5825  5841 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 09:45:40.836  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:40.837  5825  5825 D BluetoothMapService: Received start request. Starting profile...
,09-28 09:45:40.837  5825  5825 D BluetoothMapService: start()
09-28 09:45:40.840  5825  5825 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-28 09:45:40.841  5825  5825 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 09:45:40.841  5825  5825 D BluetoothMapAppObserver: createReceiver()
09-28 09:45:40.842  5825  5825 D BluetoothMapAppObserver: initObservers()
,09-28 09:45:40.842  5825  5825 D BluetoothMapAppObserver: getEnabledAccountItems()
09-28 09:45:40.848  5825  5825 V SapService: SapBinder()
09-28 09:45:40.848  5825  5825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:40.849  5684  5684 D BluetoothMap: Proxy object connected
09-28 09:45:40.849  5684  5684 D MapProfile: Bluetooth service connected
09-28 09:45:40.849  5684  5684 D BluetoothMap: getConnectedDevices()
09-28 09:45:40.850  5825  5825 D SapService: Received start request. Starting profile...
09-28 09:45:40.850  5825  5825 V SapService: start()
09-28 09:45:40.851  5825  5825 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:40.852  5825  5825 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:40.852  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:40.852  5825  5854 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 09:45:40.852  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:40.852  5684  5684 D BluetoothMap: Bluetooth is Not enabled
09-28 09:45:40.852  5825  5825 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:45:40.852  5825  5825 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:40.853  5825  5825 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:40.854  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:40.855  5825  5825 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:40.855  5825  5825 V BluetoothAdapterState: isTurningOn()=true
,09-28 09:45:40.855  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:40.855  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:40.855  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 09:45:40.855  5825  5837 D BluetoothAdapterProperties: ScanMode =  20
09-28 09:45:40.855  5825  5837 D BluetoothAdapterProperties: State =  11
09-28 09:45:40.856  5825  5837 D BluetoothAdapterProperties: Setting state to 12
09-28 09:45:40.856  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-28 09:45:40.856  5825  5837 I BluetoothAdapterState: Entering OnState
09-28 09:45:40.857  3105  3118 D BluetoothPan: onBluetoothStateChange on: true
09-28 09:45:40.858  5825  5841 D BluetoothAdapterProperties: Scan Mode:21
09-28 09:45:40.858  5825  5841 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 09:45:40.860  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:45:40.860  3105  3105 D PanProfile: Bluetooth service connected
09-28 09:45:40.860  5684  5697 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-28 09:45:40.860  3105  3905 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:45:40.861   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:45:40.861  3759  3792 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:40.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:40.862  5684  5695 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 09:45:40.863   926   926 D BluetoothA2dp: Proxy object connected
09-28 09:45:40.863   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:45:40.864  5684  5697 D BluetoothMap: onBluetoothStateChange: up=true
09-28 09:45:40.864  3105  3967 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:45:40.864  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:40.865  3105  3105 D BluetoothA2dp: Proxy object connected
09-28 09:45:40.865   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:45:40.866  3105  3119 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 09:45:40.867  3105  3105 D BluetoothInputDevice: Proxy object connected
09-28 09:45:40.867  5684  5695 D BluetoothPan: onBluetoothStateChange on: true
09-28 09:45:40.867  5825  5825 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:45:40.867  3105  3105 D HidProfile: Bluetooth service connected
09-28 09:45:40.868  5825  5825 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:40.868  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:40.870  5825  5825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:45:40.870  3105  3118 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 09:45:40.871  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:40.871  3105  3905 D BluetoothMap: onBluetoothStateChange: up=true
09-28 09:45:40.872  5825  5825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:40.873   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:45:40.873  3105  3105 D BluetoothMap: Proxy object connected
09-28 09:45:40.873  3105  3105 D MapProfile: Bluetooth service connected
09-28 09:45:40.873  3105  3105 D BluetoothMap: getConnectedDevices()
09-28 09:45:40.874   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,09-28 09:45:40.874  5825  5825 D ObexServerSockets: Succeed to create listening sockets 
,09-28 09:45:40.875  5825  5825 D ObexServerSockets0: startAccept()
,09-28 09:45:40.875  5825  5825 D ObexServerSockets0: prepareForNewConnect()
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:40.876  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:40.877  5825  5825 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 09:45:40.877  5825  5825 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 09:45:40.878  5825  5864 D ObexServerSockets0: Accepting socket connection...
09-28 09:45:40.878  5825  5825 D BluetoothMapService: onReceive
09-28 09:45:40.878  5825  5825 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-28 09:45:40.878  5684  5684 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-28 09:45:40.878  5825  5865 D ObexServerSockets0: Accepting socket connection...
09-28 09:45:40.878  5825  5825 D BluetoothMapService: STATE_ON
09-28 09:45:40.880  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:40.881  5825  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:45:40.881  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:40.881  5825  5866 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 09:45:40.882  5825  5866 D BluetoothSdpJni: SDP Create record success - handle: 1
09-28 09:45:40.882  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:40.883  5684  5684 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-28 09:45:40.883  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:40.890  5684  5684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 09:45:40.891  5684  5684 D BluetoothA2dp: Proxy object connected
,09-28 09:45:40.896  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:45:40.897  5684  5684 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:45:40.903  5684  5684 D BluetoothPbap: Proxy object connected
,09-28 09:45:40.903  5825  5825 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:45:40.903  5825  5825 D ObexServerSockets0: prepareForNewConnect()
09-28 09:45:40.903  5684  5684 D PbapServerProfile: Bluetooth service connected
,09-28 09:45:40.905  3105  3105 D BluetoothPbap: Proxy object connected
09-28 09:45:40.905  3105  3105 D PbapServerProfile: Bluetooth service connected
,09-28 09:45:40.911  5825  5870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:40.924  5825  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:40.925  5825  5874 I BtOppRfcommListener: Accept thread started.
,09-28 09:45:40.962   926   926 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.962   926   926 D BluetoothHeadset: Proxy object connected
09-28 09:45:40.962   926   926 D BluetoothHeadset: Proxy object connected
09-28 09:45:40.963  3105  3967 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.963  3105  3105 D HeadsetProfile: Bluetooth service connected
09-28 09:45:40.963   926   943 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.964  3759  4105 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.966   926   943 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.973   926   943 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.986  5684  5695 D BluetoothHeadset: Proxy object connected
,09-28 09:45:40.988  5684  5684 D HeadsetProfile: Bluetooth service connected
,09-28 09:45:41.047   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:45:42.048   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 09:45:42.653   926  2982 D ConnectivityService: handlePromptUnvalidated 101
,09-28 09:45:44.829  5825  5837 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 09:45:44.829  5825  5837 D BluetoothAdapterProperties: Setting state to 13
,09-28 09:45:44.829  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 09:45:44.830  5825  5837 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 09:45:44.832  5825  5837 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:45:44.837  5825  5825 D BluetoothMapService: onReceive
,09-28 09:45:44.837  5825  5825 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 09:45:44.837  5825  5825 D BluetoothMapService: STATE_TURNING_OFF
,09-28 09:45:44.838  5825  5825 D BluetoothMapService: MAP Service closeService in
,09-28 09:45:44.838  5825  5825 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 09:45:44.838  5825  5825 D ObexServerSockets0: shutdown(block = true)
09-28 09:45:44.840  5825  5825 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:45:44.840  5825  5825 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 09:45:44.840  5825  5850 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 09:45:44.840  5825  5864 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 09:45:44.841  5825  5865 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 09:45:44.842  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:44.842  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:44.843  5825  5825 I BtOppRfcommListener: stopping Accept Thread
09-28 09:45:44.844  5825  5874 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 09:45:44.844  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:44.844  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 09:45:44.846  5825  5874 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 09:45:44.847  5825  5841 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:45:44.848  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-28 09:45:44.848  5684  5684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 09:45:44.853  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:44.853  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:44.855  5825  5825 D HeadsetService: Received stop request...Stopping profile...
09-28 09:45:44.855  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:44.855  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:44.858  5684  5695 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:44.858   926   926 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:44.858   926   926 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:44.858   926   926 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:44.859  3105  3967 D BluetoothHeadset: Proxy object disconnected
,09-28 09:45:44.860  3759  3788 D BluetoothHeadset: Proxy object disconnected
09-28 09:45:44.860  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:44.861  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:44.863  5631  5631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 09:45:44.863  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:44.863  5825  5825 V BluetoothAdapterState: isTurningOff()=true
,09-28 09:45:44.864  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:44.864  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.864  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:44.864  5825  5825 D A2dpService: Received stop request...Stopping profile...
09-28 09:45:44.865  5825  5856 D A2dpStateMachine: Exit Disconnected: -1
09-28 09:45:44.866   926   926 D BluetoothA2dp: Proxy object disconnected
09-28 09:45:44.867  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.869  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.870  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.871  3105  3105 D HeadsetProfile: Bluetooth service disconnected
09-28 09:45:44.871  3105  3105 D BluetoothA2dp: Proxy object disconnected
09-28 09:45:44.872  5825  5825 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-28 09:45:44.872  5825  5825 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 09:45:44.872  5825  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:44.872  5825  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:44.872  5825  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:44.873  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 09:45:44.874  5825  5841 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 09:45:44.875  5825  5825 D HidService: Received stop request...Stopping profile...
09-28 09:45:44.875  5684  5684 D DockEventReceiver: finishStartingService: stopping service
09-28 09:45:44.875  5825  5825 D HidService: Stopping Bluetooth HidService
09-28 09:45:44.877  3105  3105 D BluetoothInputDevice: Proxy object disconnected
09-28 09:45:44.877  3105  3105 D HidProfile: Bluetooth service disconnected
09-28 09:45:44.877  5825  5825 D HealthService: Received stop request...Stopping profile...
09-28 09:45:44.879  5825  5825 D PanService: Received stop request...Stopping profile...
09-28 09:45:44.881  3105  3105 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 09:45:44.881  3105  3105 D PanProfile: Bluetooth service disconnected
09-28 09:45:44.881  5684  5684 D HeadsetProfile: Bluetooth service disconnected
09-28 09:45:44.882  5684  5684 D BluetoothA2dp: Proxy object disconnected
,09-28 09:45:44.882  5825  5825 D BluetoothMapService: Received stop request...Stopping profile...
09-28 09:45:44.882  5825  5825 D BluetoothMapService: stop()
09-28 09:45:44.883  5684  5684 D BluetoothInputDevice: Proxy object disconnected
09-28 09:45:44.883  5684  5684 D HidProfile: Bluetooth service disconnected
09-28 09:45:44.883  5684  5684 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 09:45:44.883  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:45:44.883  5684  5684 D PanProfile: Bluetooth service disconnected
,09-28 09:45:44.885  5825  5825 D BluetoothMapAppObserver: deinitObservers()
09-28 09:45:44.885  5825  5825 D BluetoothMapAppObserver: removeReceiver()
09-28 09:45:44.887  3105  3105 D BluetoothMap: Proxy object disconnected
09-28 09:45:44.887  3105  3105 D MapProfile: Bluetooth service disconnected
09-28 09:45:44.887  5825  5825 D SapService: Received stop request...Stopping profile...
09-28 09:45:44.887  5825  5825 V SapService: stop()
09-28 09:45:44.889  5825  5825 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:44.889  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:44.889  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.889  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:44.890  5684  5684 D BluetoothMap: Proxy object disconnected
09-28 09:45:44.890  5684  5684 D MapProfile: Bluetooth service disconnected
09-28 09:45:44.891  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 09:45:44.891  5825  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:44.891  5825  5825 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:44.891  5825  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:44.891  5825  5825 V BluetoothAdapterState: isTurningOn()=false
,09-28 09:45:44.891  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.891  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:44.891  5825  5848 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:45:44.891  5825  5848 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:45:44.891  5825  5848 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 09:45:44.892  5825  5848 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 09:45:44.892  5825  5825 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 09:45:44.892  5825  5825 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 09:45:44.892  5825  5841 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 09:45:44.892  5825  5825 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:44.892  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:44.892  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.892  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:44.892  5825  5825 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 09:45:44.893  5825  5841 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 09:45:44.893  5825  5825 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 09:45:44.893  5825  5825 V BluetoothAdapterState: isTurningOff()=true
09-28 09:45:44.893  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:44.893  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.894  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:44.894  5825  5825 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 09:45:44.894  5825  5825 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 09:45:44.897  3105  3105 D BluetoothPbap: Proxy object disconnected
09-28 09:45:44.897  3105  3105 D PbapServerProfile: Bluetooth service disconnected
,09-28 09:45:44.898  5825  5825 D BluetoothMapService: MAP Service closeService in
09-28 09:45:44.898  5825  5825 V BluetoothAdapterState: isTurningOff()=true
,09-28 09:45:44.898  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:44.898  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.898  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:45:44.899  5825  5825 D BluetoothMapService: cleanup()
09-28 09:45:44.899  5825  5825 D BluetoothMapService: MAP Service closeService in
09-28 09:45:44.899  5825  5825 V BluetoothAdapterState: isTurningOff()=true
,09-28 09:45:44.900  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:44.900  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:44.900  5825  5825 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:45:44.900  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-28 09:45:44.900  5825  5837 D BluetoothAdapterProperties: Setting state to 15
,09-28 09:45:44.900  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 09:45:44.901  5825  5837 I BluetoothAdapterState: Entering BleOnState
,09-28 09:45:44.901  3105  3119 D BluetoothPan: onBluetoothStateChange on: false
,09-28 09:45:44.901  5684  5684 D BluetoothPbap: Proxy object disconnected
09-28 09:45:44.901  5684  5684 D PbapServerProfile: Bluetooth service disconnected
09-28 09:45:44.902  5684  5697 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-28 09:45:44.903  5684  5695 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 09:45:44.904  3105  3967 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:44.904   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:45:44.904  3759  3992 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:44.904  5684  5697 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 09:45:44.905   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:44.905  5684  5695 D BluetoothMap: onBluetoothStateChange: up=false
09-28 09:45:44.906  3105  3118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 09:45:44.907  5684  5697 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:44.908   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:44.908  3105  3119 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 09:45:44.909  5684  5695 D BluetoothPan: onBluetoothStateChange on: false
,09-28 09:45:44.910  3105  3967 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 09:45:44.910  3105  3905 D BluetoothMap: onBluetoothStateChange: up=false
09-28 09:45:44.911   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 09:45:44.911  5825  5837 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 09:45:44.911  5825  5837 D BluetoothAdapterProperties: Setting state to 16
09-28 09:45:44.911  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 09:45:44.912  5825  5837 D BluetoothAdapterProperties: onBleDisable
09-28 09:45:44.913  5825  5837 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:45:44.913  5825  5838 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-28 09:45:44.914  5825  5848 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 09:45:44.914  5825  5848 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 09:45:44.914  5825  5841 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:45:44.915  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.916  5684  5684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 09:45:44.917  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.919  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.921  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 09:45:44.928  5684  5684 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:45:44.931  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.932  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:44.933  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:45.123  5825  5841 I bt_hci  : shut_down
,09-28 09:45:45.135  5825  5845 D bt_hwcfg: hw_epilog_process
,09-28 09:45:45.135  5825  5845 I bt_vendor: low_power_mode_cb
,09-28 09:45:45.138  5825  5845 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 09:45:45.138  5825  5845 I bt_vendor: epilog_cb
09-28 09:45:45.138  5825  5845 I bt_hci  : epilog_finished_callback
,09-28 09:45:45.141  5825  5841 I bt_hci_h4: hal_close
,09-28 09:45:45.141  5825  5841 I bt_userial_vendor: device fd = 54 close
,09-28 09:45:45.256  5825  5838 D bt_stack_manager: event_shut_down_stack finished.
,09-28 09:45:45.260  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 09:45:45.265  5825  5825 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 09:45:45.265  5825  5837 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 09:45:45.266  5825  5825 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 09:45:45.266  5825  5825 D BtGatt.GattService: stop()
09-28 09:45:45.266  5825  5825 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 09:45:45.270  5825  5825 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:45:45.270  5825  5825 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:45.271  5825  5825 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:45.271  5825  5825 V BluetoothAdapterState: isBleTurningOff()=true
09-28 09:45:45.271  5825  5837 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-28 09:45:45.274  5825  5837 D BluetoothAdapterProperties: Setting state to 10
,09-28 09:45:45.274  5825  5837 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 09:45:45.276  5825  5837 I BluetoothAdapterState: Entering OffState
09-28 09:45:45.277   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 09:45:45.297  5825  5825 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 09:45:45.297  5825  5825 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 09:45:45.297  5825  5825 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-28 09:45:45.300  5825  5838 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 09:45:45.311  5825  5825 I art     : System.exit called, status: 0
,09-28 09:45:45.312  5825  5825 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 09:45:45.344   926  3188 I ActivityManager: Process com.android.bluetooth (pid 5825) has died
,09-28 09:45:49.827  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:45:49.827  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:49.831  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:49.832  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f48db9 removed from the list
,09-28 09:45:49.832  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:49.832  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:49.832  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:49.837  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 09:45:49.837  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@87d815f added. We now have 4 listener(s)
09-28 09:45:49.837  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:45:49.839  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:49.839  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@87d815f removed from the list
09-28 09:45:49.839  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 09:45:49.840  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:49.840  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:45:49.842  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 09:45:49.842  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95537ac added. We now have 4 listener(s)
09-28 09:45:49.842  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:45:54.854  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:54.886   926   943 I ActivityManager: Start proc 5882:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 09:45:54.974  5882  5882 D AdapterServiceConfig: Adding HeadsetService
,09-28 09:45:54.974  5882  5882 D AdapterServiceConfig: Adding A2dpService
09-28 09:45:54.974  5882  5882 D AdapterServiceConfig: Adding HidService
09-28 09:45:54.975  5882  5882 D AdapterServiceConfig: Adding HealthService
09-28 09:45:54.975  5882  5882 D AdapterServiceConfig: Adding PanService
09-28 09:45:54.975  5882  5882 D AdapterServiceConfig: Adding GattService
09-28 09:45:54.975  5882  5882 D AdapterServiceConfig: Adding BluetoothMapService
09-28 09:45:54.975  5882  5882 D AdapterServiceConfig: Adding SapService
,09-28 09:45:54.986   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ebc45d:true
,09-28 09:45:54.986  5882  5882 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 09:45:54.989  5882  5882 I bt_bluedroid: init
,09-28 09:45:54.990  5882  5894 I BluetoothAdapterState: Entering OffState
,09-28 09:45:54.992  5882  5895 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 09:45:54.992  5882  5895 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 09:45:54.992  5882  5895 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 09:45:54.992  5882  5895 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 09:45:54.993  5882  5882 I bt_bluedroid: get_profile_interface socket
,09-28 09:45:54.995  5882  5898 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 09:45:54.996  5882  5882 I bt_bluedroid: get_profile_interface sdp
09-28 09:45:54.996  5882  5898 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 09:45:55.002  5882  5893 I bt_bluedroid: config_hci_snoop_log
,09-28 09:45:55.003   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 09:45:55.007  5882  5894 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 09:45:55.007  5882  5894 D BluetoothAdapterProperties: Setting state to 14
09-28 09:45:55.007  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 09:45:55.009  5882  5894 D BluetoothBondStateMachine: make
,09-28 09:45:55.011  5882  5899 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 09:45:55.013  5882  5894 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:45:55.015  5882  5882 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 09:45:55.017  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:55.018  5882  5882 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 09:45:55.019  5882  5882 D BtGatt.GattService: Received start request. Starting profile...
09-28 09:45:55.019  5882  5882 D BtGatt.GattService: start()
09-28 09:45:55.019  5882  5882 I bt_bluedroid: get_profile_interface gatt
09-28 09:45:55.020  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:55.021  5882  5882 D BtGatt.AdvertiseManager: advertise manager created
,09-28 09:45:55.026  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:55.026  5882  5882 V BluetoothAdapterState: isTurningOn()=false
09-28 09:45:55.026  5882  5882 V BluetoothAdapterState: isBleTurningOn()=true
09-28 09:45:55.026  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:55.027  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 09:45:55.028  5882  5894 I bt_bluedroid: bt_bluedroid
09-28 09:45:55.028  5882  5895 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 09:45:55.028  5882  5895 I bt_hci  : start_up
,09-28 09:45:55.033  5882  5895 I bt_vendor: alloc value 0xf41c9871
,09-28 09:45:55.033  5882  5895 I bt_vendor: init
09-28 09:45:55.033  5882  5895 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 09:45:55.033  5882  5895 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 09:45:55.144  5882  5895 D bt_hci  : start_up starting async portion
09-28 09:45:55.145  5882  5902 I bt_hci  : event_finish_startup
09-28 09:45:55.145  5882  5902 I bt_hci_h4: hal_open
09-28 09:45:55.145  5882  5902 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 09:45:55.149  5882  5902 I bt_userial_vendor: device fd = 54 open
,09-28 09:45:55.145  5903  5903 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 09:45:55.165  5882  5902 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 09:45:55.169  5882  5902 D bt_hwcfg: Chipset BCM4358A3
09-28 09:45:55.169  5882  5902 D bt_hwcfg: Target name = [BCM4358A3]
,09-28 09:45:55.169  5882  5902 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 09:45:55.676  5882  5902 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 09:45:55.676  5882  5902 D bt_hwcfg: Settlement delay -- 100 ms
09-28 09:45:55.676  5882  5902 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 09:45:55.810  5882  5902 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 09:45:55.811  5882  5902 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 09:45:55.812  5882  5902 I bt_hwcfg: vendor lib fwcfg completed
09-28 09:45:55.813  5882  5902 I bt_vendor: firmware callback
09-28 09:45:55.813  5882  5902 I bt_hci  : firmware_config_callback
,09-28 09:45:55.821  5882  5905 I bt_btu  : btu_task pending for preload complete event
09-28 09:45:55.821  5882  5905 I bt_btu_task: Bluetooth chip preload is complete
,09-28 09:45:55.821  5882  5905 I bt_btu  : btu_task received preload complete event
,09-28 09:45:55.827  5882  5905 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 09:45:55.827  5882  5905 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-28 09:45:55.827  5882  5905 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_BNEP
09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_GAP
,09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 09:45:55.828  5882  5905 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 09:45:55.829  5882  5905 I         : BTE_InitTraceLevels -- TRC_GATT
,09-28 09:45:55.829  5882  5905 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 09:45:55.829  5882  5905 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-28 09:45:55.829  5882  5905 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 09:45:55.930  5882  5905 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4147549
09-28 09:45:55.930  5882  5905 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4147549 
,09-28 09:45:55.961  5882  5898 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-28 09:45:55.962  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 09:45:55.962  5882  5898 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 09:45:55.964  5882  5898 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 09:45:55.967  5882  5898 D BluetoothAdapterProperties: Scan Mode:20
09-28 09:45:55.967  5882  5898 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 09:45:55.968  5882  5898 D bt_hci  : do_postload posting postload work item
09-28 09:45:55.968  5882  5902 I bt_hci  : event_postload
09-28 09:45:55.968  5882  5902 I bt_vendor: sco_config_cb
,09-28 09:45:55.968  5882  5902 I bt_hci  : sco_config_callback postload finished.
09-28 09:45:55.970  5882  5898 D bt_bte_conf: Device ID record 1 : primary
,09-28 09:45:55.971  5882  5898 D bt_bte_conf:   vendorId            = 000f
09-28 09:45:55.971  5882  5898 D bt_bte_conf:   vendorIdSource      = 0001
,09-28 09:45:55.971  5882  5898 D bt_bte_conf:   product             = 1200
09-28 09:45:55.971  5882  5898 D bt_bte_conf:   version             = 1436
,09-28 09:45:55.971  5882  5898 D bt_bte_conf:   clientExecutableURL = 
09-28 09:45:55.971  5882  5898 D bt_bte_conf:   serviceDescription  = 
09-28 09:45:55.971  5882  5898 D bt_bte_conf:   documentationURL    = 
09-28 09:45:55.971  5882  5898 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 09:45:55.971  5882  5895 D bt_stack_manager: event_start_up_stack finished
09-28 09:45:55.971  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:55.973  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 09:45:55.974  5882  5894 D BluetoothAdapterProperties: Setting state to 15
09-28 09:45:55.974  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 09:45:55.978  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:55.978  5882  5894 I BluetoothAdapterState: Entering BleOnState
,09-28 09:45:55.980  5882  5902 I bt_vendor: low_power_mode_cb
09-28 09:45:55.982  5882  5894 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 09:45:55.983  5882  5894 D BluetoothAdapterProperties: Setting state to 11
09-28 09:45:55.983  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-28 09:45:55.988  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:55.991  5882  5882 D HeadsetService: Received start request. Starting profile...
09-28 09:45:55.993  5882  5882 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-28 09:45:55.993  5882  5882 D HeadsetStateMachine: make
,09-28 09:45:55.998  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:56.000  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:45:56.007  5882  5894 I BluetoothAdapterState: Entering PendingCommandState
,09-28 09:45:56.012  5882  5882 D HeadsetStateMachine: max_hf_connections = 1
09-28 09:45:56.012  5882  5882 I bt_bluedroid: get_profile_interface handsfree
09-28 09:45:56.012  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-28 09:45:56.013  5882  5898 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-28 09:45:56.015  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:56.015  5882  5882 D A2dpService: Received start request. Starting profile...
,09-28 09:45:56.016  5882  5882 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 09:45:56.016  5882  5882 I bt_bluedroid: get_profile_interface avrcp
,09-28 09:45:56.022  5882  5882 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 09:45:56.022  5882  5882 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 09:45:56.022  5882  5882 D A2dpStateMachine: make
09-28 09:45:56.023  5882  5882 I bt_bluedroid: get_profile_interface a2dp
,09-28 09:45:56.024  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-28 09:45:56.025  5882  5913 D A2dpStateMachine: Enter Disconnected: -2
09-28 09:45:56.025  5882  5882 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 09:45:56.026  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:56.027  5882  5882 D HidService: Received start request. Starting profile...
09-28 09:45:56.027  5882  5882 I bt_bluedroid: get_profile_interface hidhost
09-28 09:45:56.027  5882  5882 D HidService: setHidService(): set to: null
09-28 09:45:56.027  5882  5898 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf412856d
09-28 09:45:56.027  5882  5898 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 09:45:56.028  5882  5882 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 09:45:56.028  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:56.029  5882  5882 D HealthService: Received start request. Starting profile...
,09-28 09:45:56.030  5882  5882 I bt_bluedroid: get_profile_interface health
,09-28 09:45:56.031  5882  5882 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 09:45:56.031  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:56.032  5882  5882 D PanService: Received start request. Starting profile...
09-28 09:45:56.032  5882  5882 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 09:45:56.032  5882  5882 I bt_bluedroid: get_profile_interface pan
,09-28 09:45:56.032  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:45:56.033  5882  5898 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 09:45:56.033  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
09-28 09:45:56.035  5882  5882 D BluetoothMapService: Received start request. Starting profile...
09-28 09:45:56.035  5882  5882 D BluetoothMapService: start()
09-28 09:45:56.036  5882  5882 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-28 09:45:56.037  5882  5882 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 09:45:56.037  5882  5882 D BluetoothMapAppObserver: createReceiver()
09-28 09:45:56.038  5882  5882 D BluetoothMapAppObserver: initObservers()
09-28 09:45:56.038  5882  5882 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 09:45:56.042  5882  5882 V SapService: SapBinder()
09-28 09:45:56.042  5882  5882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:45:56.043  5882  5882 D SapService: Received start request. Starting profile...
09-28 09:45:56.043  5882  5882 V SapService: start()
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isTurningOff()=false
,09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:56.044  5882  5911 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.044  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.045  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
09-28 09:45:56.046  5882  5882 V BluetoothAdapterState: isTurningOff()=false
09-28 09:45:56.046  5882  5882 V BluetoothAdapterState: isTurningOn()=true
09-28 09:45:56.046  5882  5882 V BluetoothAdapterState: isBleTurningOn()=false
09-28 09:45:56.046  5882  5882 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 09:45:56.047  5882  5894 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 09:45:56.047  5882  5894 D BluetoothAdapterProperties: ScanMode =  20
09-28 09:45:56.047  5882  5894 D BluetoothAdapterProperties: State =  11
,09-28 09:45:56.047  5882  5894 D BluetoothAdapterProperties: Setting state to 12
09-28 09:45:56.047  5882  5894 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 09:45:56.048  3105  3118 D BluetoothPan: onBluetoothStateChange on: true
09-28 09:45:56.048  5882  5894 I BluetoothAdapterState: Entering OnState
09-28 09:45:56.048  5882  5898 D BluetoothAdapterProperties: Scan Mode:21
09-28 09:45:56.048  5882  5898 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 09:45:56.051  3105  3105 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:45:56.051  3105  3105 D PanProfile: Bluetooth service connected
,09-28 09:45:56.053  5684  5697 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:56.053  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:56.056  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:56.056  5684  5697 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 09:45:56.059  3105  3967 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:45:56.060   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:45:56.060  5684  5684 D BluetoothA2dp: Proxy object connected
09-28 09:45:56.061   926   926 D BluetoothA2dp: Proxy object connected
09-28 09:45:56.061  3759  4105 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:56.061  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 09:45:56.062  5684  5697 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 09:45:56.063  5684  5684 D BluetoothInputDevice: Proxy object connected
,09-28 09:45:56.063  5684  5684 D HidProfile: Bluetooth service connected
09-28 09:45:56.063  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:56.064  5882  5882 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:45:56.064  5882  5882 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 09:45:56.065  5882  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:56.066   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 09:45:56.067  5684  5695 D BluetoothMap: onBluetoothStateChange: up=true
09-28 09:45:56.067  5882  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:45:56.068  5882  5882 D ObexServerSockets: Succeed to create listening sockets 
09-28 09:45:56.068  5882  5882 D ObexServerSockets0: startAccept()
,09-28 09:45:56.068  5882  5882 D ObexServerSockets0: prepareForNewConnect()
09-28 09:45:56.068  3105  3905 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 09:45:56.070  5882  5882 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 09:45:56.070  5882  5882 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 09:45:56.070  3105  3105 D BluetoothA2dp: Proxy object connected
09-28 09:45:56.070  5684  5697 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:45:56.071   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:45:56.071  3105  3119 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-28 09:45:56.072  5882  5922 D ObexServerSockets0: Accepting socket connection...
09-28 09:45:56.072  3105  3105 D BluetoothInputDevice: Proxy object connected
09-28 09:45:56.072  3105  3105 D HidProfile: Bluetooth service connected
09-28 09:45:56.073  5882  5921 D ObexServerSockets0: Accepting socket connection...
09-28 09:45:56.073  5684  5695 D BluetoothPan: onBluetoothStateChange on: true
09-28 09:45:56.075  5684  5684 D BluetoothMap: Proxy object connected
09-28 09:45:56.075  5684  5684 D MapProfile: Bluetooth service connected
09-28 09:45:56.075  5684  5684 D BluetoothMap: getConnectedDevices()
,09-28 09:45:56.079  3105  3905 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 09:45:56.080  3105  3118 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 09:45:56.081   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 09:45:56.081  3105  3105 D BluetoothMap: Proxy object connected
09-28 09:45:56.081  3105  3105 D MapProfile: Bluetooth service connected
09-28 09:45:56.081  3105  3105 D BluetoothMap: getConnectedDevices()
09-28 09:45:56.082  5684  5684 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 09:45:56.082  5684  5684 D PanProfile: Bluetooth service connected
09-28 09:45:56.082   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 09:45:56.083  5882  5882 D BluetoothMapService: onReceive
,09-28 09:45:56.083  5882  5882 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 09:45:56.083  5882  5882 D BluetoothMapService: STATE_ON
09-28 09:45:56.084  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:56.085  5882  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:45:56.085  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:45:56.086  5882  5924 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 09:45:56.086  5882  5924 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 09:45:56.087  5684  5684 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 09:45:56.094  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 09:45:56.095  5684  5684 D DockEventReceiver: finishStartingService: stopping service
,09-28 09:45:56.102  5684  5684 D BluetoothPbap: Proxy object connected
,09-28 09:45:56.102  5684  5684 D PbapServerProfile: Bluetooth service connected
,09-28 09:45:56.106  5882  5882 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 09:45:56.107  5882  5882 D ObexServerSockets0: prepareForNewConnect()
,09-28 09:45:56.108  5882  5928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:56.112  3105  3105 D BluetoothPbap: Proxy object connected
,09-28 09:45:56.112  3105  3105 D PbapServerProfile: Bluetooth service connected
,09-28 09:45:56.119  5882  5932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 09:45:56.121  5882  5932 I BtOppRfcommListener: Accept thread started.
,09-28 09:45:56.162  5684  5697 D BluetoothHeadset: Proxy object connected
,09-28 09:45:56.162   926   926 D BluetoothHeadset: Proxy object connected
09-28 09:45:56.162   926   926 D BluetoothHeadset: Proxy object connected
09-28 09:45:56.162   926   926 D BluetoothHeadset: Proxy object connected
09-28 09:45:56.162  3759  3788 D BluetoothHeadset: Proxy object connected
09-28 09:45:56.162  3105  3119 D BluetoothHeadset: Proxy object connected
09-28 09:45:56.163  3105  3105 D HeadsetProfile: Bluetooth service connected
09-28 09:45:56.163  3759  3992 D BluetoothHeadset: Proxy object connected
,09-28 09:45:56.165  5684  5684 D HeadsetProfile: Bluetooth service connected
09-28 09:45:56.167   926   943 D BluetoothHeadset: Proxy object connected
,09-28 09:45:56.171  5684  5923 D BluetoothHeadset: Proxy object connected
,09-28 09:45:56.172   926   943 D BluetoothHeadset: Proxy object connected
09-28 09:45:56.172  5684  5684 D HeadsetProfile: Bluetooth service connected
,09-28 09:45:56.182   926   943 D BluetoothHeadset: Proxy object connected
,09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:45:59.871  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:45:59.877  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:45:59.878  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:45:59.878  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95537ac removed from the list
09-28 09:45:59.878  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:45:59.878  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:45:59.878  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:45:59.881  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:45:59.881  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b474c75 added. We now have 4 listener(s)
09-28 09:45:59.881  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:45:59.884   926  3188 D WifiService: setWifiEnabled: false pid=5631, uid=10077
09-28 09:45:59.884   926  3188 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:46:02.049   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:03.050   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:04.052   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:04.894  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:04.895   926  3402 D WifiService: setWifiEnabled: true pid=5631, uid=10077
,09-28 09:46:04.896   926  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 09:46:04.905   507   920 D SoftapController: Softap fwReload - Ok
,09-28 09:46:04.911   507   920 D CommandListener: Setting iface cfg
09-28 09:46:04.911   507   920 D CommandListener: Trying to bring down wlan0
09-28 09:46:04.913   507   920 D CommandListener: Clearing all IP addresses on wlan0
,09-28 09:46:04.918   926  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 09:46:05.053   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:05.589   926  2980 D wifi    : set interface wlan0 flags (UP)
,09-28 09:46:05.589   926  2980 I WifiHAL : Initializing wifi
,09-28 09:46:05.591   926  2980 I WifiHAL : Creating socket
,09-28 09:46:05.597   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 09:46:05.599   926  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 09:46:05.600   926  2980 D wifi    : Did set static halHandle = 0x7f7ad91680
09-28 09:46:05.600   926  2980 D wifi    : halHandle = 0x7f7ad91680, mVM = 0x7f9740d140, mCls = 0x101922
09-28 09:46:05.600   926  2980 D wifi    : array field set
09-28 09:46:05.600   926  2980 I WifiNative-HAL: interface[0] = wlan0
09-28 09:46:05.602   926  5937 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547521894016
,09-28 09:46:05.602   926  5937 D wifi    : waitForHalEvents called, vm = 0x7f9740d140, obj = 0x101922, env = 0x7f7dedf900
,09-28 09:46:05.661  5938  5938 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 09:46:05.684  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:46:05.700  5938  5938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 09:46:05.700  5938  5938 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 09:46:05.703   926  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 09:46:05.714  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:05.717  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:05.724   926  2980 D WifiConfigStore: Loading config and enabling all networks 
,09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:46:05.730  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:46:05.732  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:46:05.734   926  2980 D WifiConfigStore: loaded 0 passpoint configs
,09-28 09:46:05.734   926  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 09:46:05.735   926  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 09:46:05.735  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 09:46:05.735   926  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 09:46:05.737   926  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-28 09:46:05.737   926  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 09:46:05.737   926  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 09:46:05.737   926  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-28 09:46:05.740  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 09:46:05.742   926  2980 D WifiNative-HAL: Setting external_sim to 1
,09-28 09:46:05.742   926  2980 D wifi    : setting dfs flag to true, 0x7f7d05b340
09-28 09:46:05.742  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 09:46:05.743   926  2980 D WifiStateMachine: Setting OUI to DA-A1-19
,09-28 09:46:05.743   926  2980 D wifi    : setting scan oui 0x7f7d05b340
09-28 09:46:05.743   926  2980 D WifiHAL : Sending mac address OUI
,09-28 09:46:05.748   926  2980 E native  : do suspend false
,09-28 09:46:05.756   926  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-28 09:46:05.756   926   926 D RttService: SCAN_AVAILABLE : 3
09-28 09:46:05.756   926  3046 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 09:46:05.756   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 09:46:05.757   507   920 D CommandListener: Setting iface cfg
,09-28 09:46:05.760   926  2977 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-28 09:46:05.760   926  2977 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 09:46:05.767   926  2977 D WifiNative-HAL: p2pGetDeviceAddress
09-28 09:46:05.768   926  2977 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 09:46:05.788   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303275 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=28 mControllerEnergyUsed=106 }
,09-28 09:46:06.054   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:07.054   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 09:46:08.931  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:46:08.935  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:46:08.940  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:46:08.945  5938  5938 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 09:46:09.000   926  2980 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 09:46:09.001   926  2980 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 09:46:09.002   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:46:09.013   926  2980 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 09:46:09.044   926  2980 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 09:46:09.045  5938  5938 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 09:46:09.472  5938  5938 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 09:46:09.511  5938  5938 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 09:46:09.511  5938  5938 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 09:46:09.524   926  2980 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-28 09:46:09.524   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:46:09.524   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 09:46:09.542   926  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 09:46:09.555   507   920 D CommandListener: Setting iface cfg
,09-28 09:46:09.562   926  2980 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 09:46:09.568   926  5943 D DhcpClient: Receive thread started
,09-28 09:46:09.572   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:46:09.573   926  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 09:46:09.573   926  2982 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 09:46:09.655   926  2980 E native  : do suspend false
,09-28 09:46:09.669   926  5942 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 09:46:09.683   926  5943 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null,
09-28 09:46:09.683   926  5942 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-28 09:46:09.685   926  5942 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 09:46:09.704   926  5943 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 09:46:09.705   926  5942 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 09:46:09.708   507   920 D CommandListener: Setting iface cfg
,09-28 09:46:09.712   926  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 09:46:09.718   926  5942 D DhcpClient: Scheduling renewal in 86399s
,09-28 09:46:09.726   926  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 09:46:09.727   926  2980 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 09:46:09.728   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-28 09:46:09.730   926  2982 D ConnectivityService: Adding iface wlan0 to network 102
,09-28 09:46:09.735   926  2980 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 09:46:09.777   926  2982 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 09:46:09.777   926  2982 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-28 09:46:09.781   926  2982 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-28 09:46:09.783   926  2982 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-28 09:46:09.785   926  2982 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 09:46:09.793   926  2982 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:46:09.797   926  2982 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-28 09:46:09.797   926  2982 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 09:46:09.797   926  2982 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 09:46:09.797   926  2982 D ConnectivityService:    accepting network in place of null
09-28 09:46:09.797   926  2980 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 09:46:09.797   926  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 09:46:09.798   926  2982 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 09:46:09.813   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307301, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:46:09.820   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:46:09.847   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 09:46:09.851   926  2982 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-28 09:46:09.851  3721  3871 W QCNEJ   : |CORE| network available: 102
,09-28 09:46:09.851   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:46:09.852   926  2982 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-28 09:46:09.853   926   943 D Tethering: MasterInitialState.processMessage what=3
09-28 09:46:09.855  3721  3871 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-28 09:46:09.858  3721  3871 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-28 09:46:09.859  3721  3871 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:09.863  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:46:09.866  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:09.871  5631  5631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:46:09.873  5631  5631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:46:09.877  5041  5072 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 09:46:09.877  5041  5072 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 09:46:09.877  5041  5072 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 09:46:09.877  5041  5072 E SarControlService: no key has been found,reset the power
09-28 09:46:09.877  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 09:46:09.877  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-28 09:46:09.877  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 09:46:09.878  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:46:09.878  5073  5073 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 09:46:09.879  5041  5084 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 09:46:09.879  5041  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 09:46:09.879  5041  5084 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 09:46:09.879  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 09:46:09.879  5073  5073 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 09:46:09.881  4933  4933 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-28 09:46:09.883  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 09:46:09.887  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000f003000000000000ffffffff]
09-28 09:46:09.887  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:46:09.887  5073  5088 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-28 09:46:09.887  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:46:09.888  5041  5052 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 09:46:09.888  3834  3834 D SystemUpdateService: onCreate
,09-28 09:46:09.893  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 09:46:09.895  5073  5088 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fa6334a HexData = [00000000f103000000000000ffffffff]
09-28 09:46:09.895  5073  5088 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 09:46:09.895  5073  5088 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 09:46:09.895  5073  5073 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 09:46:09.896  5041  5051 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 09:46:09.907  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:09.908  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:46:09.910  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:09.910  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:09.910  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b474c75 removed from the list
,09-28 09:46:09.910  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:46:09.910  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:09.910  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:09.913  5631  5957 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-28 09:46:09.913  5631  5957 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 09:46:09.915  3834  5408 I iu.UploadsManager: num queued entries: 0
,09-28 09:46:09.916  3834  5408 I iu.UploadsManager: num updated entries: 0
09-28 09:46:09.916  3834  5408 I iu.SyncManager: NEXT; no task
,09-28 09:46:09.918  3834  5953 I SystemUpdateService: active receiver: enabled
,09-28 09:46:09.919  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 09:46:09.921  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 09:46:09.923  5750  5750 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 09:46:09.926  5750  5750 D SprintDMHelper: simOperator: 
,09-28 09:46:09.927  5750  5750 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 09:46:09.948  3834  5953 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 09:46:09.964  3834  5953 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 09:46:09.964  3834  5953 I SystemUpdateService: now status is 0 (complete)
09-28 09:46:09.964  3834  5953 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 09:46:09.964  3834  5953 I SystemUpdateService: file has been verified
09-28 09:46:09.964  3834  5953 I SystemUpdateService: OTA package size = 21989297
,09-28 09:46:09.970  3834  5953 I SystemUpdateService: showing system update notification
,09-28 09:46:09.981  3834  3834 D SystemUpdateService: onDestroy
,09-28 09:46:10.032   926  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-28 09:46:10.141   926  5940 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 13:46:10 GMT], X-Android-Received-Millis=[1475070370139], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475070370079]}
,09-28 09:46:10.142   926  2982 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 09:46:10.143   926  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-28 09:46:10.143   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:46:10.148   926  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 09:46:10.150  5015  5959 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 09:46:12.594   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:46:12.925  5631  5957 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-28 09:46:12.925  5631  5966 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-28 09:46:12.926  5631  5957 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 09:46:12.926  5631  5966 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 09:46:12.927  5631  5957 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 09:46:12.927  5631  5966 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 09:46:12.928  5631  5957 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 09:46:12.928  5631  5966 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 09:46:12.931  5631  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender)
,09-28 09:46:12.932  5631  5957 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-28 09:46:12.933  5631  5966 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 09:46:12.936  5631  5968 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Sender)
,09-28 09:46:12.938  5631  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Receiver)
,09-28 09:46:12.938  5631  5971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver)
,09-28 09:46:12.939  5631  5971 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver)
09-28 09:46:12.939  5631  5970 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: OutgoingSocketThread/Receiver)
09-28 09:46:12.940  5631  5970 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-28 09:46:12.940  5631  5971 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 09:46:12.940  5631  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 09:46:12.940  5631  5971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 09:46:15.922  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 09:46:15.923  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 09:46:15.930  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9d875ee Bundle[{}]
,09-28 09:46:15.931  5631  5677 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 09:46:15.932  5631  5677 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-28 09:46:15.934  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-28 09:46:15.935  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-28 09:46:15.936  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-28 09:46:15.937  5631  5677 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-28 09:46:15.944  5631  5677 I System.out: Running OutgoingSocketThread
,09-28 09:46:15.947  5631  5972 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-28 09:46:15.947  5631  5972 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 09:46:17.804   926  2982 D ConnectivityService: handlePromptUnvalidated 102
,09-28 09:46:18.959  5631  5973 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-28 09:46:18.959  5631  5973 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 09:46:18.959  5631  5972 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-28 09:46:18.959  5631  5973 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 09:46:18.959  5631  5972 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 09:46:18.960  5631  5972 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 09:46:18.962  5631  5973 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 09:46:18.963  5631  5972 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 09:46:18.966  5631  5976 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender)
,09-28 09:46:18.966  5631  5973 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 09:46:18.968  5631  5972 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-28 09:46:18.969  5631  5975 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Sender)
,09-28 09:46:18.970  5631  5977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Receiver)
09-28 09:46:18.971  5631  5978 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver)
,09-28 09:46:18.972  5631  5978 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver)
,09-28 09:46:18.973  5631  5978 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 09:46:18.973  5631  5977 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Receiver)
09-28 09:46:18.973  5631  5978 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 09:46:18.973  5631  5977 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-28 09:46:18.973  5631  5977 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 09:46:20.771   926  2980 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-28 09:46:21.956  5631  5677 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,09-28 09:46:21.957  5631  5677 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-28 09:46:21.957  5631  5677 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-28 09:46:21.963  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 09:46:21.963  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e25640a added. We now have 3 listener(s)
,09-28 09:46:21.967  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 09:46:21.968  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:46:21.968  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:46:21.968  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:46:21.968  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@422d47b added. We now have 4 listener(s)
09-28 09:46:21.968  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:46:21.969  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 09:46:21.974  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:21.982  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:46:21.984  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:46:21.984  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:46:21.985  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:46:21.985  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:46:21.985  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:46:21.985  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:46:21.985  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:21.985  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:46:21.985  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:46:21.985  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e25640a removed from the list
09-28 09:46:21.986  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:21.986  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@422d47b removed from the list
,09-28 09:46:21.988  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:46:21.988  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:46:21.988  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:21.989  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:21.989  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:21.990  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:21.990  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:21.990  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:46:21.991  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@422d47b not in the list
09-28 09:46:21.991  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:21.991  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:21.992  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:21.992  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:46:21.992  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:21.993  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:46:21.993  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@422d47b not in the list
09-28 09:46:21.993  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:21.993  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:21.993  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:21.993  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e25640a not in the list
09-28 09:46:21.994  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 09:46:21.994  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cd3af1 added. We now have 3 listener(s)
09-28 09:46:21.996  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:46:21.996  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:46:21.996  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:46:21.996  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:46:21.996  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bdb6d6 added. We now have 4 listener(s)
09-28 09:46:21.996  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:46:21.997  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 09:46:22.000  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:22.005  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 09:46:22.008  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:22.008  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:46:22.008  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:46:22.008  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-28 09:46:22.008  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:46:22.008  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:22.009  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:46:22.011  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:46:22.012  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:22.013  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:46:22.015  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:22.017  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 09:46:22.017  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:46:22.018  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 09:46:22.021  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 09:46:22.021  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:46:22.021  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-28 09:46:22.021  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:46:22.024  5882  5893 D BtGatt.GattService: registerClient() - UUID=4890b3d3-5d54-43fe-8f28-5e004f7a95db
,09-28 09:46:22.026  5882  5898 D BtGatt.GattService: onClientRegistered() - UUID=4890b3d3-5d54-43fe-8f28-5e004f7a95db, clientIf=5
,09-28 09:46:22.027  5631  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 09:46:22.028  5882  5918 D BtGatt.GattService: start scan with filters
,09-28 09:46:22.032  5882  5901 D BtGatt.ScanManager: handling starting scan
09-28 09:46:22.032  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 09:46:22.032  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:46:22.032  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:46:22.032  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 09:46:22.033  5882  5901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4109e33
,09-28 09:46:22.034  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:46:22.035  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 09:46:22.035  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:46:22.036  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 09:46:22.039  5631  5677 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 09:46:22.039  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 09:46:22.039  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 09:46:22.039  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:22.039  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:46:22.039  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:46:22.039  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:46:22.039  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:46:22.040  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:46:22.040  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:46:22.040  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 09:46:22.040  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:22.041  5882  5898 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 09:46:22.041  5882  5919 D BtGatt.GattService: stopScan() - queue size =1
09-28 09:46:22.041  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:46:22.042  5882  5893 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 09:46:22.042  5882  5901 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 09:46:22.042  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:22.042  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:46:22.042  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 09:46:22.042  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:46:22.042  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 09:46:22.044  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:46:22.044  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:46:22.044  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 09:46:22.044  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:46:22.044  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:46:22.045  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:46:22.046  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:22.046  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:46:22.048  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:22.048  5882  5898 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 09:46:22.049  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:22.049  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:46:22.050  5882  5901 D BtGatt.ScanManager: Starting BLE batch scan
09-28 09:46:22.050  5882  5901 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 09:46:22.053  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:46:22.055  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:46:22.055  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:46:22.055  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 09:46:22.057  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:46:22.058  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 09:46:22.058  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:22.058  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:46:22.061  5882  5898 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 09:46:22.061  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:22.061  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:22.061  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:22.062  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:46:22.064  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:46:22.066  5882  5898 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 09:46:22.067  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:46:22.073  5882  5898 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 09:46:22.073  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:22.073  5882  5901 D BtGatt.ScanManager: stopping BLe Batch
,09-28 09:46:22.078  5882  5898 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:46:22.078  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:46:22.078  5882  5901 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 09:46:22.084  5882  5898 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 09:46:22.084  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:46:22.565  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:46:22.566  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:46:22.566  5631  5631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:46:25.046  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:46:25.046  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:46:25.046  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:46:25.047  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:46:25.047  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:25.047  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:46:25.047  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:46:25.047  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cd3af1 removed from the list
09-28 09:46:25.048  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:25.048  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bdb6d6 removed from the list
,09-28 09:46:25.048  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:46:25.048  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:25.050  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:25.050  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:25.054  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:46:25.054  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:46:25.055  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:46:25.056  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:46:25.056  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:46:25.057  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:25.057  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:25.057  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bdb6d6 not in the list
09-28 09:46:25.057  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:25.057  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:25.059  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:46:25.061  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:25.061  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:46:25.061  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:25.061  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:25.061  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:46:25.062  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:25.062  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bdb6d6 not in the list
,09-28 09:46:25.062  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:25.063  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:25.063  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:25.063  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cd3af1 not in the list
,09-28 09:46:25.064  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 09:46:25.064  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8af804f added. We now have 3 listener(s)
09-28 09:46:25.067  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:46:25.067  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:46:25.067  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:46:25.067  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:46:25.067  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebe3dc added. We now have 4 listener(s)
09-28 09:46:25.068  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:46:25.068  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 09:46:25.072  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:25.079  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:46:25.082  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:46:25.083  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:46:25.083  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 09:46:25.084  5631  5677 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-28 09:46:25.084  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-28 09:46:25.085  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 09:46:25.085  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 09:46:25.085  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 09:46:25.085  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:25.086  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 09:46:25.086  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 09:46:25.087  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 09:46:25.087  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 09:46:25.087  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 09:46:25.087  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:25.087  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:25.087  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:46:25.089  5631  5979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 09:46:25.090  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:25.091  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:46:25.092  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:46:25.092  5631  5631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-28 09:46:25.095  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:46:25.096  5631  5979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 09:46:25.091  5919  5919 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33701]" dev="sockfs" ino=33701 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 09:46:25.091  5919  5919 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33701]" dev="sockfs" ino=33701 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 09:46:25.096  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:46:25.096  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:46:25.098  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 09:46:25.099  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:46:25.099  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-28 09:46:25.100  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 09:46:25.100  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 09:46:25.100  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 09:46:25.101  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:46:25.106  5882  5918 D BtGatt.GattService: registerClient() - UUID=1e8a57dd-5d72-433b-9454-5688191ec625
09-28 09:46:25.107  5882  5898 D BtGatt.GattService: onClientRegistered() - UUID=1e8a57dd-5d72-433b-9454-5688191ec625, clientIf=5
09-28 09:46:25.107  5631  5641 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 09:46:25.109  5882  5900 D BtGatt.AdvertiseManager: message : 0
,09-28 09:46:25.111  5882  5900 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 09:46:25.121  5882  5898 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 09:46:25.127  5882  5898 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 09:46:25.128  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 09:46:25.129  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 09:46:25.131  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 09:46:25.132  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 09:46:25.133  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-28 09:46:25.133  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 09:46:25.133  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 09:46:25.133  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 09:46:25.133  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-28 09:46:25.134  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 09:46:25.136  5631  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-28 09:46:25.136  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 09:46:25.637  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-28 09:46:25.637  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 09:46:25.637  5631  5631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:46:28.135  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:46:28.136  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-28 09:46:28.136  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 09:46:28.136  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 09:46:28.136  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-28 09:46:28.137  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 09:46:28.137  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:46:28.137  5631  5979 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 09:46:28.137  5631  5677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 09:46:28.137  5631  5979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 09:46:28.138  5631  5979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 09:46:28.138  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:46:28.138  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 09:46:28.138  5631  5631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 09:46:28.138  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:46:28.138  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 09:46:28.138  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:46:28.141  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:28.141  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:46:28.141  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:28.141  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 09:46:28.143  5882  5900 D BtGatt.AdvertiseManager: message : 1
09-28 09:46:28.144  5882  5900 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 09:46:28.157  5882  5898 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-28 09:46:28.157  5882  5898 D BtGatt.GattService: Client app is not null!
09-28 09:46:28.158  5882  5893 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 09:46:28.159  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 09:46:28.159  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-28 09:46:28.159  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-28 09:46:28.160  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-28 09:46:28.160  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-28 09:46:28.162  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:46:28.162  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 09:46:28.163  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:28.164  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:46:28.166  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:28.166  5631  5631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 09:46:28.166  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:28.166  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:46:28.167  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:46:28.167  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:46:28.167  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8af804f removed from the list
09-28 09:46:28.167  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:28.167  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:28.167  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:46:28.167  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebe3dc removed from the list
09-28 09:46:28.167  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:46:28.167  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 09:46:28.171  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:28.172  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:46:28.178  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:46:28.180  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:46:28.180  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:46:28.180  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:28.181  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:28.183  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:28.183  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:28.185  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 09:46:28.185  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 09:46:28.185  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:28.186  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:28.186  5631  5677 D BluetoothLeScanner: could not find callback wrapper
,09-28 09:46:28.186  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:28.187  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:28.187  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:46:28.187  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebe3dc not in the list
09-28 09:46:28.187  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:28.187  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:46:28.192  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:28.192  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:28.193  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:28.195  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 09:46:28.195  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:28.195  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:28.197  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:28.198  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:28.198  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:46:28.198  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:28.198  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:28.198  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:46:28.198  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:28.198  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebe3dc not in the list
09-28 09:46:28.198  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:28.198  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:28.198  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:28.199  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8af804f not in the list
09-28 09:46:28.199  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 09:46:28.200  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@187239d added. We now have 3 listener(s)
09-28 09:46:28.202  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:46:28.202  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 09:46:28.202  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:46:28.202  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:46:28.202  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd23012 added. We now have 4 listener(s)
,09-28 09:46:28.203  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 09:46:28.203  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 09:46:28.207  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:28.213  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:46:28.215  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 09:46:28.216  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:46:28.216  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:46:28.216  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 09:46:28.216  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 09:46:28.216  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:28.216  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:46:28.219  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:28.221  5631  5677 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 09:46:28.221  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 09:46:28.223  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 09:46:28.226  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:46:28.227  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:46:28.227  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 09:46:28.231  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 09:46:28.232  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 09:46:28.232  5631  5677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-28 09:46:28.233  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:46:28.237  5882  5893 D BtGatt.GattService: registerClient() - UUID=7931c16d-6412-48dd-bb12-2314ffc64cc8
,09-28 09:46:28.237  5882  5898 D BtGatt.GattService: onClientRegistered() - UUID=7931c16d-6412-48dd-bb12-2314ffc64cc8, clientIf=5
09-28 09:46:28.238  5631  5642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 09:46:28.238  5882  5918 D BtGatt.GattService: start scan with filters
,09-28 09:46:28.241  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 09:46:28.241  5882  5901 D BtGatt.ScanManager: handling starting scan
,09-28 09:46:28.241  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 09:46:28.241  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 09:46:28.241  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 09:46:28.244  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 09:46:28.245  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 09:46:28.245  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 09:46:28.246  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 09:46:28.249  5882  5898 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 09:46:28.249  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:28.250  5882  5901 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 09:46:28.256  5882  5898 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 09:46:28.256  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:28.257  5882  5901 D BtGatt.ScanManager: Starting BLE batch scan
,09-28 09:46:28.257  5882  5901 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 09:46:28.268  5882  5898 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 09:46:28.268  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:46:28.275  5882  5898 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 09:46:28.275  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 09:46:28.697  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:46:28.745  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 09:46:28.745  5631  5631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:46:28.745  5631  5631 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 09:46:30.722   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:46:31.256  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 09:46:31.257  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:46:31.257  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 09:46:31.257  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:31.257  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:46:31.257  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 09:46:31.257  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 09:46:31.258  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 09:46:31.258  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 09:46:31.258  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 09:46:31.258  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 09:46:31.262  5631  5677 D BluetoothAdapter: STATE_ON
,09-28 09:46:31.264  5882  5919 D BtGatt.GattService: stopScan() - queue size =1
,09-28 09:46:31.266  5882  5909 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 09:46:31.267  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 09:46:31.267  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 09:46:31.267  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 09:46:31.267  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 09:46:31.268  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 09:46:31.271  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:46:31.271  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 09:46:31.272  5631  5677 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 09:46:31.272  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:31.274  5882  5882 D BtGatt.ScanManager: awakened up at time 328761
,09-28 09:46:31.274  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:46:31.278  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:46:31.278  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:31.278  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 09:46:31.278  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:31.280  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:31.280  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 09:46:31.280  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:46:31.280  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@187239d removed from the list
09-28 09:46:31.280  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:31.280  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd23012 removed from the list
,09-28 09:46:31.280  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:46:31.280  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:46:31.283  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:31.283  5631  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 09:46:31.285  5882  5898 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 09:46:31.285  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:31.285  5882  5901 D BtGatt.ScanManager: stopping BLe Batch
,09-28 09:46:31.288  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 09:46:31.289  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 09:46:31.289  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 09:46:31.289  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:31.290  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:31.294  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:31.294  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:31.295  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:31.295  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:46:31.296  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:31.296  5882  5898 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 09:46:31.296  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:31.296  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:31.296  5882  5901 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 09:46:31.296  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:46:31.296  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:31.297  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 09:46:31.297  5631  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 09:46:31.297  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd23012 not in the list
09-28 09:46:31.297  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 09:46:31.297  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 09:46:31.301  5631  5631 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 09:46:31.302  5631  5631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 09:46:31.302  5631  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:31.305  5631  5631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 09:46:31.305  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:31.305  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:31.306  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 09:46:31.308  5631  5677 D BluetoothAdapter: STATE_ON
09-28 09:46:31.308  5631  5677 D BluetoothLeScanner: could not find callback wrapper
09-28 09:46:31.308  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 09:46:31.308  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:31.308  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 09:46:31.308  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:31.309  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd23012 not in the list
09-28 09:46:31.309  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 09:46:31.309  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:31.309  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:31.309  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@187239d not in the list
,09-28 09:46:31.310  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 09:46:31.310  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c2c5b added. We now have 3 listener(s)
09-28 09:46:31.312  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 09:46:31.312  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 09:46:31.312  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 09:46:31.312  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 09:46:31.312  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4ccf8 added. We now have 4 listener(s)
09-28 09:46:31.312  5631  5677 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 09:46:31.313  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 09:46:31.316  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 09:46:31.320  5882  5898 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-28 09:46:31.321  5882  5898 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 09:46:31.321  5882  5898 D BtGatt.GattService: current time is 328808719206
09-28 09:46:31.321  5882  5898 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -74, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -75, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -71, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-28 09:46:31.323  5882  5898 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 09:46:31.324  5882  5898 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 09:46:31.325  5882  5898 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 09:46:31.325  5882  5898 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 09:46:31.325  5882  5898 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 09:46:31.326  5631  5677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 09:46:31.328  5631  5677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 09:46:31.328  5631  5677 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 09:46:31.328  5631  5677 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 09:46:31.329  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 09:46:31.329  5631  5677 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 09:46:31.329  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:31.329  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 09:46:31.329  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 09:46:31.330  5631  5677 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 09:46:31.330  5631  5677 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c2c5b removed from the list
09-28 09:46:31.330  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:31.330  5631  5677 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4ccf8 removed from the list
,09-28 09:46:31.331  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:46:31.331  5631  5677 D io.jxcore.node.ConnectivityMonitor: stop
09-28 09:46:31.331  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 09:46:31.332  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:31.332  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:31.333  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:31.333  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:31.333  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:31.333  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4ccf8 not in the list
09-28 09:46:31.333  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:31.333  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:31.334  5631  5631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 09:46:31.335  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 09:46:31.335  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 09:46:31.335  5631  5677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 09:46:31.335  5631  5677 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4ccf8 not in the list
09-28 09:46:31.335  5631  5677 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 09:46:31.335  5631  5677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 09:46:31.335  5631  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 09:46:31.335  5631  5677 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c2c5b not in the list
,09-28 09:46:31.336  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-28 09:46:31.336  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 09:46:31.336  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 09:46:31.336  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 09:46:31.336  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 09:46:31.336  5631  5677 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 09:46:31.806  5631  5631 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 09:46:32.055   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 09:46:32.055   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 09:46:33.348  5631  5981 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: My test thread name)
,09-28 09:46:33.754   926  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 09:46:35.347  5631  5677 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 190
,09-28 09:46:35.347  5631  5677 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 190, name: My test thread name)
,09-28 09:46:35.352  5631  5982 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
09-28 09:46:35.352  5631  5982 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: My test thread name)
,09-28 09:46:35.353  5631  5982 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-28 09:46:35.357  5631  5677 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 09:46:35.363  5631  5983 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name)
09-28 09:46:35.363  5631  5983 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 195, thread name: My test thread name): Test exception.
,09-28 09:46:35.364  5631  5983 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 09:46:35.374  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-28 09:46:35.374  5631  5677 I jxcore-log: 
,09-28 09:46:35.376  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-28 09:46:35.376  5631  5677 I jxcore-log: 
,09-28 09:46:35.378  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-28 09:46:35.378  5631  5677 I jxcore-log: 
,09-28 09:46:35.380  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-28 09:46:35.380  5631  5677 I jxcore-log: 
,09-28 09:46:35.383  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Total duration:  101031'
09-28 09:46:35.383  5631  5677 I jxcore-log: 
,09-28 09:46:35.392  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-28 09:46:35.392  5631  5677 I jxcore-log: 
,09-28 09:46:35.400  5631  5981 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-28 09:46:35.402  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.402  5631  5677 I jxcore-log: 
,09-28 09:46:35.405  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.405  5631  5677 I jxcore-log: 
,09-28 09:46:35.407  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.407  5631  5677 I jxcore-log: 
,09-28 09:46:35.408  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.408  5631  5677 I jxcore-log: 
09-28 09:46:35.409  5631  5631 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-28 09:46:35.410  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 09:46:35.410  5631  5677 I jxcore-log: 
,09-28 09:46:35.411  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 09:46:35.411  5631  5677 I jxcore-log: 
,09-28 09:46:35.413  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.413  5631  5677 I jxcore-log: 
,09-28 09:46:35.414  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.414  5631  5677 I jxcore-log: 
,09-28 09:46:35.415  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 09:46:35.415  5631  5677 I jxcore-log: 
09-28 09:46:35.415  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 09:46:35.415  5631  5677 I jxcore-log: 
,09-28 09:46:35.416  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 09:46:35.416  5631  5677 I jxcore-log: 
,09-28 09:46:35.417  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.417  5631  5677 I jxcore-log: 
09-28 09:46:35.418  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.418  5631  5677 I jxcore-log: 
,09-28 09:46:35.419  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.419  5631  5677 I jxcore-log: 
,09-28 09:46:35.420  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.420  5631  5677 I jxcore-log: 
09-28 09:46:35.421  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.421  5631  5677 I jxcore-log: 
,09-28 09:46:35.423  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.423  5631  5677 I jxcore-log: 
09-28 09:46:35.424  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.424  5631  5677 I jxcore-log: 
,09-28 09:46:35.425  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.425  5631  5677 I jxcore-log: 
09-28 09:46:35.426  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.426  5631  5677 I jxcore-log: 
,09-28 09:46:35.427  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.427  5631  5677 I jxcore-log: 
,09-28 09:46:35.428  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.428  5631  5677 I jxcore-log: 
09-28 09:46:35.428  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.428  5631  5677 I jxcore-log: 
,09-28 09:46:35.432  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.432  5631  5677 I jxcore-log: 
,09-28 09:46:35.433  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.433  5631  5677 I jxcore-log: 
,09-28 09:46:35.434  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.434  5631  5677 I jxcore-log: 
,09-28 09:46:35.435  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.435  5631  5677 I jxcore-log: 
,09-28 09:46:35.436  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.436  5631  5677 I jxcore-log: 
,09-28 09:46:35.437  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.437  5631  5677 I jxcore-log: 
09-28 09:46:35.437  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.437  5631  5677 I jxcore-log: 
09-28 09:46:35.438  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.438  5631  5677 I jxcore-log: 
09-28 09:46:35.438  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.438  5631  5677 I jxcore-log: 
09-28 09:46:35.439  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.439  5631  5677 I jxcore-log: 
,09-28 09:46:35.440  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.440  5631  5677 I jxcore-log: 
,09-28 09:46:35.441  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.441  5631  5677 I jxcore-log: 
09-28 09:46:35.441  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.441  5631  5677 I jxcore-log: 
09-28 09:46:35.442  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.442  5631  5677 I jxcore-log: 
,09-28 09:46:35.443  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.443  5631  5677 I jxcore-log: 
,09-28 09:46:35.444  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.444  5631  5677 I jxcore-log: 
09-28 09:46:35.445  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 09:46:35.445  5631  5677 I jxcore-log: 
,09-28 09:46:35.445  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.445  5631  5677 I jxcore-log: 
,09-28 09:46:35.446  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 09:46:35.446  5631  5677 I jxcore-log: 
09-28 09:46:35.447  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.447  5631  5677 I jxcore-log: 
,09-28 09:46:35.447  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.447  5631  5677 I jxcore-log: 
09-28 09:46:35.448  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.448  5631  5677 I jxcore-log: 
,09-28 09:46:35.449  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.449  5631  5677 I jxcore-log: 
,09-28 09:46:35.449  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.449  5631  5677 I jxcore-log: 
09-28 09:46:35.450  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 09:46:35.450  5631  5677 I jxcore-log: 
,09-28 09:46:35.451  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.451  5631  5677 I jxcore-log: 
09-28 09:46:35.451  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-28 09:46:35.451  5631  5677 I jxcore-log: 
,09-28 09:46:35.452  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.452  5631  5677 I jxcore-log: 
,09-28 09:46:35.453  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 09:46:35.453  5631  5677 I jxcore-log: 
09-28 09:46:35.453  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 09:46:35.453  5631  5677 I jxcore-log: 
,09-28 09:46:35.454  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 09:46:35.454  5631  5677 I jxcore-log: 
09-28 09:46:35.455  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 09:46:35.455  5631  5677 I jxcore-log: 
,09-28 09:46:35.458  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-28 09:46:35.458  5631  5677 I jxcore-log: 
,09-28 09:46:35.459  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - WARN testUtils: 'myNameCallback not set!'
09-28 09:46:35.459  5631  5677 I jxcore-log: 
,09-28 09:46:35.460  5631  5677 I jxcore-log: 2016-09-28 13:46:35 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-28 09:46:35.460  5631  5677 I jxcore-log: 
,09-28 09:46:37.475  5631  5677 I jxcore-log: 2016-09-28 13:46:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-28 09:46:37.475  5631  5677 I jxcore-log: 
,09-28 09:46:37.792  5631  5677 I jxcore-log: 2016-09-28 13:46:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-28 09:46:37.792  5631  5677 I jxcore-log: 
,09-28 09:46:37.807  5631  5677 I jxcore-log: 2016-09-28 13:46:37 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-28 09:46:37.807  5631  5677 I jxcore-log: 
,09-28 09:46:38.909  5631  5677 I jxcore-log: 2016-09-28 13:46:38 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-28 09:46:38.909  5631  5677 I jxcore-log: 
,09-28 09:46:39.058  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-28 09:46:39.058  5631  5677 I jxcore-log: 
,09-28 09:46:39.063  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-28 09:46:39.063  5631  5677 I jxcore-log: 
,09-28 09:46:39.075  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-28 09:46:39.075  5631  5677 I jxcore-log: 
,09-28 09:46:39.336   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=336823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:46:39.605  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-28 09:46:39.605  5631  5677 I jxcore-log: 
,09-28 09:46:39.655  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-28 09:46:39.655  5631  5677 I jxcore-log: 
,09-28 09:46:39.667  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-28 09:46:39.667  5631  5677 I jxcore-log: 
,09-28 09:46:39.671  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-28 09:46:39.671  5631  5677 I jxcore-log: 
,09-28 09:46:39.929  5631  5677 I jxcore-log: 2016-09-28 13:46:39 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-28 09:46:39.929  5631  5677 I jxcore-log: 
,09-28 09:46:40.048  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-28 09:46:40.048  5631  5677 I jxcore-log: 
,09-28 09:46:40.273  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-28 09:46:40.273  5631  5677 I jxcore-log: 
,09-28 09:46:40.284  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-28 09:46:40.284  5631  5677 I jxcore-log: 
,09-28 09:46:40.290  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-28 09:46:40.290  5631  5677 I jxcore-log: 
,09-28 09:46:40.296  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-28 09:46:40.296  5631  5677 I jxcore-log: 
,09-28 09:46:40.326  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-28 09:46:40.326  5631  5677 I jxcore-log: 
,09-28 09:46:40.363  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-28 09:46:40.363  5631  5677 I jxcore-log: 
,09-28 09:46:40.370  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-28 09:46:40.370  5631  5677 I jxcore-log: 
,09-28 09:46:40.377  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-28 09:46:40.377  5631  5677 I jxcore-log: 
,09-28 09:46:40.392  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-28 09:46:40.392  5631  5677 I jxcore-log: 
,09-28 09:46:40.397  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-28 09:46:40.397  5631  5677 I jxcore-log: 
,09-28 09:46:40.403  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-28 09:46:40.403  5631  5677 I jxcore-log: 
,09-28 09:46:40.416  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-28 09:46:40.416  5631  5677 I jxcore-log: 
,09-28 09:46:40.437  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-28 09:46:40.437  5631  5677 I jxcore-log: 
,09-28 09:46:40.447  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-28 09:46:40.447  5631  5677 I jxcore-log: 
,09-28 09:46:40.457  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-28 09:46:40.457  5631  5677 I jxcore-log: 
,09-28 09:46:40.467  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-28 09:46:40.467  5631  5677 I jxcore-log: 
,09-28 09:46:40.479  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-28 09:46:40.479  5631  5677 I jxcore-log: 
,09-28 09:46:40.489  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-28 09:46:40.489  5631  5677 I jxcore-log: 
,09-28 09:46:40.494  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-28 09:46:40.494  5631  5677 I jxcore-log: 
,09-28 09:46:40.513  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-28 09:46:40.513  5631  5677 I jxcore-log: 
,09-28 09:46:40.521  5631  5677 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-28 09:46:40.522  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - INFO testUtils: 'BLE multiple advertisement supported'
09-28 09:46:40.522  5631  5677 I jxcore-log: 
,09-28 09:46:40.786  5631  5677 I jxcore-log: 2016-09-28 13:46:40 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:46:40.786  5631  5677 I jxcore-log: 
,09-28 09:46:45.590   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:46:47.057   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:48.058   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:49.060   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:49.744   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:46:50.061   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:51.062   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:52.063   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 09:46:57.065   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:58.066   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:46:59.067   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:00.068   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:01.070   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:02.070   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 09:47:05.710   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=363197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:47:10.777   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=368264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:47:12.072   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:13.073   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:14.074   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:15.075   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:16.076   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:17.076   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 09:47:29.749   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:47:30.830   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:47:32.077   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:33.078   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:34.080   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:35.081   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:35.844   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=393331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:47:36.083   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:37.084   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 09:47:49.750   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:47:55.897   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=413384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:47:57.085   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:58.087   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:47:59.088   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:00.089   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:00.937   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:48:01.090   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:02.091   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 09:48:20.963   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=438450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:48:25.990   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-28 09:48:27.092   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 09:48:27.092   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 09:48:29.753   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:48:47.094   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:48.095   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:49.096   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:49.756   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:48:50.097   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:51.098   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:52.099   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 09:48:57.100   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:58.101   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:48:59.103   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:00.103   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:01.105   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:02.106   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 09:49:09.757   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 09:49:11.043   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=488530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:49:12.107   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:13.109   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:14.110   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:15.111   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:16.057   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=493544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 09:49:16.113   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:17.114   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 09:49:32.115   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:33.117   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:34.118   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:34.942  5631  5677 I jxcore-log: 2016-09-28 13:49:34 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-28 09:49:34.942  5631  5677 I jxcore-log: 
,09-28 09:49:35.120   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:35.208  5631  5677 I jxcore-log: 2016-09-28 13:49:35 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:35.208  5631  5677 I jxcore-log: 
,09-28 09:49:35.220  5631  5677 I jxcore-log: 2016-09-28 13:49:35 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:35.220  5631  5677 I jxcore-log: 
,09-28 09:49:35.530  5631  5677 I jxcore-log: 2016-09-28 13:49:35 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:35.530  5631  5677 I jxcore-log: 
,09-28 09:49:35.540  5631  5677 I jxcore-log: 2016-09-28 13:49:35 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:35.540  5631  5677 I jxcore-log: 
,09-28 09:49:36.056   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=513543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 09:49:36.101  5631  5677 I jxcore-log: 2016-09-28 13:49:36 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:36.101  5631  5677 I jxcore-log: 
09-28 09:49:36.107  5631  5677 I jxcore-log: 2016-09-28 13:49:36 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:36.107  5631  5677 I jxcore-log: 
,09-28 09:49:36.120   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 09:49:37.121   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 09:49:37.147  5631  5677 I jxcore-log: 2016-09-28 13:49:37 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:37.147  5631  5677 I jxcore-log: 
,09-28 09:49:37.155  5631  5677 I jxcore-log: 2016-09-28 13:49:37 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:37.155  5631  5677 I jxcore-log: 
,09-28 09:49:38.193  5631  5677 I jxcore-log: 2016-09-28 13:49:38 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:38.193  5631  5677 I jxcore-log: 
,09-28 09:49:38.199  5631  5677 I jxcore-log: 2016-09-28 13:49:38 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:38.199  5631  5677 I jxcore-log: 
,09-28 09:49:39.240  5631  5677 I jxcore-log: 2016-09-28 13:49:39 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:39.240  5631  5677 I jxcore-log: 
,09-28 09:49:39.249  5631  5677 I jxcore-log: 2016-09-28 13:49:39 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:39.249  5631  5677 I jxcore-log: 
,09-28 09:49:40.297  5631  5677 I jxcore-log: 2016-09-28 13:49:40 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:40.297  5631  5677 I jxcore-log: 
,09-28 09:49:40.306  5631  5677 I jxcore-log: 2016-09-28 13:49:40 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:40.306  5631  5677 I jxcore-log: 
,09-28 09:49:41.097   926  5941 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-28 09:49:41.346  5631  5677 I jxcore-log: 2016-09-28 13:49:41 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:41.346  5631  5677 I jxcore-log: 
,09-28 09:49:41.353  5631  5677 I jxcore-log: 2016-09-28 13:49:41 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:41.353  5631  5677 I jxcore-log: 
,09-28 09:49:42.389  5631  5677 I jxcore-log: 2016-09-28 13:49:42 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:42.389  5631  5677 I jxcore-log: 
,09-28 09:49:42.395  5631  5677 I jxcore-log: 2016-09-28 13:49:42 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:42.395  5631  5677 I jxcore-log: 
,09-28 09:49:43.468  5631  5677 I jxcore-log: 2016-09-28 13:49:43 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:43.468  5631  5677 I jxcore-log: 
,09-28 09:49:43.476  5631  5677 I jxcore-log: 2016-09-28 13:49:43 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:43.476  5631  5677 I jxcore-log: 
,09-28 09:49:44.512  5631  5677 I jxcore-log: 2016-09-28 13:49:44 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:44.512  5631  5677 I jxcore-log: 
,09-28 09:49:44.520  5631  5677 I jxcore-log: 2016-09-28 13:49:44 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:44.520  5631  5677 I jxcore-log: 
,09-28 09:49:45.555  5631  5677 I jxcore-log: 2016-09-28 13:49:45 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:45.555  5631  5677 I jxcore-log: 
,09-28 09:49:45.563  5631  5677 I jxcore-log: 2016-09-28 13:49:45 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:45.563  5631  5677 I jxcore-log: 
,09-28 09:49:46.607  5631  5677 I jxcore-log: 2016-09-28 13:49:46 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:46.607  5631  5677 I jxcore-log: 
,09-28 09:49:46.616  5631  5677 I jxcore-log: 2016-09-28 13:49:46 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:46.616  5631  5677 I jxcore-log: 
,09-28 09:49:47.650  5631  5677 I jxcore-log: 2016-09-28 13:49:47 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:47.650  5631  5677 I jxcore-log: 
,09-28 09:49:47.658  5631  5677 I jxcore-log: 2016-09-28 13:49:47 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:47.658  5631  5677 I jxcore-log: 
,09-28 09:49:48.692  5631  5677 I jxcore-log: 2016-09-28 13:49:48 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 09:49:48.692  5631  5677 I jxcore-log: 
,09-28 09:49:48.700  5631  5677 I jxcore-log: 2016-09-28 13:49:48 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-28 09:49:48.700  5631  5677 I jxcore-log: 
,09-28 09:49:49.761   926  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437

```
